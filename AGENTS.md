# Star Dash

A single-file HTML5 canvas game (`index.html`) — no backend, no build step, no dependencies.

## Running

```
docker compose -f docker-compose.base44.yml up -d
```

Serves `index.html` via nginx:alpine on host port 3000. No credentials needed.

## Editing

All game logic is inline in `index.html` (one `<script>` block, ~1000 lines). Edit the file and reload the preview — nginx serves it live.
