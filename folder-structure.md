Study Planner/
│
├── node_modules/
│
├── public/
│   ├── favicon.svg
│   └── icons.svg
│
├── src/
│   │
│   ├── assets/                # Images, icons, static files
│   │
│   ├── components/            # Reusable UI components
│   │   ├── LoadingSpinner.tsx
│   │   ├── Navbar.tsx
│   │   ├── ProtectedRoute.tsx
│   │   └── ScrollToTop.tsx
│   │
│   ├── lib/                   # Utility functions / helpers
│   │
│   ├── pages/                 # Application pages (routes)
│   │   ├── Dashboard.tsx
│   │   ├── Home.tsx
│   │   ├── Login.tsx
│   │   ├── NotFound.tsx
│   │   ├── Profile.tsx
│   │   └── Signup.tsx
│   │
│   ├── App.css
│   ├── App.tsx                # Main app with routing
│   ├── index.css             # Global styles (Tailwind)
│   └── main.tsx              # Entry point
│
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── README.md
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
