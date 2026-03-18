# Beautysalon — Tailwind CSS (Node.js)

Ин проект дар ду версияи Tailwind CSS омода шудааст.

---

## 📁 Сохтор

```
tailwind-v3/         ← Tailwind CSS v3
tailwind-v4/         ← Tailwind CSS v4
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
# tailwindcss
