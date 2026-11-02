# Bedesi — Luxury Heritage Customer Ordering App

A mobile-first customer ordering PWA styled around the actual Bedesi restaurant interior: deep navy woodwork, ivory walls, terracotta roof accents, brass details and warm wood tones.

## Customer features
- Premium mobile-first home and menu experience
- Real Bedesi interior photograph integrated into the welcome banner
- Search, categories and vegetarian / egg / non-vegetarian filters
- Popular, New and Offers menu views
- Item details, favourites and quantity controls
- Table number selection, cart and checkout flow
- Local order history and saved cart
- PWA manifest and service worker for installation / app shell caching

## Run locally
Run a local server from this folder:

```bash
python -m http.server 8080
```

Open `http://localhost:8080` in a browser.

## Install on Android
Deploy the complete folder to an HTTPS host, open it in Chrome on Android, then choose **Install app** or **Add to Home screen**.

## Prototype boundary
Orders and cart are stored in the current browser/device only. The demo does not send orders to a kitchen/admin panel and has no live database, user authentication, payment gateway or real-time order status. These require a backend/API integration.
