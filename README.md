# EcoDecor - GreenIT Project

## Overview

EcoDecor is an eco-conscious website focused on promoting sustainable home furniture while implementing green web development practices. The project aims to:

- **Promote** eco-friendly furniture through an online catalog.
- **Reduce** the environmental impact of the website by optimizing performance and energy consumption.

## Key Features

### Viewer (Unregistered User)
- Browse the catalog.
- Registration/login required to add items to the cart.

### Logged-in User
- Add products to the cart.
- Browse personalized content.

### Admin
- Manage products: Add, edit, and delete furniture items.
- Manage users: Block or unblock users to maintain a safe community.

## Eco-Friendly Practices

- **Lazy Loading:** Images and Vue components are loaded only when needed.
- **Asset Compression:** Images compressed (e.g., WebP format); unused CSS/JS removed.
- **Optimized Hosting:** Deployed on **Vercel** (powered by renewable energy).
- **Code Optimization:** Clean, minimized code and efficient API calls.
- **Database Optimization:** Light, efficient queries to minimize server load.

## Technical Stack

- **Frontend:** Vue.js
  - Dynamic imports and lazy-loaded routes with Vue Router.
  - Local storage and props for state management.
  - Image lazy loading via `vue3-lazyload`.
- **Backend:** Node.js + Express.js
  - RESTful APIs with CRUD operations for users and products.
  - Authentication secured with **JWT (JSON Web Tokens)**.
  - Role-based access control (User/Admin).
- **Database:** MySQL (hosted via MySQL Workbench server).
- **Hosting:** Vercel (carbon-conscious hosting).

## Future Improvements

- Further reduce dependencies and server requests.
- Prioritize static content when possible.
- Choose even greener hosting options.
- Raise awareness among users about digital carbon footprint.

## License

This project is developed as part of an academic assignment on green web development principles.  
**All rights reserved to the EcoDecor project contributors.**
