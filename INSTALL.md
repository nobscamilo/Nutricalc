# 📦 Instalación - Calculadora Glucémica PWA

## 🚀 Inicio Rápido

### Opción 1: Servidor Local Simple
```bash
# Descomprimir el archivo
tar -xzf calculadora-glucemica-pwa.tar.gz
# o
unzip calculadora-glucemica-pwa.zip

# Navegar al directorio
cd calculadora-glucemica-pwa

# Iniciar servidor (Python 3)
python3 -m http.server 8000

# Abrir en navegador
# http://localhost:8000
```

### Opción 2: Con npm
```bash
npm start
```

### Opción 3: Servidor Node.js
```bash
# Instalar http-server globalmente
npm install -g http-server

# Ejecutar
http-server -p 8000
```

## 📱 Instalar como PWA

1. Abre la aplicación en tu navegador
2. Busca el botón "📲 Instalar" en la esquina superior derecha
3. Haz clic y confirma la instalación
4. La app se instalará como aplicación nativa

### En Chrome/Edge (Desktop)
- Busca el ícono ➕ en la barra de direcciones
- O ve a Menú → Instalar Calculadora Glucémica

### En Safari (iOS)
- Toca el botón Compartir
- Selecciona "Añadir a pantalla de inicio"

### En Chrome (Android)
- Toca el menú (⋮)
- Selecciona "Añadir a pantalla de inicio"

## 📂 Estructura de Archivos

```
calculadora-glucemica-pwa/
├── index.html                  # Página de inicio
├── app.html                    # Aplicación principal
├── manifest.json               # Configuración PWA
├── sw.js                       # Service Worker (offline)
├── package.json                # Configuración del proyecto
├── README.md                   # Documentación
├── INSTALL.md                  # Esta guía
├── LICENSE                     # Licencia MIT
└── .gitignore                  # Archivos ignorados por Git
```

## ✨ Características

- ✅ **Funciona Offline** - Gracias al Service Worker
- ✅ **Instalable** - Como app nativa en cualquier dispositivo
- ✅ **Responsive** - Adaptado a móvil, tablet y desktop
- ✅ **Base de datos local** - IndexedDB con 320+ alimentos
- ✅ **Scanner de códigos** - Escanea códigos de barras
- ✅ **Exportar datos** - CSV y PDF
- ✅ **Plantillas/Recetas** - Guarda tus comidas favoritas
- ✅ **Perfil de usuario** - Cálculos personalizados

## 🔧 Requisitos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Python 3 (para servidor local) o Node.js
- Conexión a internet (solo primera vez)

## 🌐 Despliegue en Producción

### GitHub Pages
```bash
# Subir a GitHub
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main

# Activar GitHub Pages en Settings → Pages
# Seleccionar rama 'main' y carpeta '/ (root)'
```

### Vercel
```bash
npm install -g vercel
vercel
```

### Netlify
```bash
npm install -g netlify-cli
netlify deploy
```

## 🐛 Solución de Problemas

### La app no se instala
- Verifica que estés usando HTTPS (o localhost)
- Asegúrate de que el Service Worker esté registrado
- Revisa la consola del navegador para errores

### No funciona offline
- Abre la app al menos una vez con internet
- Verifica que el Service Worker esté activo en DevTools

### El scanner no funciona
- Permite el acceso a la cámara cuando se solicite
- Verifica que estés usando HTTPS (requerido para cámara)

## 📞 Soporte

Para reportar problemas o sugerencias:
- Abre un issue en GitHub
- Contacta al desarrollador

## 📄 Licencia

MIT License - Ver archivo LICENSE para más detalles

---

**Desarrollado por Sarmiento** 🍎
