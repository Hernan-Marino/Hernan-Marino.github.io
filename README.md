# Portfolio de Hernán Marino

Portfolio profesional de Técnico Analista de Sistemas.

## 🚀 Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- GitHub Pages

## 📁 Estructura del Proyecto

```
portfolio/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos
├── js/
│   └── main.js         # Interactividad
└── README.md           # Documentación
```

## 🌐 Despliegue en GitHub Pages

### Paso 1: Crear repositorio en GitHub
1. Ve a GitHub y crea un nuevo repositorio
2. Nómbralo: `Hernan-Marino.github.io` (importante: debe ser tu-usuario.github.io)
3. Márcalo como público
4. NO inicialices con README

### Paso 2: Subir el código

Desde tu terminal, en la carpeta del portfolio, ejecutá:

```bash
# Inicializar repositorio Git
git init

# Agregar todos los archivos
git add .

# Hacer el primer commit
git commit -m "Initial commit: Portfolio completo"

# Conectar con GitHub (reemplazá con tu URL)
git remote add origin https://github.com/Hernan-Marino/Hernan-Marino.github.io.git

# Subir a GitHub
git branch -M main
git push -u origin main
```

### Paso 3: Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Clickeá en "Settings" (Configuración)
3. En el menú lateral, buscá "Pages"
4. En "Source", seleccioná "main" branch
5. Guardá los cambios

### Paso 4: Acceder a tu portfolio
Después de unos minutos, tu portfolio estará disponible en:
`https://Hernan-Marino.github.io`

## 📝 Personalización

### Agregar nuevos proyectos
Editá `index.html` en la sección de proyectos y agregá un nuevo `.proyecto-card`.

### Cambiar colores
Editá las variables CSS en `css/style.css`:
```css
:root {
    --primary-color: #3498DB;
    --secondary-color: #1ABC9C;
    /* ... más colores */
}
```

### Agregar imágenes
1. Creá una carpeta `images/` en la raíz
2. Agregá tus imágenes
3. Actualizá las rutas en `index.html`

## 🔄 Actualizar el portfolio

Cuando hagas cambios:

```bash
git add .
git commit -m "Descripción de los cambios"
git push
```

Los cambios se verán reflejados en unos minutos en tu sitio.

## 📧 Contacto

- Email: hernanemarino@gmail.com
- LinkedIn: [linkedin.com/in/hernan-marino](https://www.linkedin.com/in/hernan-marino)
- GitHub: [github.com/Hernan-Marino](https://github.com/Hernan-Marino)

---

Desarrollado con ❤️ por Hernán Marino
