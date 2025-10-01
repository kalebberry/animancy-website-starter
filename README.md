# Studio Eien — A Web Design System ✒️

A showcase for **The Eien Framework**, a web design system built around a calm, monochrome aesthetic that lets the work speak for itself. Inspired by the clarity of manga and inkwork, this system provides a foundation for creating clean, content-focused web experiences.

---

## 🎯 Vision

This design system provides:

- A set of reusable, themeable layout primitives (`cluster`, `sidebar`, `switcher`, etc.).
- A core component library (`card`, `btn`, `tag`) with a distinct monochrome style.
- A design token-based architecture for colors, spacing, and typography.
- A focus on minimalism, accessibility, and modern CSS

---

## 🚧 Roadmap

### ✅ Phase 1: Foundation & Showcase

- [x] Define core design tokens (colors, typography, spacing).
- [x] Build foundational layout components.
- [x] Create core UI components (`card`, `btn`, `input`).
- [x] Develop a static showcase landing page with Astro.

### ✅ Phase 2: Light Automation & Smarter UX

- [ ] Add interactive examples using Vue components.
- [ ] Create dedicated documentation pages for each component.
- [ ] Implement a live theme switcher (e.g., dark/light mode toggle).
- [ ] Publish the system as an NPM package.

### 💡 Phase 3: Expansion

- [ ] Add more complex components (e.g., modals, dropdowns).
- [ ] Develop data visualization components.
- [ ] Explore additional themes beyond monochrome.

---

## 🛠️ Tech Stack

- [Astro](https://astro.build) (Static-first UI framework)
- [Vue 3](https://vuejs.org) (UI reactivity and interactivity)
- [Pinia](https://pinia.vuejs.org) (Vue state management)
- [TypeScript](https://www.typescriptlang.org)
- [SCSS](https://sass-lang.com) (7-1 architecture)
- [GSAP](https://greensock.com/gsap/) + [PixiJS](https://pixijs.com) (Animations for gamification)

---

## ⚙️ Getting Started

### Install dependencies:

```bash
npm install
```

### Run the development server:

```
npm run dev
```

Open your browser to http://localhost:4321.

## 📁 Project Structure

```
src/
├── components/
│ ├── vue/ # Vue interactive components
│ ├── astro/ # Static Astro layout parts
├── pages/ # Astro routes (Dashboard, Goals, etc.)
├── stores/ # Pinia state management
├── styles/ # SCSS styles (7-1 pattern)
├── hydrate/ # Manual Vue + Pinia mount scripts
├── utils/ # Helper functions (budget, currency, etc.)
├── data/ # Static/mock data
├── composables/ # Reusable logic (Vue Composition API)
├── types/ # TypeScript interfaces
```

Built with 💙 for neurodivergent creators.
