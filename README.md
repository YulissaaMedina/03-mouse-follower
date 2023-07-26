# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# ¿Qué hace el hook `useEffect`?

El hook useEffect se usa para ejecutar código cuando se renderiza el componente o cuando cambian las dependencias del efecto.

Recibe dos parámetros:

La función que se ejecutará al cambiar las dependencias o al renderizar el componente.

Un array de dependencias. Si cambia el valor de alguna dependencia, ejecutará la función.

¿Cuándo se usa useEffect?

useEffect se ejecuta después de que el componente se ha renderizado por primera vez y luego se vuelve a ejecutar cada vez que cambia alguna de las dependencias.
