# FrameLens 🎬🔍

Reproductor de video **frame a frame** con búsqueda directa por **Google Lens** vía long press.

## Funciones

- 📹 Sube cualquier video (MP4, WebM, MOV, AVI, MKV)
- ⏯ Barra de reproducción con precisión de milisegundos
- ◀▶ Navegación frame a frame (±1f, ±10f)
- 🐢 Control de velocidad (0.1x, 0.25x, 0.5x, 1x, 1.5x, 2x)
- 📷 Captura de frame a imagen real
- 🔍 **Long press** sobre el frame → menú nativo de Google Lens
- 🗂 Historial de frames capturados en la sesión
- ⌨️ Atajos de teclado (← → Space C L)
- 📱 **Instalable como PWA** (sin Play Store)

## Instalar como app en Android

1. Abre **[tu-usuario].github.io/framelens** en Chrome o Brave
2. Menú ⋮ → **"Instalar app"** o **"Agregar a pantalla de inicio"**
3. Listo — funciona offline después de la primera carga

## Subir a GitHub Pages

```bash
# 1. Crea un repo en GitHub llamado "framelens"
# 2. Sube estos archivos:
#    - index.html   (renombrar video-lens.html → index.html)
#    - manifest.json
#    - sw.js
#    - icon-192.png
#    - icon-512.png

git init
git add .
git commit -m "FrameLens v1.0"
git remote add origin https://github.com/TU_USUARIO/framelens.git
git push -u origin main

# 3. En GitHub → Settings → Pages → Branch: main → Save
# 4. Tu app queda en: https://TU_USUARIO.github.io/framelens
```

## Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | App principal (renombrar video-lens.html) |
| `manifest.json` | Configuración PWA |
| `sw.js` | Service Worker (caché offline) |
| `icon-192.png` | Ícono app 192×192 |
| `icon-512.png` | Ícono app 512×512 |
