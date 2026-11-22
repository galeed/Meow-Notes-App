<div align="center">


# 🐱 Meow Notes App

**Terminal de notas estilo CRT — guarda, etiqueta y encuentra.**

[![Licencia: MIT](https://img.shields.io/badge/Licencia-MIT-33ff33?style=flat-square)](./LICENSE)
[![PWA](https://img.shields.io/badge/PWA-instalable-00e5ff?style=flat-square)](https://web.dev/progressive-web-apps/)
[![Sin dependencias](https://img.shields.io/badge/deps-0-ffb000?style=flat-square)](#)
[![Demo](https://img.shields.io/badge/demo-live-c066ff?style=flat-square)](https://TU-USUARIO.github.io/TU-REPO/)

</div>

---

## ✨ Características

- 📝 **Notas completas** — título editable, descripción y tags ilimitados.
- 🕒 **Fechas automáticas** — guarda fecha/hora de creación y de última modificación.
- 🔍 **Búsqueda instantánea** — filtra por título o por tag mientras escribes.
- 🏷️ **Filtrado por tags** — un clic en cualquier tag muestra solo esas notas.
- 🎨 **60 combinaciones de tema** — 2 modos (claro/oscuro) × 5 fondos × 6 acentos CRT.
- 💾 **Persistencia local** — todo se guarda en `localStorage`, sin servidor ni cuenta.
- 📦 **Exportar / Importar JSON** — backup completo con opción de reemplazar o fusionar.
- 🔗 **Sincronización entre pestañas** — vía `BroadcastChannel`, sin recargar.
- 📴 **Funciona offline** — service worker con cache-first tras la primera visita.
- ⚡ **Instalable como PWA** — en desktop, Android e iOS (vía "Añadir a inicio").
- 🖥️ **Estética CRT/TUI** — tipografía monoespaciada, scanlines, glow fósforo y flicker sutil.

---

## 📸 Capturas

> _Reemplaza estas rutas por tus propias capturas (o elimina esta sección)._

| Modo oscuro (verde) | Modo claro (cian) |
|---|---|
| ![Oscuro](./screenshots/dark.png) | ![Claro](./screenshots/light.png) |

| Pestaña Personalizar |
|---|
| ![Personalizar](./screenshots/customize.png) |

---

## 🚀 Demo

👉 **[TU-USUARIO.github.io/TU-REPO](https://TU-USUARIO.github.io/TU-REPO/)**

---

## 🛠️ Tecnologías

- **HTML5 + CSS3 + JavaScript vanilla** — sin frameworks, sin build step, sin dependencias.
- **Custom Properties CSS** para el sistema de temas dinámico.
- **localStorage** para persistencia de notas y preferencias.
- **Service Worker** + **Web App Manifest** para PWA.
- **BroadcastChannel API** para sincronización entre pestañas.
- **IBM Plex Mono** (Google Fonts) como tipografía base.

---

## 📦 Instalación local

La PWA **no funciona abriendo `index.html` con doble clic** (`file://`). Necesita servirse por HTTP para que el service worker se registre.

### Opción A — Python (macOS/Linux)

```bash
git clone https://github.com/TU-USUARIO/TU-REPO.git
cd TU-REPO
python3 -m http.server 8000
