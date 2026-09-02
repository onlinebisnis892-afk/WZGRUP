# WZ MANAGE PRO — ONLINE (SAME FEATURES/UI)

This package uses the original WZ MANAGE PRO offline HTML as the frontend master.
The UI, menus, data fixtures, and existing JavaScript workflows are preserved.
An additive online compatibility layer is appended at the end.

Online API is optional until a database/API is connected:
- localStorage/sessionStorage remain the fallback
- when WZ_ONLINE_API is configured, saves attempt POST /api/sync
- failed online sync never deletes or replaces local data

This package is intentionally NOT a claim that a production database is connected.
