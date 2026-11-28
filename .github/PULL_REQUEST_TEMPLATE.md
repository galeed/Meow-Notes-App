<!--
  ¡Gracias por enviar un Pull Request a Meow Notes! 🐱
  Rellena esta plantilla con la mayor cantidad de información posible.
  El CI (validate.yml) tiene que estar en verde antes de mergear.
-->

## 📝 Descripción

<!--
  ¿Qué hace este PR? ¿Por qué es necesario?
  Si resuelve un issue, enlázalo: "Closes #12" o "Fixes #34".
-->

Closes #

## 🎯 Tipo de cambio

<!-- Marca lo que aplique -->

- [ ] 🐛 Bug fix (cambio que corrige un problema)
- [ ] ✨ Nueva feature (cambio que añade funcionalidad)
- [ ] 💥 Breaking change (cambio que rompe compatibilidad con versiones previas)
- [ ] 📚 Documentación (solo README, CHANGELOG, comentarios…)
- [ ] 🎨 Estilo (formato, espacios, puntos y comas — no cambia lógica)
- [ ] ♻️ Refactor (cambio de código que no corrige bug ni añade feature)
- [ ] ⚡ Rendimiento (mejora de velocidad o memoria)
- [ ] 🔧 Chore (CI, configs, tareas de mantenimiento)

## 🔍 ¿Qué se ha cambiado?

<!--
  Lista los cambios principales. Viñetas cortas y concretas.
-->

- 
- 
- 

## 📸 Capturas / vídeo

<!--
  Si el cambio es visual, incluye captura ANTES y DESPUÉS.
  Puedes pegar imágenes directamente en el editor de GitHub.
-->

| Antes | Después |
|---|---|
| _captura_ | _captura_ |

## 🧪 Cómo probar

<!--
  Pasos para que el reviewer pueda verificar el cambio.
  Ej: "1. Abrir la app, 2. Crear nota con tag, 3. Pulsar el tag…"
-->

1. 
2. 
3. 

## ✅ Checklist de calidad

- [ ] He leído el [CONTRIBUTING.md](../blob/main/CONTRIBUTING.md).
- [ ] He probado la app en **local** (`http://localhost:8000`).
- [ ] He probado en **modo claro y oscuro**, con al menos **2 acentos CRT**.
- [ ] He probado en **móvil** (o con DevTools responsive).
- [ ] He probado **online y offline** (DevTools → Application → Service Workers → Offline).
- [ ] He probado con **dos pestañas abiertas** (sincronización vía `BroadcastChannel`).
- [ ] El workflow **`validate.yml`** pasa en verde ✅.
- [ ] He **actualizado `CHANGELOG.md`** si es una feature o un fix visible.
- [ ] He **escapado** todo input de usuario con `escapeHtml()` antes de renderizar.
- [ ] No he añadido **dependencias innecesarias** (la app es vanilla a propósito).
- [ ] No he roto la **estética CRT/TUI** ni los 60 temas.

## 🌍 ¿A quién beneficia?

<!-- Marca lo que aplique -->

- [ ] Usuarios de escritorio
- [ ] Usuarios de móvil
- [ ] Usuarios con muchas notas
- [ ] Usuarios offline
- [ ] Usuarios con PWA instalada
- [ ] Contribuidores

## 🧩 Dependencias nuevas

<!--
  Si has añadido alguna librería externa, justifícala aquí (¿por qué es necesaria? ¿peso?).
  Si no has añadido, deja "Ninguna".
-->

Ninguna.

## ⚠️ Notas para el reviewer

<!--
  Cualquier cosa que quieras destacar: decisiones de diseño, partes delicadas,
  o zonas que merecen revisión extra.
-->

## 📝 Checklist de commits

- [ ] Mis commits siguen [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`…).
- [ ] El título del PR es descriptivo.
- [ ] He hecho **rebase** o **squash** para que el historial quede limpio (opcional).