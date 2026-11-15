2026-11-15 – Anonymous GET /recipes → 200 OK, returns full recipe list
2026-11-15 – Anonymous PATCH /recipes/2 → 200 OK, title changed, confirmed by GET /recipes/2
2026-11-15 – Anonymous DELETE /recipes/<id> → 204 No Content, later GET → 404 Not Found
