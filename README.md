# Explorer App 🌍 (Unidad 2 - Vanilla TypeScript)

Aplicación web modular para explorar y consultar información de países mediante la API de Rest Countries. Proyecto desarrollado para la Unidad 2 (Sesión 23).

## 🚀 Tecnologías
- **TypeScript** (sin uso de `any`)
- **Tailwind CSS v4** (`@tailwindcss/vite`)
- **Vite**
- **Git / GitHub** (Etiqueta `vanilla-u2`)

## 🛠️ Estructura Modular y Funcionalidades
- **`src/api/`**: Consumo de datos con `fetch`.
- **`src/types/`**: Contratos de datos e interfaces tipadas.
- **`src/utils/`**: Funciones puras, formateo de texto y control de *debounce* (300 ms).
- **`src/render/`**: Generación de la interfaz y estados visuales (carga, vacío y error).
- **Filtros Combinados:** Búsqueda por texto integrada con el selector por región.
- **Accesibilidad:** Navegación por teclado con estados `focus-visible`.