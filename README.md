<<<<<<< HEAD
# BWU-Kart
BWU-Kart a web-based marketplace built for college and university students to buy and sell educational products within their campus community. It simplifies the exchange of used items like textbooks, lab equipment, calculators, and other study-related tools — making education more affordable and accessible for students.
Problem Statement - 
Students often struggle to find affordable study materials, tools, or gadgets, especially when they're only needed for a short time. Meanwhile, others have unused items they’d like to sell—but there’s no dedicated system in place for that.
Solution (How BWU-Kart helps) - 
Campus Kart solves this by creating a trusted, campus-specific marketplace where students can connect to buy and sell items like books, lab equipment, calculators, and more—safely and efficiently.
=======
<<<<<<< HEAD
# BWU-Kart
=======
Frontend - React.js , Typescript , CSS , HTML 
Serverless Backend - Firebase Authentication , Firebase Firestore
Deployment - Vercel
Other Tools - Git (Tracking code changes) , VS code (Code Editor)

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default tseslint.config({
  extends: [
    // Remove ...tseslint.configs.recommended and replace with this
    ...tseslint.configs.recommendedTypeChecked,
    // Alternatively, use this for stricter rules
    ...tseslint.configs.strictTypeChecked,
    // Optionally, add this for stylistic rules
    ...tseslint.configs.stylisticTypeChecked,
  ],
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config({
  plugins: {
    // Add the react-x and react-dom plugins
    'react-x': reactX,
    'react-dom': reactDom,
  },
  rules: {
    // other rules...
    // Enable its recommended typescript rules
    ...reactX.configs['recommended-typescript'].rules,
    ...reactDom.configs.recommended.rules,
  },
})
```
>>>>>>> 824eb02 (Initial commit)
>>>>>>> 2a32f0b (Initial commit)
