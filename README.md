# CSS Playground (Vue 3 + Vite)

A lightweight **CSS sandbox** powered by **Vue 3** and **Vite**. Use it to prototype layouts (Grid/Flexbox), transitions/animations, and responsive patterns inside Vue single-file components.

> Based on the Vue 3 + Vite template using `<script setup>` SFCs. :contentReference[oaicite:1]{index=1}

---

## ✨ What’s inside
- **Vue 3 + Vite** starter for instant HMR and fast builds. :contentReference[oaicite:2]{index=2}
- Conventional project layout: `src/`, `public/`, `index.html`, `vite.config.js`. :contentReference[oaicite:3]{index=3}
- Ready to add demo components for Grid, Flexbox, variables, and keyframe animations.

---

## 🚀 Getting Started

### 1) Install
```bash
npm install
```


### 2) Run dev server
```
npm run dev
```


### 3) Build & preview
```
npm run build
npm run preview
```

---

## 🗂️ Project structure (high-level)
```
.
├─ public/
├─ src/
├─ index.html
├─ package.json
└─ vite.config.js
```

--

## 🧪 How to add a new CSS demo
1. Create a component in src/ (e.g., src/demos/GridGallery.vue).
2. Add your markup + styles (scoped or global).
3. Register it in your root view/router and link it from a simple index page.

--

## 🛣️ Ideas / Roadmap
- Flexbox & Grid galleries (gap, minmax, auto-fit/auto-fill)
- Transitions & keyframes (hover states, reveal effects)
- CSS variables & themes (dark/light)
- Responsive utilities & container queries

--

## 📄 License
MIT

--

## 🗣️ Author
Hakim Murphy
