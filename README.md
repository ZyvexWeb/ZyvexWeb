# ZyvexWeb - Portfolio Website

Página web profesional de Yonaiker Contreras, desarrollador y diseñador web con diseño 100% responsive.

## 🚀 Despliegue

### Opción 1: Netlify (Recomendado)

1. Ve a [netlify.com](https://netlify.com)
2. Arrastra y suelta la carpeta `zyvexweb-miweb` en el área de despliegue
3. Tu sitio estará disponible en `https://[nombre].netlify.app`

### Opción 2: GitHub Pages

1. Crea un nuevo repositorio en GitHub (o usa uno existente)
2. Sube todos los archivos a la raíz del repositorio
3. Ve a Settings > Pages en tu repositorio
4. Selecciona "Deploy from a branch"
5. Elige la rama main/master
6. Tu sitio estará disponible en `https://[usuario].github.io/[repositorio]/`

**Nota importante para GitHub Pages:**
- El archivo principal debe llamarse `index.html`
- Incluye el archivo `.nojekyll` en la raíz para evitar conflictos con Jekyll
- Las redirecciones complejas pueden no funcionar igual que en Netlify

### Opción 3: Vercel

1. Ve a [vercel.com](https://vercel.com)
2. Conecta tu repositorio de GitHub
3. Vercel detectará automáticamente que es un sitio estático
4. Despliega con un clic

## ✨ Características

- ✅ **Diseño 100% responsivo** - Compatible con todos los dispositivos y pantallas
- ✅ **SEO optimizado** - Metadatos completos para motores de búsqueda
- ✅ **Performance ultra-optimizado** - Lazy loading, optimización de imágenes y videos
- ✅ **Accesibilidad WCAG 2.1** - Soporte completo para lectores de pantalla y navegación por teclado
- ✅ **PWA Ready** - Funciona como aplicación web progresiva
- ✅ **Sitios WordPress** - Desarrollo profesional con temas personalizados y optimización SEO
- ✅ **Mantenimiento incluido** - Primera actualización gratuita después de la entrega
- ✅ **Formulario de contacto** - Integrado con EmailJS
- ✅ **Animaciones suaves** - Scroll reveal y transiciones optimizadas
- ✅ **Navegación activa** - Resalta la sección actual
- ✅ **Videos de proyectos** - Con fallbacks y lazy loading
- ✅ **Favicon personalizado** - SVG e ICO incluidos
- ✅ **Configuración de despliegue** - Archivos optimizados

## 📱 Responsive Design Avanzado

### Breakpoints Implementados:
- **Ultra-wide Desktop**: 1400px+
- **Desktop Grande**: 1200px - 1399px
- **Desktop**: 1024px - 1199px
- **Tablet Grande**: 768px - 1023px
- **Tablet**: 481px - 767px
- **Móvil Grande**: 320px - 480px
- **Móvil Pequeño**: 320px - 379px

### Orientaciones Soportadas:
- Portrait y Landscape en móviles
- Optimizaciones específicas para cada dispositivo
- Menú hamburguesa adaptativo

### Optimizaciones por Dispositivo:
- **Videos**: Lazy loading con poster images
- **Imágenes**: Múltiples formatos (WebP, JPEG, PNG)
- **Fuentes**: Responsive typography scaling
- **Layout**: CSS Grid y Flexbox adaptativos
- **Interacciones**: Touch-friendly en móviles

## 🌐 Accesibilidad (WCAG 2.1 AA)

- **Navegación por teclado**: Focus visible y skip links
- **Lectores de pantalla**: ARIA labels, roles semánticos y landmarks
- **Alto contraste**: Media query support automático
- **Reducción de movimiento**: Respects `prefers-reduced-motion`
- **Color contrast**: Cumple con estándares AA
- **Tema automático**: Soporte para `prefers-color-scheme`
- **Focus management**: Gestión inteligente del foco

## ⚡ Optimizaciones de Performance

### Imágenes:
- Lazy loading implementado (`loading="lazy"`)
- Múltiples formatos con `<picture>` y `srcset`
- Decoding asíncrono (`decoding="async"`)
- Responsive images automáticas

### Videos:
- Lazy loading con `preload="metadata"`
- Múltiples formatos (MP4, WebM)
- Poster images para preview rápido
- Manejo robusto de errores con fallbacks

### CSS & JavaScript:
- Critical CSS optimizado
- Media queries por performance
- `will-change` para animaciones
- Intersection Observer para scroll effects
- Reduced motion support

### PWA:
- Manifest.json configurado
- Service Worker ready
- Offline capability
- App-like experience

## 📋 Archivos de Configuración

```
zyvexweb-miweb/
├── index.html              # Página principal optimizada
├── manifest.json           # Configuración PWA
├── robots.txt              # SEO y crawling optimization
├── favicon.svg             # Favicon SVG moderno
├── favicon.ico             # Favicon tradicional
├── logo-mi marca/          # Assets de la marca
│   └── Captura de pantalla 2025-10-22 033225.png
└── proyectos destacados/   # Videos optimizados
    ├── campana&asociados.mp4
    ├── campana&asociados.webm     # Formato recomendado
    ├── campana&asociados-thumb.jpg # Poster image
    ├── nexusvr.com.mp4
    ├── nexusvr.com.webm           # Formato recomendado
    └── nexusvr-thumb.jpg          # Poster image
```

## 🔧 Tecnologías utilizadas

- **HTML5** - Estructura semántica y accesible
- **CSS3** - Grid, Flexbox, Custom Properties, Media Queries avanzadas
- **JavaScript (ES6+)** - Interactividad optimizada
- **CSS Grid & Flexbox** - Layouts responsivos modernos
- **Intersection Observer API** - Animaciones de scroll eficientes
- **WebP & Modern formats** - Optimización de imágenes
- **PWA APIs** - Progressive Web App features
- **EmailJS** - Formularios de contacto sin backend

## 📧 Configuración de EmailJS

El formulario de contacto está configurado para usar EmailJS:

1. Service ID: `service_i9d4uc4`
2. Template ID: `template_65nzjga`
3. Email destino: `cyonaiker76@gmail.com`

Para probar la configuración, ejecuta `testEmailJS()` en la consola del navegador.

## 🎨 Personalización

### Variables CSS Principales

```css
:root {
    --primary: #00f5ff;      /* Cyan principal */
    --secondary: #7c3aed;    /* Purple secundario */
    --accent: #ff006e;       /* Rosa acento */
    --dark: #0a0a0a;         /* Fondo oscuro */
    --dark-light: #1a1a1a;   /* Fondo secundario */
    --text: #ffffff;         /* Texto principal */
    --text-gray: #a0a0a0;    /* Texto gris */
}
```

### Responsive Breakpoints

```css
/* Ultra-wide Desktop */
@media (max-width: 1400px) { /* Optimizaciones específicas */ }

/* Desktop */
@media (max-width: 1199px) { /* Layout adaptativo */ }

/* Tablet */
@media (max-width: 1023px) { /* Navegación mobile */ }

/* Mobile */
@media (max-width: 767px) { /* Layout single column */ }

/* Small Mobile */
@media (max-width: 480px) { /* Optimizaciones extremas */ }
```

## 🐛 Solución de problemas

### Problemas comunes de responsive

#### Layout se rompe en ciertos dispositivos
1. Verifica que el viewport meta tag esté correcto
2. Revisa las media queries específicas
3. Usa herramientas de developer tools para simular dispositivos

#### Imágenes no se cargan correctamente
1. Verifica las rutas de archivos
2. Asegúrate de que los formatos alternativos existan
3. Revisa la consola para errores de red

#### Animaciones no funcionan en algunos navegadores
1. Verifica que JavaScript esté habilitado
2. Revisa la compatibilidad de Intersection Observer
3. Considera fallbacks para navegadores antiguos

### Problemas específicos de GitHub Pages

#### Error 404 - Página no encontrada
1. **Verifica el nombre del archivo**: Asegúrate de que se llame `index.html`
2. **Archivo .nojekyll**: Incluye el archivo `.nojekyll` en la raíz del repositorio
3. **Rutas de archivos**: Todas las rutas en el HTML deben ser relativas y correctas
4. **Espera la publicación**: GitHub Pages puede tardar unos minutos en publicar cambios

#### Problemas con rutas de archivos
- Usa rutas relativas en lugar de absolutas
- Verifica que todas las imágenes y videos estén en las carpetas correctas
- Los nombres de archivos deben ser exactamente igual en el código y en el repositorio

#### Limitaciones de GitHub Pages
- No soporta redirecciones complejas como Netlify
- Algunos archivos de configuración de Netlify pueden no funcionar igual
- Considera usar Netlify o Vercel para funcionalidades avanzadas

## 🧪 Testing y Validación

### Herramientas recomendadas:
- **HTML Validation**: [W3C Validator](https://validator.w3.org/)
- **Accessibility**: [WAVE](https://wave.webaim.org/)
- **Performance**: [PageSpeed Insights](https://pagespeed.web.dev/)
- **Responsive**: [BrowserStack](https://www.browserstack.com/responsive)

### Dispositivos de prueba:
- iPhone SE (375x667)
- iPhone 12 Pro (390x844)
- iPad (768x1024)
- Desktop HD (1920x1080)
- Desktop 4K (3840x2160)

## 📞 Contacto

**Yonaiker Contreras**
- Email: cyonaiker76@gmail.com
- WhatsApp: +51 906 057 426
- Trabajo: 100% remoto (Toda Latinoamérica)

---

© 2025 ZyvexWeb - Todos los derechos reservados.
