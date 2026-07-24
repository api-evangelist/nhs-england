---
name: Notify a citizen through the NHS App
description: Send a message to a citizen via the NHS App and reconcile delivery outcomes with receipts and callbacks.
api: openapi/nhs-app-openapi.yaml
operations: [create-notification, create-in-app, get-receipt-report, get-patient-report]
---

# Notify a citizen through the NHS App

Use the **NHS App API** to deliver messages/content to citizens and reconcile the outcomes.

## Preconditions
- OAuth 2.0 bearer token; base `/nhs-app`. The integrating partner is onboarded and (for real-time receipts) has registered a callback endpoint + certificate with the NHS App team.

## Steps
1. Acquire an access token; set `Authorization: Bearer <token>` and an `X-Correlation-ID` (echoed on the response for tracing).
2. Send a notification with **`create-notification`**, or create an in-app message with **`create-in-app`**.
3. Reconcile outcomes: pull the daily **`get-receipt-report`**, and/or subscribe to real-time receipts so NHS pushes FHIR `Task` resources to your callback endpoint (see asyncapi/nhs-england-webhooks.yml).
4. Use **`get-patient-report`** for patient-level reporting.

## Error handling
- `400` validation, `401`/`403` auth, `429` throttled (honour `Retry-After`). See errors/nhs-england-problem-types.yml.
