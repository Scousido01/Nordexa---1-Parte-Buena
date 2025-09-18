# nodexa - Página Web Profesional

Página web profesional para **nodexa**, una empresa especializada en automatización con n8n para pequeñas y medianas empresas (pymes) en España.

## 📋 Información del Proyecto

- **Empresa**: nodexa
- **Fundador**: Sergio Cousido
- **Ubicación**: Vigo, España
- **Especialidad**: Automatizaciones para pymes
- **Tecnología**: n8n

## 🎨 Características del Diseño

### Paleta de Colores
- **Color Primario**: Azul oscuro (#0A2540)
- **Color de Acento**: Verde (#2ECC71)
- **Colores Neutros**: Blancos y grises claros
- **Tipografía**: Inter (Google Fonts)

### Diseño Responsive
- ✅ Mobile-first approach
- ✅ Navegación móvil con hamburger menu
- ✅ Grid layouts adaptativos
- ✅ Imágenes optimizadas

## 📁 Estructura de Archivos

```
connectiva/
├── index.html              # Página de inicio
├── automatizaciones.html   # Página de servicios
├── contacto.html          # Página de contacto y sobre mí
├── styles.css             # Estilos CSS principales
├── script.js              # Funcionalidad JavaScript
└── README.md              # Este archivo
```

## 🚀 Páginas del Sitio

### 1. Página de Inicio (`index.html`)
- **Sección Hero**: Presentación principal con CTA
- **Problemas Comunes**: 3 tarjetas con iconos
- **Cómo Funciona**: 3 pasos del proceso
- **Footer**: Enlaces y información de contacto

### 2. Página de Automatizaciones (`automatizaciones.html`)
- **Paquetes Prediseñados**: 3 servicios principales
  - Recepcionista Virtual IA
  - Chatbot Web Inteligente
  - Gestor de Citas 24/7
- **Soluciones a Medida**: Sección personalizada

### 3. Página de Contacto (`contacto.html`)
- **Sección Sobre Mí**: Información de Sergio Cousido
- **Formulario de Contacto**: Campos para contacto
- **Información Adicional**: Email directo y detalles

## ⚡ Funcionalidades JavaScript

### Navegación
- Menú hamburger responsive
- Animaciones suaves de navegación
- Cierre automático del menú móvil

### Formulario de Contacto
- Validación de campos en tiempo real
- Validación de email
- Notificaciones de éxito/error
- Simulación de envío

### Animaciones
- Efectos de scroll con Intersection Observer
- Contadores animados para estadísticas
- Efectos hover en tarjetas
- Parallax suave en hero section

### Optimizaciones
- Throttling para eventos de scroll
- Lazy loading preparado para imágenes
- Transiciones CSS optimizadas

## 🎯 Características Técnicas

### HTML5 Semántico
- Estructura semántica correcta
- Meta tags para SEO
- Accesibilidad básica

### CSS3 Moderno
- CSS Grid y Flexbox
- Variables CSS (Custom Properties)
- Media queries responsive
- Animaciones y transiciones

### JavaScript ES6+
- Arrow functions
- Template literals
- Destructuring
- Intersection Observer API

## 🔧 Instalación y Uso

### Requisitos
- Navegador web moderno
- Servidor web (opcional para desarrollo local)

### Instalación Local
1. Descarga todos los archivos
2. Abre `index.html` en tu navegador
3. Para desarrollo, usa un servidor local:
   ```bash
   # Con Python
   python -m http.server 8000
   
   # Con Node.js
   npx serve .
   
   # Con PHP
   php -S localhost:8000
   ```

### Despliegue
- Sube todos los archivos a tu servidor web
- Asegúrate de que el servidor soporte HTML, CSS y JavaScript
- Configura el dominio para apuntar a `index.html`

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px - 480px
- **Mobile**: < 480px

## 🎨 Personalización

### Cambiar Colores
Edita las variables CSS en `styles.css`:
```css
:root {
    --primary-color: #0A2540;    /* Color principal */
    --accent-color: #2ECC71;     /* Color de acento */
    /* ... más variables */
}
```

### Cambiar Contenido
- Edita el texto directamente en los archivos HTML
- Actualiza la información de contacto
- Modifica los servicios según necesidades

### Agregar Funcionalidades
- El espacio para chatbot está preparado en la esquina inferior derecha
- Puedes integrar formularios con servicios como Formspree, Netlify Forms, etc.
- Agregar analytics (Google Analytics, etc.)

## 🔒 Seguridad y Privacidad

- No se almacenan datos sensibles
- Formulario preparado para integración con servicios seguros
- Sin dependencias externas críticas

## 📈 SEO y Rendimiento

### Optimizaciones Incluidas
- Meta tags descriptivos
- Estructura HTML semántica
- CSS y JS optimizados
- Imágenes con lazy loading preparado

### Mejoras Recomendadas
- Agregar sitemap.xml
- Configurar Google Analytics
- Optimizar imágenes con WebP
- Implementar Service Worker para PWA

## 🤝 Soporte

Para soporte técnico o personalizaciones:
- Email: sergio@nodexa.com
- Ubicación: Vigo, España

## 📄 Licencia

Este proyecto está diseñado específicamente para nodexa. Todos los derechos reservados.

---

**Desarrollado con ❤️ para automatizar el éxito de las pymes españolas** 