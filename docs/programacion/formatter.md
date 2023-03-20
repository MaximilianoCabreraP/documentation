# Instalación Eslint, Prettier y Tailwind

[Volver](/index)

## Eslint y Prettier

1. Instalación Eslint y Prettier

```bash
npm install -D standard prettier
```

2. Modificar o crear el archivo `.eslintrc.json`

```
{
  "extends": [
    "./node_modules/standard/eslintrc.json"
  ]
}
```

3. Crear archivo `.prettierrc.json` para declarar las reglas de prettier

```json
{
  "semi": false,
  "singleQuote": true,
  "jsxSingleQuote": true
}
```

## Tailwind y PostCSS

1. Instalar tailwind y postcss

```bash
npm install -D tailwindcss postcss autoprefixer
```

2. Crear archivos de configuración de Tailwind y Postcss

```bash
npx tailwind init -p
```

3. Modificar el archivo `tailwind.config.cjs`

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

4. Agregar en el archivo principal de `.css` (`index.css` | `globals.css`)

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Bonus

1. Agregar rules al archivo `.eslintrc.json`

```json
{
  "extends": [
    ...
  ],
  "rules": {
    "space-before-function-paren": "off" -> Espacios post nombre de función
  }
}
```

[Volver](/index)
