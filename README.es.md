# Dashboard Social Commerce (HTML + Tailwind CSS v4)

Proyecto reiniciado para usar solo HTML y Tailwind CSS v4 compilado localmente, sin CDN.

## Requisitos

- Node.js 18+
- Python 3 (opcional para `server.py`)

## Instalacion

```bash
npm install
npm run build:css
```

Con esto se genera `styles.css` a partir de `src/input.css`.

## Flujo de trabajo

1. Ejecuta Tailwind en modo watch:

```bash
npm run watch:css
```

2. Levanta el servidor local:

```bash
python3 server.py
```

3. Abre `http://localhost:3000`.

## Estructura

- `index.html`: dashboard responsive (mobile-first).
- `src/input.css`: entrada para Tailwind v4.
- `styles.css`: salida compilada.
- `package.json`: scripts y dependencias.

## Nota

No se usa `cdn.tailwindcss.com` ni configuracion de Tailwind v3.
