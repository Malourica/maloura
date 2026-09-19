# Maloura

Maloura is a mobile-first Version 0.1 prototype for a local delivery business and its connected idea-to-revenue operating loop.

## Run locally

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173` in a browser. The app is dependency-free and uses hash routes, so it can be hosted as a static site.

## Included routes

- `/` landing page
- `/services` service catalog
- `/request` delivery request form and pricing estimate
- `/orders` customer order dashboard
- `/admin` revenue, order, and performance dashboard
- `/ideas`, `/research`, `/projects` connected planning library

Delivery requests are stored in `localStorage` under `maloura.delivery_requests` for this prototype. The stored shape is ready to move into a `delivery_requests` table alongside `users`, `services`, `riders`, `orders`, `payments`, `ideas`, `research`, `projects`, and `expenses`.# maloura