# Paradise Nursery 🌿

A React + Redux plant shopping cart app. Browse plants by category, add them to your cart, and manage quantities — built with Vite for fast dev/build.

## Features

- Landing page with an "About Us" section and a call-to-action into the store
- Product listing grouped by plant category
- Cart management (add, increase/decrease quantity, remove) powered by Redux Toolkit
- Client-side state via `react-redux`

## Tech Stack

- [React 18](https://react.dev/)
- [Redux Toolkit](https://redux-toolkit.js.org/) + [React Redux](https://react-redux.js.org/)
- [Vite](https://vitejs.dev/) for dev server and bundling
- ESLint for linting

## Getting Started

### Prerequisites

- Node.js and npm installed

### Installation

```bash
npm install
```

### Development

Start the local dev server:

```bash
npm run dev
```

### Build

Create a production build:

```bash
npm run build
```

### Preview

Build and preview the production output locally:

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

## Project Structure

```
src/
├── App.jsx           # Landing page + routing between home and product list
├── AboutUs.jsx        # About Us section on the landing page
├── ProductList.jsx     # Plant catalog grouped by category
├── CartItem.jsx        # Individual cart line item UI
├── CartSlice.jsx        # Redux slice for cart state
├── store.js            # Redux store configuration
└── main.jsx             # App entry point
```

## License

See [LICENSE](LICENSE).
