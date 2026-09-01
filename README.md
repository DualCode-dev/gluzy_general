# 🩸 Gluzy - Documentación Central

Bienvenidos al repositorio principal de **Gluzy**, el ecosistema de software multiplataforma para la gestión de la diabetes y la recaudación de donaciones.

Este repositorio es la **fuente de la verdad** para los 30 miembros del equipo. Aquí no hay código ejecutable, sino los cimientos de nuestra arquitectura.

## 🚀 Ecosistema de Repositorios
Nuestro código está dividido en:
1. **[gluzy-android](https://github.com/DualCode-dev):** App móvil nativa/multiplataforma.
2. **[gluzy-backend](https://github.com/DualCode-dev):** API central y base de datos PostgreSQL.
3. **[gluzy-web-publica](https://github.com/DualCode-dev):** Landing page y portal de donaciones.
4. **[gluzy-web-admin](https://github.com/DualCode-dev):** Dashboard de administración interno.

## 📚 Por dónde empezar
Si acabas de unirte al proyecto:
1. Lee las normas de trabajo en [`guidelines/git-workflow.md`](guidelines/git-workflow.md).
2. Revisa la arquitectura y tecnologías en [`guidelines/tech-stack.md`](guidelines/tech-stack.md).
3. Consulta las pantallas y diseño en [`design/ui-ux.md`](design/ui-ux.md).
4. Revisa la guía de incorporación en [`CONTRIBUTING.md`](CONTRIBUTING.md).
5. Ve a la pestaña de **Projects** de nuestra organización en GitHub para asignarte tu primera tarea.

---

## 📁 Estructura del Repositorio
```plaintext
Gluzy_General/
├── 📂 api-contracts/     # Contratos de API (OpenAPI / Swagger)
│   └── openapi.yaml
├── 📂 database/          # Esquema de base de datos PostgreSQL y diagramas
│   ├── esquema.md
│   └── diagrama-er.png
├── 📂 design/            # Recursos de diseño UX/UI, tokens y logos
│   ├── ui-ux.md
│   └── logo/
├── 📂 guidelines/        # Normas de Git, flujos de trabajo y stack tecnológico
│   ├── git-workflow.md
│   └── tech-stack.md
├── CONTRIBUTING.md       # Guía rápida para empezar a trabajar
└── README.md             # Portada principal del proyecto
```


Esta línea se agrega desde la rama 16