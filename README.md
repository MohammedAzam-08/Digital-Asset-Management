# DAMS
Digital assets management system.

## Project Structure

```
Root/
│   package.json
│   README.md
│
├── CDAC_project/              # Main application
│   ├── package.json
│   ├── vite.config.ts
│   ├── tailwind.config.js
│   ├── tsconfig.json
│   ├── .env
│   ├── src/
│   │   ├── App.tsx
│   │   ├── main.tsx
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   └── ...
│   └── server/
│       ├── index.js
│       ├── config/
│       ├── controllers/
│       ├── middleware/
│       ├── models/
│       ├── routes/
│       └── uploads/
│
├── landing_page/              # Separate landing page app
│   ├── package.json
│   ├── vite.config.ts
│   ├── src/
│   │   ├── App.tsx
│   │   └── components/
│   └── ...
└── ...
```

## How to Run

1. Open a terminal in `CDAC_project/CDAC_project`.
2. Install dependencies:
   ```powershell
   npm install
   ```
3. Start both frontend and backend:
   ```powershell
   npm run dev:full
   ```
4. Frontend: http://localhost:5173/
   Backend: http://localhost:5000/
