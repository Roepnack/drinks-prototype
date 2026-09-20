# Drinks

A cocktail-tracking app prototype — a single self-contained HTML file, no
build step, no backend. Browse a searchable list of classic cocktails and
their ingredients, and track a bar's stock.

## Running it

Open `index.html` directly in a browser (works from the filesystem, no
server needed) or from a phone over a local network:

```
python3 -m http.server 8000
```

then visit `http://<your-ip>:8000/index.html` on the phone.

Demo data is seeded on first load. Data is stored in `localStorage`, so
nothing leaves your device.
