# ZyvexWeb - Portfolio Website

Página web profesional de Yonaiker Contreras, desarrollador y diseñador web.

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

- ✅ **Diseño responsivo** - Se adapta a todos los dispositivos
- ✅ **SEO optimizado** - Metadatos completos para motores de búsqueda
- ✅ **Sitios WordPress** - Desarrollo profesional con temas personalizados y optimización SEO
- ✅ **Mantenimiento incluido** - Primera actualización gratuita después de la entrega
- ✅ **Formulario de contacto** - Integrado con EmailJS
- ✅ **Animaciones suaves** - Scroll reveal y transiciones
- ✅ **Navegación activa** - Resalta la sección actual
- ✅ **Videos de proyectos** - Con fallbacks para errores
- ✅ **Favicon personalizado** - SVG e ICO incluidos
- ✅ **Configuración de despliegue** - Archivos optimizados

## 📁 Estructura del proyecto

```
zyvexweb-miweb/
├── index.html          # Página principal
├── favicon.svg         # Favicon SVG moderno
├── favicon.ico         # Favicon tradicional
├── _redirects          # Configuración de redirecciones
├── netlify.toml        # Configuración de Netlify
├── logo-mi marca/      # Logo de la empresa
│   └── Captura de pantalla 2025-10-22 033225.png
└── proyectos destacados/  # Videos de proyectos
    ├── campana&asociados.mp4
    └── nexusvr.com.mp4
```

## 🔧 Tecnologías utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Animaciones y diseño moderno
- **JavaScript (ES6+)** - Interactividad y funcionalidades
- **React** - Framework frontend moderno
- **Node.js** - Entorno de ejecución JavaScript
- **WordPress** - CMS para sitios web profesionales
- **EmailJS** - Envío de formularios por email
- **Intersection Observer API** - Animaciones al hacer scroll
- **CSS Grid & Flexbox** - Layout responsivo

## 📧 Configuración de EmailJS

El formulario de contacto está configurado para usar EmailJS:

1. Service ID: `service_i9d4uc4`
2. Template ID: `template_65nzjga`
3. Email destino: `cyonaiker76@gmail.com`

Para probar la configuración, ejecuta `testEmailJS()` en la consola del navegador.

## 🎨 Personalización

### Colores principales

```css
--primary: #00f5ff;    /* Cyan */
--secondary: #7c3aed;  /* Purple */
--accent: #ff006e;     /* Pink */
--dark: #0a0a0a;       /* Dark background */
```

### Fuentes

- Principal: 'Inter'
- Fallback: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif

## 📱 Responsive Design

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## 🐛 Solución de problemas

### El formulario no envía emails

1. Verifica que EmailJS esté cargado correctamente
2. Ejecuta `testEmailJS()` en la consola para probar
3. Revisa las credenciales en EmailJS dashboard

### Los videos no se reproducen

- Los videos tienen fallbacks automáticos
- Verifica que los archivos estén en `proyectos destacados/`

### Problemas de carga

- Los estilos están inline para carga más rápida
- Los archivos tienen headers de cache optimizados

### Problemas específicos de GitHub Pages

#### Error 404 - Página no encontrada
1. **Verifica el nombre del archivo**: Asegúrate de que se llame `index.html` (no `index.html.html`)
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

## 📞 Contacto

**Yonaiker Contreras**
- Email: cyonaiker76@gmail.com
- WhatsApp: +51 906 057 426
- Trabajo: 100% remoto

---

© 2025 ZyvexWeb - Todos los derechos reservados.
