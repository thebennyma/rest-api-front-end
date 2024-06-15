# Front End API Rest

Este proyecto configura una aplicación mínima de React usando TypeScript y Vite. Se enfoca en implementar Hot Module Replacement (HMR) e incluye reglas de ESLint para mantener la calidad del código. El proyecto demuestra el uso de dos plugins oficiales de Vite para Fast Refresh: uno usando Babel y otro usando SWC. Además, proporciona guías para extender la configuración de ESLint para habilitar reglas de lint conscientes del tipo, adecuadas para aplicaciones de producción.

## Tecnologías Utilizadas
- **React**: Una biblioteca de JavaScript para construir interfaces de usuario.
- **TypeScript**: Un superconjunto tipado de JavaScript que se compila a JavaScript plano.
- **Vite**: Una herramienta de construcción que proporciona una experiencia de desarrollo más rápida y liviana para proyectos web modernos.
- **ESLint**: Una herramienta para identificar y reportar patrones encontrados en el código ECMAScript/JavaScript.
- **Babel**: Un compilador de JavaScript utilizado principalmente para convertir código ECMAScript 2015+ en una versión compatible hacia atrás de JavaScript.
- **SWC**: Un compilador superrápido de TypeScript / JavaScript escrito en Rust.

## Plugins de Vite para Fast Refresh

Este proyecto incluye configuraciones para dos plugins de Vite:
- `@vitejs/plugin-react`: Utiliza Babel para Fast Refresh.
- `@vitejs/plugin-react-swc`: Utiliza SWC para Fast Refresh.

Ambos plugins están configurados para demostrar diferentes enfoques de Fast Refresh en una aplicación React.

## Extender la Configuración de ESLint

El proyecto proporciona una configuración básica de ESLint. Para aplicaciones de producción, puedes extender la configuración de ESLint para habilitar reglas de lint conscientes del tipo. Esto implica integrar ESLint con TypeScript y configurar reglas adicionales para capturar posibles problemas relacionados con tipos en tu código.

## Dependencias

- `@vitejs/plugin-react`: Plugin para habilitar Fast Refresh usando Babel.
- `@vitejs/plugin-react-swc`: Plugin para habilitar Fast Refresh usando SWC.
- `eslint-plugin-react`: Plugin de ESLint con reglas para aplicaciones React.
