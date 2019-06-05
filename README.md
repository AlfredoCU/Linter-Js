# Linter-Js
Instalar un Linter para JS usando el estándar de AirBnb y configura tu editor para que evalué y te corrija al momento.

- Instalar dependencias.
```
npm install --save-dev eslint eslint-config-airbnb eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react
```
- En el editor instalar eslint.

- Crear un archivo .eslintrc y colocar nuestras reglas.
```
{
  "extends": "airbnb-base",
  "rules": {
    "indent": ["error", 2],
    "string": off,
    "no-alert": off,
    "no-console": off,
    "func-names": off,
    }
}
```
