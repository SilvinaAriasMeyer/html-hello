# Social Commerce Dashboard (HTML + Tailwind CSS v4)

Proyecto reiniciado para usar unicamente HTML semantico y Tailwind CSS v4 compilado en local (sin CDN).

## Requisitos

- Node.js 18+
- Python 3 (opcional, solo para correr `server.py`)

## Instalacion

```bash
npm install
npm run build:css
```

Esto genera `styles.css` desde `src/input.css` usando Tailwind v4 CLI.

## Desarrollo

1. En una terminal, recompila CSS en modo watch:

```bash
npm run watch:css
```

2. En otra terminal, levanta el servidor:

```bash
python3 server.py
```

3. Abre `http://localhost:3000`.

## Estructura

- `index.html`: dashboard responsive mobile-first.
- `src/input.css`: entrada de Tailwind v4 (`@import "tailwindcss";`).
- `styles.css`: CSS compilado.
- `package.json`: scripts y dependencias de Tailwind v4.

## Nota importante

Esta base no usa `cdn.tailwindcss.com` ni la sintaxis/configuracion de Tailwind v3.
