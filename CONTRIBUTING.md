# 🤝 Guía de Contribución para el Equipo

¡Bienvenido al equipo de **GluV.IA**! Esta guía te ayudará a integrarte rápidamente y empezar a contribuir eficazmente.

---

## 🏁 Primeros Pasos

1. **Configuración de Cuenta e Identidad:**
   Asegúrate de que tu usuario de Git coincide con tu cuenta de GitHub:
   ```bash
   git config --global user.name "Tu Nombre"
   git config --global user.email "tu-correo@ejemplo.com"
   ```

2. **Acceso a los Repositorios:**
   Verifica que tienes acceso a la organización **DualCode-dev** y a todos los repositorios del proyecto.

3. **Revisión de Documentación Clave:**
   - Lee [`guidelines/git-workflow.md`](guidelines/git-workflow.md) antes de crear tu primera rama.
   - Consulta [`guidelines/tech-stack.md`](guidelines/tech-stack.md) para conocer las tecnologías acordadas.
   - Revisa [`api-contracts/openapi.yaml`](api-contracts/openapi.yaml) si estás trabajando en Backend o integrando endpoints en Front/Mobile.

---

## 📋 Asignación de Tareas
- Todas las tareas se gestionan en la pestaña **GitHub Projects / Issues** de la organización.
- Asigna la tarea a tu usuario y mueve la tarjeta a la columna **In Progress**.
- Crea la rama correspondiente siguiendo el estándar: `feature/nombre-tarea` o `fix/nombre-bug`.

---

## 🧪 Pruebas y Calidad
- Antes de abrir un Pull Request, ejecuta las pruebas locales y asegúrate de que no haya errores de compilación o linter.
- Mantén el código limpio, comentado donde sea necesario y modular.

---

## 💬 Comunicación y Ayuda
- Si tienes dudas sobre los contratos de API o modelos de datos, crea una incidencia (Issue) o consulta en los canales oficiales de comunicación del equipo.
