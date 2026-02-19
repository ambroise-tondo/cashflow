# SPEC — Cash-in / Payments MVP (Africa-first)

Goal: Simple B2B SaaS to track incoming payments and unpaid balances, with minimal data entry.

MVP features:
- Auth (email + password OK for MVP)
- Add payment in a very fast flow (3-click spirit):
  - amount, date, payment method, reference/note, status (paid/partial/unpaid)
  - optional client name as plain text (no CRM required)
- List payments + filters
- Dashboard: totals day/week/month + unpaid total
- PDF report export
- WhatsApp reminder link (pre-filled message)

Out of scope (do not build in MVP):
- Product catalog, inventory, full CRM, ERP features
- Operator API integrations (later phase only)
