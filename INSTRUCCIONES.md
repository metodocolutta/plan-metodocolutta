# Método Colutta — Constructor de Planes
## Instrucciones para publicar en Netlify

---

### Lo que incluye este paquete

```
colutta-app/
├── index.html        ← La app completa
├── manifest.json     ← Configuración PWA (ícono, nombre, colores)
├── sw.js             ← Service worker (funciona offline)
├── icons/
│   ├── icon-192.png  ← Ícono app (pantalla inicio)
│   └── icon-512.png  ← Ícono app (alta resolución)
└── INSTRUCCIONES.md  ← Este archivo
```

---

### Cómo publicar en Netlify (gratis, 5 minutos)

**Paso 1 — Crear cuenta**
Entrá a https://netlify.com y creá una cuenta gratuita (podés usar Google o GitHub).

**Paso 2 — Subir la carpeta**
1. En el dashboard de Netlify, buscá el recuadro que dice **"Deploy manually"**
2. Arrastrá y soltá la carpeta `colutta-app` completa ahí
3. Netlify la despliega en segundos

**Paso 3 — Obtener tu URL**
Netlify te asigna una URL automática tipo `https://nombre-aleatorio.netlify.app`
Podés cambiarla a algo como `https://metodocolutta.netlify.app` desde Site Settings → Change site name.

**Paso 4 — Dominio propio (opcional)**
Si querés `app.metodocolutta.com`, desde Site Settings → Domain Management podés agregar tu dominio.

---

### Cómo instalar la app en el celular

**En iPhone (Safari):**
1. Abrí la URL en Safari
2. Tocá el botón compartir (cuadrado con flecha)
3. Elegí "Agregar a pantalla de inicio"
4. La app aparece como ícono nativo

**En Android (Chrome):**
1. Abrí la URL en Chrome
2. Aparece un banner "Instalar app" automáticamente, o
3. Tocá los tres puntos → "Agregar a pantalla de inicio"

**En desktop (Chrome / Edge):**
1. Abrí la URL
2. En la barra de direcciones aparece un ícono de instalación (⊕)
3. Hacé click → "Instalar"
4. Se abre como ventana independiente sin barra del navegador

---

### Funciona offline
Una vez instalada, la app funciona sin conexión a internet.
Los planes se crean y exportan localmente — no hay servidor, no hay base de datos.

---

### Para actualizar la app
Cuando hagas cambios al `index.html`, volvé a arrastrar la carpeta a Netlify.
Netlify reemplaza la versión anterior automáticamente.

---

### Soporte
Si algo no funciona, revisá que la carpeta subida tenga exactamente esta estructura:
- `index.html` en la raíz (no dentro de otra carpeta)
- `manifest.json` en la raíz
- `sw.js` en la raíz
- `icons/` como subcarpeta
