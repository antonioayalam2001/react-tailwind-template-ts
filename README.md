# React + TypeScript + Vite + TailwindCSS + ESLint 

This is a template for React + TypeScript + Vite + TailwindCSS + ESLint.

Las importaciones de  Tailwind se encuentran en index.css (En caso de querer eliminar este archivo, debemos realizar la importación de estas directivas en el nuevo archivo que creemos). La hoja debe estar anclada a la página en el archivo index.html o en el archivo App.tsx.

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Podemos desactivar el aviso de VSCode de que no encuentra los tipos de TailwindCSS modificando la configuración que se encuentra en 
 ```
  unknown at rules: ignore 
 ```
**Ejecución**
```bash
  yarn install
  yarn dev
```
`