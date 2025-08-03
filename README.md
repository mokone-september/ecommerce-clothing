# Ecommerce Clothing Store

A modern e-commerce clothing store built with React, Vite, and Tailwind CSS.

## Features

- Product listing and details pages
- Shopping cart with add, remove, and quantity adjustment
- Responsive design with Tailwind CSS
- Context API for state management (products, cart, sidebar)
- Fake Store API integration for product data

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router](https://reactrouter.com/)
- [Fake Store API](https://fakestoreapi.com/)

## Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```

2. **Run the development server:**
   ```sh
   npm run dev
   ```

3. **Build for production:**
   ```sh
   npm run build
   ```

4. **Preview the production build:**
   ```sh
   npm run preview
   ```

## Project Structure

```
src/
  components/      # Reusable UI components
  contexts/        # React Context providers for state management
  img/             # Static images
  pages/           # Page components (Home, ProductDetails)
  App.jsx          # Main app component with routing
  main.jsx         # Entry point
  index.css        # Tailwind CSS imports
```

## Customization

- Update Tailwind config in [`tailwind.config.js`](tailwind.config.js)
- Change API endpoint in [`ProductContext.jsx`](src/contexts/ProductContext.jsx) if needed

## License

This project is for educational/demo purposes.
```
