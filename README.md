# Hotel IN Žepče — web stranica

Statična stranica. Nema build koraka.

## Struktura
- `index.html` — cijela stranica
- `support.js` — runtime potreban za `index.html`
- `assets/` — fotografije

## Lokalno pokretanje
Otvori `index.html` u browseru, ili posluži folder:

```
python3 -m http.server 8000
```

## GitHub Pages
1. Push sadržaj ovog foldera u root repozitorija.
2. Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
