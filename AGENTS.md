# AGENTS.md — Rules for this repo

## Non-negotiables
- MVP is NOT an ERP.
- Progressive structuring: user can record money without creating customers/products.
- Mobile-first UI.
- Do not add features outside SPEC.md without asking for approval.

## Engineering rules
- Use Laravel conventions.
- Prefer Blade + Tailwind for MVP speed.
- Always add migrations and tests for core flows.
- Always run:
  - ./vendor/bin/sail artisan migrate
  - ./vendor/bin/sail test
- If tests fail: fix until green.

## Approval checkpoints (MUST STOP)
1) After proposing the database schema (tables + columns).
2) After the first working "Add Payment" fast entry flow exists.
3) Before adding PDF export + WhatsApp reminder.

