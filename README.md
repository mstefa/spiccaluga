# Piccaluga Arquitectura - Sitio Web

Este es el sitio web oficial de Piccaluga Arquitectura, un estudio de arquitectura contemporánea.

## Tecnologías Utilizadas

- [Astro](https://astro.build)
- [TypeScript](https://www.typescriptlang.org)
- [Tailwind CSS](https://tailwindcss.com)

## Requisitos Previos

- Node.js (versión 16 o superior)
- npm (incluido con Node.js)

## Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/piccaluga-arquitectura.git
cd piccaluga-arquitectura
```

2. Instala las dependencias:
```bash
npm install
```

## Desarrollo

Para iniciar el servidor de desarrollo:

```bash
npm run dev
```

El sitio estará disponible en `http://localhost:4321`

## Construcción

Para construir el sitio para producción:

```bash
npm run build
```

## Estructura del Proyecto

```
src/
├── components/     # Componentes reutilizables
├── layouts/       # Layouts de página
├── pages/         # Páginas del sitio
└── styles/        # Estilos globales
public/
└── images/        # Imágenes estáticas
```

## Personalización

### Imágenes
Coloca las imágenes del proyecto en el directorio `public/images/`. Las imágenes necesarias son:
- hero.jpg
- about-hero.jpg
- history.jpg
- project1.jpg a project6.jpg
- team1.jpg a team3.jpg

### Contenido
Puedes personalizar el contenido modificando los archivos en `src/pages/` y `src/components/`.

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles. 
