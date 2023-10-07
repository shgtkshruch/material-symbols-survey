# material-symbols-survey
## React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

## Links

- [Google Fonts API を使ってみる - Google for Developers](https://developers.google.com/fonts/docs/getting_started?hl=ja#Subsets)
- [CSS API の更新 - Google Fonts - Google for Developers](https://developers.google.com/fonts/docs/css2?hl=ja)
- [マテリアル シンボル ガイド - Google Fonts - Google for Developers](https://developers.google.com/fonts/docs/material_symbols?hl=ja)
- [Reduce web font size](https://web.dev/reduce-webfont-size/)
- [Introduction to variable fonts on the web](https://web.dev/variable-fonts/)
- [Speed Up Google Fonts – Harry Roberts – Web Performance Consultant](https://csswizardry.com/2020/05/the-fastest-google-fonts/)
