# Finance Studio

Budgets, forecasts, billing and payroll

Plan budgets, track expenses, and build financial models and forecasts. Manage cash flow, P&L, and balance sheet reporting, run payroll and vendor payments, set expense approval workflows, and monitor it all with dashboards and audit trails.

## Microservices Used

**Platform baseline** (common to every app & studio): `gateway-service`, `authentication-service`, `identity-service`, `access-service`, `security-service`, `audit-service`, `observability-service`, `control-service`, `deployment-service`, `integration-service`, `storage-service`, `reporting-service`, `analytics-service`, `notification-service`

**Functional services (6):**

| Service | Status |
|---|---|
| `finance-service` | Core |
| `ledger-service` | New (Tier-1) |
| `billing-service` | Core |
| `payment-service` | Core |
| `tax-service` | New (Tier-1) |
| `document-service` | Core |
