# API

## GET /health

Returns project, network, and service status.

## GET /api/actions

Returns seeded remittance records.

## POST /api/actions/quote

Accepts:

```json
{
  "recordId": "ofw-insurance-premium-collector-001",
  "amount": "125.50",
  "asset": "XLM",
  "destination": "G..."
}
```

Returns a Stellar-oriented quote with memo, SEP-7 URI, and Soroban method name.
