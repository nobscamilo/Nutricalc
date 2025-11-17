# Calculadora Glucémica PWA 🍎

[![pages-build-deployment](https://github.com/nobscamilo/Nutricalc/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/nobscamilo/Nutricalc/actions/workflows/pages/pages-build-deployment)

Una aplicación web progresiva (PWA) para calcular índice y carga glucémica de alimentos con funcionalidades offline, scanner de códigos de barras y gestión de recetas.

## 🚀 Launch App

[![Launch App](https://img.shields.io/badge/Launch-App-2e8b57?style=for-the-badge&logo=rocket)](https://nobscamilo.github.io/Nutricalc/)

**[🌐 Abrir Calculadora Glucémica](https://nobscamilo.github.io/Nutricalc/)**

## 📥 Descargar Aplicación Completa

La aplicación está disponible para descarga en dos formatos:

- **[⬇️ Descargar ZIP](calculadora-glucemica-pwa.zip)** (49 KB) - Compatible con Windows, Mac, Linux
- **[⬇️ Descargar TAR.GZ](calculadora-glucemica-pwa.tar.gz)** (46 KB) - Formato Unix/Linux

### 🚀 Inicio Rápido

```bash
# Descomprimir
unzip calculadora-glucemica-pwa.zip
# o
tar -xzf calculadora-glucemica-pwa.tar.gz

# Iniciar servidor
python3 -m http.server 8000

# Abrir en navegador
# http://localhost:8000
```

📖 Ver [INSTALL.md](INSTALL.md) para instrucciones detalladas de instalación.

## ✨ Características

- 📱 **PWA** - Instalable como aplicación nativa en cualquier dispositivo
- 📡 **Modo Offline** - Funciona 100% sin conexión después de la primera carga
- 📷 **Scanner** - Escanea códigos de barras de productos
- 🍽️ **Recetas** - Guarda y carga plantillas de comidas
- 👤 **Perfiles** - Gestión de perfiles de usuario con cálculos personalizados
- 📊 **Exportación** - Exporta datos a CSV y PDF
- ⚡ **Optimizado** - Búsqueda rápida con estructura Trie
- 📱 **Responsive** - Diseño adaptado a móvil, tablet y desktop
- 🗄️ **Base de datos** - 320+ alimentos precargados en IndexedDB

## 📊 Métricas Calculadas

- **CG Total**: Carga Glucémica total de la comida
- **IG Ponderado**: Índice Glucémico promedio ponderado por carbohidratos
- **IRE**: Índice de Respuesta Estimada (CG / kg de peso corporal)
- **VG**: Valor Glucémico por cada 100 kcal

## 🛠️ Tecnologías

- HTML5
- CSS3 (Variables CSS, Grid, Flexbox)
- JavaScript (Vanilla ES6+)
- Service Workers (PWA)
- IndexedDB (Almacenamiento local)
- Quagga.js (Scanner de códigos)
- jsPDF (Exportación PDF)

## 📦 Instalación Local

### Opción 1: Desde descarga

```bash
# Descargar y descomprimir
unzip calculadora-glucemica-pwa.zip
cd calculadora-glucemica-pwa

# Iniciar servidor
python3 -m http.server 8000
```

### Opción 2: Desde repositorio

```bash
# Clonar repositorio
git clone https://github.com/nobscamilo/Nutricalc.git
cd Nutricalc

# Iniciar servidor
python3 -m http.server 8000
# o con Node.js
npx serve
```

### Opción 3: Con npm

```bash
npm start
```

Visita `http://localhost:8000` en tu navegador.

## 📱 Instalar como Aplicación

### Desktop (Chrome/Edge)
1. Abre la aplicación en el navegador
2. Busca el ícono ➕ en la barra de direcciones
3. O haz clic en el botón "📲 Instalar"

### iOS (Safari)
1. Abre la aplicación
2. Toca el botón Compartir
3. Selecciona "Añadir a pantalla de inicio"

### Android (Chrome)
1. Abre la aplicación
2. Toca el menú (⋮)
3. Selecciona "Añadir a pantalla de inicio"

## 🌐 Despliegue en Producción

### GitHub Pages

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/nobscamilo/Nutricalc.git
git push -u origin main
```

Luego activa GitHub Pages en Settings → Pages → Source: main branch

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

## 📂 Estructura del Proyecto

```
calculadora-glucemica-pwa/
├── index.html                  # Página de inicio
├── app.html                    # Aplicación principal
├── manifest.json               # Configuración PWA
├── sw.js                       # Service Worker
├── package.json                # Configuración npm
├── README.md                   # Este archivo
├── INSTALL.md                  # Guía de instalación
├── DOWNLOAD_INFO.txt           # Información de descarga
├── LICENSE                     # Licencia MIT
└── .gitignore                  # Archivos ignorados
```

## 🧪 Testing

La aplicación incluye un botón de tests integrado (🧪 Tests) que verifica:

- ✅ Búsqueda Trie
- ✅ Agregar alimentos
- ✅ Cálculos de CG
- ✅ Perfil de usuario
- ✅ IndexedDB

## 🔧 Requisitos

- Navegador moderno (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Python 3 o Node.js (para servidor local)
- Conexión a internet (solo primera vez)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Autor

**Sarmiento**

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📞 Soporte

Para reportar problemas o sugerencias, abre un issue en GitHub.

---

**Powered by Sarmiento** 🍎
