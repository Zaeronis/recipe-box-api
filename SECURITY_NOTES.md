2026-11-08
- GET /recipes -> 200 OK, returns all recipes including is_public=false (secret sauce).
- POST /recipes -> 201 CREATED, anonymous client can create new recipe records.
- PATCH /recipes/4 -> 200 OK, anonymous client can modify existing recipe by id.
- DELETE /recipes/4 -> 204 NO CONTENT, anonymous client can delete recipes by id.
