# Architecture

Current: browser inputs → numeric validation → KPI calculations; synthetic service tasks → status changes and category filters; both → local CSV export. No external requests, persistent storage, authenticated roles, guest communications, or live integrations.

Future: authorized PMS integration → room and revenue updates; persistent service workboard → role-based assignment and timestamps; reviewed reports → shared operational decisions. Separate available inventory from out-of-order rooms and establish consistent revenue/cost accounting definitions before comparing periods.

No guest identity is needed for the public demo. User-entered task text is displayed through textContent. CSV cells are escaped, with leading formula characters prefixed.
