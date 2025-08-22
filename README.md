# RentiGO 🚗

Una plataforma web moderna para el alquiler de vehículos, diseñada para ofrecer una experiencia de usuario intuitiva y profesional.

## 🌟 Características

- **Catálogo completo** de vehículos organizados por categorías
- **Interfaz moderna** y responsive
- **Sistema de reservas** integrado
- **Múltiples categorías** de vehículos (económicos, SUVs, híbridos, etc.)
- **Formulario de contacto** funcional
- **Autenticación** de usuarios (login/registro)

## 🚀 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Diseño moderno con Grid y Flexbox
- **JavaScript** - Interactividad (próximamente)
- **Diseño Responsive** - Compatible con todos los dispositivos

## 📁 Estructura del Proyecto

```
RentiGO/
├── index.html          # Página principal
├── categorias.html     # Catálogo de vehículos
├── contacto.html       # Página de contacto
├── login.html          # Iniciar sesión
├── registro.html       # Crear cuenta
├── style.css          # Estilos principales
└── assets/            # Imágenes y recursos
    ├── favicon.png
    ├── hero.png
    ├── grupo-*.png    # Imágenes de categorías
    ├── mapa.png
    └── fondo.png
```

## 🎨 Categorías de Vehículos

### Disponibles:
- **Grupo C** - Económico con aire mecánico
- **Grupo F** - Intermedio mecánico
- **Grupo FL** - Mecánico libre de pico y placa
- **Grupo FU** - Automático sin pico y placa
- **Grupo FX** - Intermedio automático
- **Grupo G4** - SUV mecánica 4x4
- **Grupo GL** - SUV AT sin pico y placa
- **Grupo GY** - SUV híbrido
- **Grupo LE** - SUV especial

## 🛠️ Instalación y Uso

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/rentigo.git
   cd rentigo
   ```

2. **Abrir en un servidor local:**
   - Opción 1: Live Server (VS Code)
   - Opción 2: Python HTTP Server
     ```bash
     python -m http.server 8000
     ```
   - Opción 3: Node.js HTTP Server
     ```bash
     npx http-server
     ```

3. **Acceder a la aplicación:**
   ```
   http://localhost:8000
   ```

## 📱 Páginas Principales

### 🏠 Inicio (`index.html`)
- Hero section con llamada a la acción
- Formulario de búsqueda de reservas
- Sección "¿Por qué elegir RentiGO?"
- Marcas de vehículos disponibles

### 🚗 Categorías (`categorias.html`)
- Catálogo completo de vehículos
- 9 grupos diferentes de vehículos
- Información detallada de cada categoría
- Botones de reserva directa

### 📞 Contacto (`contacto.html`)
- Formulario de contacto
- Información de ubicación
- Mapa integrado
- Datos de contacto

### 🔐 Autenticación
- **Login** (`login.html`) - Iniciar sesión
- **Registro** (`registro.html`) - Crear cuenta nueva

## 🎨 Diseño y UX

- **Paleta de colores:** Minimalista en blanco, negro y grises
- **Tipografía:** Roboto para legibilidad óptima
- **Layout:** Grid y Flexbox para diseño responsive
- **Animaciones:** Transiciones suaves y hover effects

## 📋 Características Técnicas

- ✅ **Responsive Design** - Adaptable a móviles, tablets y desktop
- ✅ **SEO Optimizado** - Meta tags y estructura semántica
- ✅ **Accesibilidad** - Labels y navegación por teclado
- ✅ **Performance** - Imágenes optimizadas y CSS eficiente
