# Guía de Contribución 🚀

¡Gracias por querer formar parte de este proyecto! Para mantener el código limpio y organizado, seguimos estas reglas de nomenclatura y flujo de trabajo.

---

## 1. Nomenclatura de Issues 📋
Antes de crear una, verifica que no exista una similar. El título debe ser descriptivo y seguir este formato:

**Formato:** `[TIPO]: Descripción breve y clara`

* `[BUG]`: Errores o fallos técnicos.
* `[FEATURE]`: Nuevas funcionalidades.
* `[REFACTOR]`: Mejoras en el código sin cambiar funcionalidad.
* `[DOCS]`: Cambios en la documentación.
* `[CHORE]`: Tareas de mantenimiento, configuración de herramientas o actualización de dependencias.
---

## 2. Nomenclatura de Ramas (Branches) 🌿
Trabajamos con una estructura basada en el propósito del cambio. Usa siempre minúsculas y separa las palabras con guiones.

**Formato:** `tipo/nro-issue-descripcion-breve`

| Tipo | Propósito | Ejemplo |
| :--- | :--- | :--- |
| `feat/` | Nueva funcionalidad | `feat/12-sistema-reservas` |
| `fix/` | Corrección de errores | `fix/45-error-login-ios` |
| `docs/` | Documentación | `docs/actualizar-instalacion` |
| `refactor/` | Optimización de código | `refactor/limpieza-api` |
| `hotfix/` | Parche crítico en producción | `hotfix/error-pagos` |
`chore/` |	Tareas de mantenimiento	| `chore/3-configurar-gitignore`
`hotfix/` |	Parche crítico en producción |	`hotfix/error-pagos`
---

## 3. Estándar de Commits 📝
Usamos el estándar de **Conventional Commits**. Esto facilita la lectura del historial y la generación de changelogs automáticos.

**Formato:** `tipo(alcance): mensaje en minúsculas`

* **Tipos comunes:** `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.
* **Alcance (Opcional):** El módulo afectado (ej. `api`, `ui`, `auth`).

**Ejemplos:**
- `feat(ui): añadir selector de fechas al calendario`
- `fix(auth): corregir expiración de token de sesión`
- `docs: actualizar guía de configuración de base de datos`
- `chore(repo): configurar reglas del archivo .gitignore`
---

## 4. Proceso de Pull Request (PR) 🔄
1.  **Sincroniza:** Asegúrate de que tu rama esté actualizada con `main`.
2.  **Describe:** En el PR, explica *qué* hiciste y *por qué*.
3.  **Referencia:** Incluye "Closed #[número de issue]" para que se vincule automáticamente.
4.  **Revisión:** Al menos un administrador debe aprobar los cambios antes del merge.

---

## 5. Estilo de Código (Linting) 🎨
* Usa el linter configurado en el proyecto.
* No subas código con console.logs o comentarios innecesarios.