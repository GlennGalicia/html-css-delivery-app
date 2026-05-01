# 🛵 Delivery App

A responsive food delivery landing page built as a front-end learning project, using a modern workflow with Sass and Gulp for asset automation.

🔗 **Live site:** [delivery-app-miller.netlify.app](https://delivery-app-miller.netlify.app)

---

## 🔗 🛠️ Built With

| Technology         | Purpose                                      |
| ------------------ | -------------------------------------------- |
| HTML5              | Page structure                               |
| CSS3 / Sass        | Styling, variables & mixins                  |
| BEM Methodology    | CSS class naming convention                  |
| CSS Grid & Flexbox | Responsive layouts                           |
| Media Queries      | Mobile-first design                          |
| Gulp               | Task automation (compile Sass, minify, etc.) |
| Node.js / npm      | Dev environment & package management         |

---

## 📚 What I Practiced

- Building responsive layouts with **CSS Grid** and **Flexbox**
- Writing modular styles with **Sass** (variables, partials, nesting, `@use`, `@forward`)
- Using **BEM methodology** for scalable and maintainable CSS class naming
- Creating reusable **Sass mixins** for grid, breakpoints and button styles
- Applying **pseudo-elements** (`::before`) for decorative content like quote marks
- Applying **pseudo-classes** (`:hover`, `:last-of-type`, `:nth-child`) for interactive and structural styling
- Using **CSS custom properties** via Sass variables for colors, spacing and typography
- Implementing **hover animations** with `transform: rotate()` and `scale()`
- Building **asymmetric grid layouts** with `grid-column` and `grid-row`
- Setting up a dev workflow with **Gulp** and **Node.js**
- Managing dependencies with **npm** and `package.json`
- Deploying a static site to **Netlify**

---

## 🗂️ Project Structure

```
delivery-app/
├── src/
│   ├── scss/
│   │   ├── base/          # Variables, mixins, normalize, utilities
│   │   └── layout/        # Section-specific styles (header, footer, etc.)
│   └── img/               # Original images
├── build/
│   ├── css/               # Compiled & minified CSS
│   └── img/               # Optimized images
├── index.html
├── gulpfile.js
└── package.json
```

---

## 📐 Sections

| Section       | Description                                             |
| ------------- | ------------------------------------------------------- |
| Header        | Hero with search form, responsive navigation            |
| Pasos         | How it works — 3-step grid with hover animations        |
| Testimoniales | Asymmetric 5-column grid with quote pseudo-element      |
| Favoritos     | Restaurant cards with internal 2-column grid            |
| Repartidores  | Delivery driver CTA with 2-column layout                |
| Descargar     | App download section with App Store & Google Play links |
| Footer        | 3-column grid with navigation links and copyright bar   |
