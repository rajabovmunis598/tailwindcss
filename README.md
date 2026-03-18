# Beautysalon — Tailwind CSS (Node.js)

Ин проект дар ду версияи Tailwind CSS омода шудааст.

---

## 📁 Сохтори пурраи проект

```
beautysalon/
│
├── tailwind-v3/                  ← Tailwind CSS v3
│   ├── package.json              ← npm скриптҳо ва dependencies
│   ├── tailwind.config.js        ← кастомизацияи рангҳо ва сояҳо
│   └── src/
│       ├── index.html            ← саҳифаи асосӣ
│       ├── input.css             ← манбаъи CSS (@tailwind directives)
│       ├── output.css            ← автоматик месозад (git-га нагузоред)
│       ├── Logo (5).png
│       ├── Logo (6).png
│       ├── Img (15).png
│       ├── Img (16).png
│       ├── Img (17).png
│       ├── Icon (6).png
│       ├── Icon (7).png
│       ├── Icon (8).png
│       ├── Icon (9).png
│       ├── Avatar.png
│       ├── Client.png
│       ├── Dots.png
│       ├── Shape.png
│       ├── Redes sociais.png
│       ├── phone 1.png
│       ├── map-pin 1.png
│       └── mail 1.png
│
└── tailwind-v4/                  ← Tailwind CSS v4
    ├── package.json              ← npm скриптҳо ва dependencies
    └── src/
        ├── index.html            ← саҳифаи асосӣ
        ├── input.css             ← @import "tailwindcss" + @theme {}
        ├── output.css            ← автоматик месозад (git-га нагузоред)
        ├── Logo (5).png
        ├── Logo (6).png
        ├── Img (15).png
        ├── Img (16).png
        ├── Img (17).png
        ├── Icon (6).png
        ├── Icon (7).png
        ├── Icon (8).png
        ├── Icon (9).png
        ├── Avatar.png
        ├── Client.png
        ├── Dots.png
        ├── Shape.png
        ├── Redes sociais.png
        ├── phone 1.png
        ├── map-pin 1.png
        └── mail 1.png
```

---

## 🚀 Чӣ тавр истифода кард

### Tailwind v3

```bash
cd tailwind-v3
npm install
npm run build       # як маротиба build кунед
npm run dev         # ё watch mode барои таҳия
```

Файлҳо:
- `src/input.css`  → манбаъ
- `src/output.css` → автоматик месозад (HTML-ро аз ин истифода мебарад)
- `tailwind.config.js` → кастомизация (рангҳо, сояҳо)

---

### Tailwind v4

```bash
cd tailwind-v4
npm install
npm run build       # як маротиба build кунед
npm run dev         # ё watch mode барои таҳия
```

Файлҳо:
- `src/input.css`  → манбаъ + `@theme {}` барои кастомизация
- `src/output.css` → автоматик месозад
- ❌ `tailwind.config.js` лозим нест — v4 тавассути CSS танзим мешавад

---

## ⚡ Фарқи v3 ва v4

| | v3 | v4 |
|---|---|---|
| Кастомизация | `tailwind.config.js` | `@theme {}` дар CSS |
| Import | `@tailwind base/components/utilities` | `@import "tailwindcss"` |
| CLI package | `tailwindcss` | `@tailwindcss/cli` |
| Суръат | Хуб | Хеле тез (Rust-based) |

---

## 📋 Талабот

- Node.js v18 ё баландтар
- npm v9+
