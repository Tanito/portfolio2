# Portfolio de Ulises D'Elia

Portfolio profesional de Ulises D'Elia, Full Stack Developer especializado en backend, arquitectura y desarrollo de productos web y mobile.

## Requisitos

- Node.js 22 o superior
- npm

Si utilizás `nvm`, activá la versión del proyecto:

```bash
nvm use
```

Si todavía no está instalada:

```bash
nvm install 22.22.3
nvm use 22.22.3
```

## Instalación

Desde la carpeta del proyecto:

```bash
nvm use
npm install
```

## Levantar en desarrollo

```bash
nvm use
npm run dev
```

Luego abrir la URL que muestra Vite, normalmente:

```text
http://localhost:5173
```

## Generar una versión de producción

```bash
npm run build
```

Los archivos optimizados se generan en la carpeta `dist/`.

Para previsualizar esa versión localmente:

```bash
npm run preview
```

## Despliegue en Vercel

1. Subir el proyecto a un repositorio de GitHub.
2. Entrar en [vercel.com](https://vercel.com) y seleccionar **Add New Project**.
3. Importar el repositorio.
4. Mantener la configuración detectada por Vercel:
   - Framework: `Vite`
   - Build command: `npm run build`
   - Output directory: `dist`
5. Hacer clic en **Deploy**.

No se necesitan variables de entorno para la versión actual.

## Estructura principal

```text
.
├── index.html          # Metadata y punto de entrada
├── src/
│   ├── main.js         # Contenido y estructura del portfolio
│   └── style.css       # Estilos, responsive y sistema visual
├── public/
│   ├── portrait.png    # Imagen de perfil
│   └── cv-ulises-delia.pdf
├── favicon.svg
├── vercel.json
└── package.json
```

## Actualizar contenido

Los datos principales —experiencia, tecnologías, proyectos y enlaces— están centralizados al inicio de `src/main.js`. Los estilos globales y responsive están en `src/style.css`.
