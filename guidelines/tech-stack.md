# 🛠️ Stack Tecnológico Oficial de GluV.IA

Este documento define las tecnologías, herramientas y versiones acordadas para cada componente del ecosistema **GluV.IA**.

---

## 📱 1. Mobile (gluvia-android)
- **Lenguaje:** Kotlin
- **Arquitectura:** MVVM / Clean Architecture
- **UI:** Jetpack Compose
- **Networking:** Retrofit + Kotlinx Serialization / Gson
- **Almacenamiento Local / Caché:** Room Database
- **Inyección de Dependencias:** Hilt / Koin

---

## ⚙️ 2. Backend & API (gluvia-backend)
- **Lenguaje:** Java / Kotlin (Spring Boot) o Node.js / TypeScript
- **Base de Datos:** PostgreSQL
- **ORM / Acceso a Datos:** Spring Data JPA / Prisma / Hibernate
- **Seguridad:** JWT (JSON Web Tokens) & Spring Security
- **Documentación de API:** OpenAPI 3.0 / Swagger UI

---

## 🌐 3. Frontend Web (gluvia-web-publica & gluvia-web-admin)
- **Framework:** Angular / React + Vite
- **Estilos:** CSS Modules / SCSS / Tailwind CSS
- **Gestión de Estado:** NgRx / Redux Toolkit / Zustand
- **Visualización de Datos / Gráficos:** Chart.js / Recharts

---

## 🗄️ 4. Infraestructura & DevOps
- **Control de Versiones:** Git + GitHub
- **Integración Continua (CI/CD):** GitHub Actions
- **Contenedores:** Docker & Docker Compose
- **Entorno de Despliegue:** AWS / Render / Railway
