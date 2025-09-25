# 🧩 JS Advanced Playground

A collection of **interactive demos and mini apps** to practice advanced **modern JavaScript** concepts.  
This project is part of a personal roadmap to strengthen my frontend developer skills and build a solid GitHub portfolio.

## ✨ Features

- **Advanced JavaScript demos**
  - Closures
  - Event loop (micro/macro tasks)
  - Async/Await
  - Promises
  - Generators
  - Fetch API
- **Mini apps**
  - ToDo list (with `localStorage`)
  - Fake mini chat (async response simulation)
  - Canvas particles animation
- **Styling with [Tailwind CSS v4](https://tailwindcss.com/docs)** via [Vite](https://vite.dev/) plugin
- **Linting & formatting** with [ESLint](https://eslint.org/docs/latest/) + [Prettier](https://prettier.io/docs/en/)
- **Git hooks** powered by [Husky](https://typicode.github.io/husky/) and [lint-staged](https://github.com/okonet/lint-staged) to ensure code quality on every commit
- **Testing** with [Vitest](https://vitest.dev/guide/), [DOM Testing Library](https://testing-library.com/docs/dom-testing-library/intro/), and [JSDOM](https://github.com/jsdom/jsdom)
- **CI/CD** using [GitHub Actions](https://docs.github.com/en/actions)
- Deployed to [Vercel](https://vercel.com/) or [Netlify](https://docs.netlify.com/)

---

## 📦 Installation

Clone and install dependencies:

git clone https://github.com/AbrilDAngelo/js-advanced-playground.git
cd js-advanced-playground
npm install

## 🚀 Available Scripts
npm run dev       # Start local dev server (Vite)
npm run build     # Create production build
npm run preview   # Preview production build locally
npm run lint      # Run ESLint on src
npm run format    # Format code with Prettier
npm run typecheck # Run TypeScript type checks
npm test          # Run Vitest tests

## 🔧 Tech Stack
**Vite**
- fast modern build tool

**Tailwind CSS v4**
- utility-first CSS

**TypeScript**
- static typing

**ESLint**
- linting

**Prettier**
- consistent formatting

**Husky**
- Git hooks

**lint-staged**
- run linters on staged files

**Vitest**
- fast test runner

**DOM Testing Library**
- accessible UI testing

**JSDOM**
- DOM environment for tests


## 📊 Project Status

- Basic JS demos (Closures, Event Loop, Async/Await)
-  Promises / Generators / Fetch screens
-  Mini apps (ToDo, Chat, Canvas)
-  Unit tests + CI/CD
-  Public deployment (Vercel/Netlify)