# WebSite · Base Gatsby

Repositorio de **JLC-DevLab** basado en Gatsby Default Starter. Conserva una base de Gatsby 4 y React 17 con páginas y componentes de ejemplo.

**[Explorar el catálogo de proyectos públicos](docs/PROYECTOS.md)**

## Desarrollo

El repositorio incluye `package-lock.json`. Con Node.js y npm compatibles con las dependencias del proyecto:

```sh
npm ci
npm run develop
```

Servidor de desarrollo: `http://localhost:8000`.

## Comandos disponibles

| Comando | Función |
| --- | --- |
| `npm run develop` | Iniciar Gatsby en desarrollo. |
| `npm run build` | Generar el sitio. |
| `npm run serve` | Servir una compilación generada. |
| `npm run clean` | Limpiar la caché y la salida de Gatsby. |

`npm test` contiene el marcador de ejemplo del starter: no es una batería de pruebas implementada. También existe un `yarn.lock`; conviene elegir un único gestor antes de actualizar dependencias.

## Estructura

- `src/pages/`: páginas.
- `src/components/`: componentes y estilos.
- `gatsby-config.js`: configuración y metadatos del starter.
- [docs/PROYECTOS.md](docs/PROYECTOS.md): catálogo de repositorios públicos.
- [docs/README_STARTER.md](docs/README_STARTER.md): documentación original conservada.

## Procedencia y licencia

Basado en [Gatsby Default Starter](https://github.com/gatsbyjs/gatsby-starter-default). Se conserva [LICENSE](LICENSE), con licencia 0BSD, y la atribución original. Mantener este repositorio no implica autoría del starter.

La organización documental no actualiza dependencias ni acredita una compilación reciente. Los metadatos y recursos visuales de ejemplo siguen pendientes de personalización.
