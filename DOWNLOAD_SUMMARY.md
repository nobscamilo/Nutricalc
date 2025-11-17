# 📦 Calculadora Glucémica PWA - Resumen de Descarga

## ✅ Aplicación Lista para Descargar

Tu **Calculadora Glucémica PWA** está completamente empaquetada y lista para usar.

---

## 📥 Archivos Disponibles

| Archivo | Tamaño | Descripción |
|---------|--------|-------------|
| **calculadora-glucemica-pwa.zip** | 49 KB | Formato ZIP (Windows/Mac/Linux) |
| **calculadora-glucemica-pwa.tar.gz** | 46 KB | Formato TAR.GZ (Unix/Linux) |
| **calculadora-glucemica-pwa-complete.tar.gz** | 36 KB | Versión compacta con documentación |

---

## 📂 Contenido del Paquete

### Archivos Principales
- ✅ `index.html` - Página de inicio con enlace a la app
- ✅ `app.html` - Aplicación principal (standalone)
- ✅ `manifest.json` - Configuración PWA
- ✅ `sw.js` - Service Worker para funcionalidad offline
- ✅ `package.json` - Configuración del proyecto

### Documentación
- 📖 `README.md` - Documentación completa del proyecto
- 📖 `INSTALL.md` - Guía de instalación paso a paso
- 📖 `DOWNLOAD_INFO.txt` - Información detallada de descarga
- 📖 `LICENSE` - Licencia MIT

### Archivos Adicionales
- 🔧 `.gitignore` - Configuración Git
- 📄 Versiones HTML alternativas (2 archivos)

---

## 🚀 Inicio Rápido (3 pasos)

### 1️⃣ Descargar y Descomprimir

```bash
# Opción A: ZIP
unzip calculadora-glucemica-pwa.zip

# Opción B: TAR.GZ
tar -xzf calculadora-glucemica-pwa.tar.gz
```

### 2️⃣ Iniciar Servidor Local

```bash
cd calculadora-glucemica-pwa
python3 -m http.server 8000
```

### 3️⃣ Abrir en Navegador

Visita: **http://localhost:8000**

---

## ✨ Características de la Aplicación

### 🎯 Funcionalidades Core
- ✅ **Cálculo de IG y CG** - Índice y Carga Glucémica
- ✅ **Base de datos** - 320+ alimentos precargados
- ✅ **Búsqueda rápida** - Algoritmo Trie optimizado
- ✅ **Modo offline** - Funciona sin internet (PWA)

### 📱 Características Avanzadas
- ✅ **Scanner de códigos** - Escanea códigos de barras
- ✅ **Exportación** - CSV y PDF
- ✅ **Perfiles de usuario** - Cálculos personalizados
- ✅ **Plantillas/Recetas** - Guarda comidas favoritas
- ✅ **Responsive** - Móvil, tablet y desktop

### 📊 Métricas Calculadas
- **CG Total** - Carga Glucémica total
- **IG Ponderado** - Promedio ponderado por carbohidratos
- **IRE** - Índice de Respuesta Estimada (CG/kg)
- **VG** - Valor Glucémico por 100 kcal

---

## 📱 Instalar como Aplicación Nativa

### Desktop (Chrome/Edge)
1. Abre la app en el navegador
2. Busca el ícono ➕ en la barra de direcciones
3. Haz clic en "📲 Instalar"

### iOS (Safari)
1. Abre la app
2. Toca **Compartir** (icono cuadrado con flecha)
3. Selecciona **"Añadir a pantalla de inicio"**

### Android (Chrome)
1. Abre la app
2. Toca el menú **⋮** (tres puntos)
3. Selecciona **"Añadir a pantalla de inicio"**

---

## 🌐 Desplegar en Internet

### GitHub Pages (Gratis)

```bash
# 1. Crear repositorio en GitHub
# 2. Subir archivos
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main

# 3. Activar GitHub Pages
# Settings → Pages → Source: main branch
```

Tu app estará en: `https://TU_USUARIO.github.io/TU_REPO/`

### Vercel (Gratis)

```bash
npm install -g vercel
vercel
```

### Netlify (Gratis)

```bash
npm install -g netlify-cli
netlify deploy
```

---

## 🔧 Requisitos del Sistema

### Navegadores Soportados
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### Para Servidor Local
- Python 3.x (recomendado)
- O Node.js 14+

### Conexión a Internet
- Solo necesaria la primera vez
- Después funciona 100% offline

---

## 📖 Documentación Adicional

| Archivo | Descripción |
|---------|-------------|
| `README.md` | Documentación completa con todas las características |
| `INSTALL.md` | Guía detallada de instalación y configuración |
| `DOWNLOAD_INFO.txt` | Información visual de descarga |
| `LICENSE` | Licencia MIT del proyecto |

---

## 🐛 Solución de Problemas

### La app no se instala como PWA
- ✅ Verifica que uses HTTPS (o localhost)
- ✅ Asegúrate de que el Service Worker esté registrado
- ✅ Revisa la consola del navegador (F12)

### No funciona offline
- ✅ Abre la app al menos una vez con internet
- ✅ Verifica que el Service Worker esté activo en DevTools

### El scanner no funciona
- ✅ Permite el acceso a la cámara cuando se solicite
- ✅ Usa HTTPS (requerido para acceso a cámara)
- ✅ Verifica que tu dispositivo tenga cámara

---

## 🧪 Probar la Aplicación

La app incluye un botón de **🧪 Tests** que verifica:

1. ✅ Búsqueda Trie
2. ✅ Agregar alimentos
3. ✅ Cálculos de CG
4. ✅ Perfil de usuario
5. ✅ IndexedDB

---

## 📊 Estructura de Archivos

```
calculadora-glucemica-pwa/
│
├── 📄 index.html              # Página de inicio
├── 📄 app.html                # Aplicación principal
├── ⚙️ manifest.json           # Configuración PWA
├── 🔧 sw.js                   # Service Worker
├── 📦 package.json            # Config npm
│
├── 📖 README.md               # Documentación
├── 📖 INSTALL.md              # Guía instalación
├── 📖 DOWNLOAD_INFO.txt       # Info descarga
├── 📖 DOWNLOAD_SUMMARY.md     # Este archivo
│
├── 📄 LICENSE                 # Licencia MIT
└── 🔧 .gitignore              # Config Git
```

---

## 📄 Licencia

**MIT License** - Uso libre para proyectos personales y comerciales.

Ver archivo `LICENSE` para más detalles.

---

## 👨‍💻 Desarrollador

**Sarmiento**

---

## 🎉 ¡Listo para Usar!

Tu aplicación está completamente configurada y lista para:

1. ✅ Ejecutar localmente
2. ✅ Instalar como PWA
3. ✅ Desplegar en producción
4. ✅ Funcionar offline
5. ✅ Calcular valores glucémicos

---

## 📞 Soporte

Para preguntas o problemas:
- 📧 Contacta al desarrollador
- 🐛 Reporta issues en GitHub
- 📖 Consulta la documentación

---

**¡Gracias por usar Calculadora Glucémica PWA!** 🍎

---

*Última actualización: Noviembre 2025*
