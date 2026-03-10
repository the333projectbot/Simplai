# SimplAI — Módulo 0

Landing page + PDF descargable gratuito de SimplAI.

## Estructura

```
simplai-repo/
├── index.html                  # Landing page
├── SimplAI-Introduccion-IA.pdf # PDF Módulo 0
├── .nojekyll                   # Necesario para GitHub Pages
└── README.md
```

## Deploy en GitHub Pages — 5 pasos

### 1. Crear el repositorio

1. Ir a [github.com/new](https://github.com/new)
2. Nombre: `simplai` (o `simplai-web`)
3. Visibilidad: **Public** ← obligatorio para GitHub Pages gratis
4. NO marcar "Add README" (ya tiene uno)
5. Clic en **Create repository**

### 2. Subir los archivos

En la página del repo recién creado, clic en **"uploading an existing file"**:

- Arrastrá los 4 archivos: `index.html`, `SimplAI-Introduccion-IA.pdf`, `.nojekyll`, `README.md`
- Commit message: `primer deploy`
- Clic **Commit changes**

### 3. Activar GitHub Pages

1. Ir a **Settings** → **Pages** (menú izquierdo)
2. Source: **Deploy from a branch**
3. Branch: `main` / `root`
4. Clic **Save**

### 4. URL lista en ~2 minutos

```
https://TU-USUARIO.github.io/simplai/
```

### 5. Cuando tengas el dominio simplai.com

En Settings → Pages → Custom domain: escribir `simplai.com`  
Después agregar en tu DNS (donde compraste el dominio):
```
Tipo A     @    185.199.108.153
Tipo A     @    185.199.109.153
Tipo A     @    185.199.110.153
Tipo A     @    185.199.111.153
CNAME     www   TU-USUARIO.github.io
```

---
Hecho con ♥ en Argentina.
