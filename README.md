# Neobrutalism Linktree - Ema Enríquez ⚡

Un Linktree personalizado desarrollado con **HTML5 y CSS3 puro** (sin JavaScript ni frameworks extra), siguiendo el estilo visual **Neobrutalism UI / Bento Box Grid** e inspirado en el diseño de referencia.

---

## 🎨 Características de Diseño
- **Estilo Neobrutalism UI**: Bordes negros contrastados (2.5px solid), sombras duras con desplazamiento (tactile offset shadow `4px 4px 0px #000`), bordes redondeados orgánicos (`18px`) y tipografía geométrica bold (*Space Grotesk* + *Plus Jakarta Sans*).
- **Layout Bento Grid Grid**: Tarjeta héroe destacada para el **Portafolio** y tarjetas simétricas coloridas para redes sociales (GitHub, LinkedIn, Instagram, X).
- **Interacciones Táctiles en CSS**: Efecto de botón físico presionado en `:hover` y `:active` mediante transformaciones CSS.
- **100% Responsivo**: Se adapta perfectamente a pantallas de teléfonos móviles, tablets y escritorio.

---

## 🔗 Redes Incluidas
1. 🌐 **Portafolio Web**: [emaenriquez.vercel.app](https://emaenriquez.vercel.app)
2. 💻 **GitHub**: [github.com/emaenriquez](https://github.com/emaenriquez)
3. 💼 **LinkedIn**: [linkedin.com/in/emaenriquez](https://www.linkedin.com/in/emaenriquez)
4. 📸 **Instagram**: [instagram.com/emaenriquez.design](https://www.instagram.com/emaenriquez.design/)
5. 🐦 **X (Twitter)**: [x.com/EmanuelEnr60383](https://x.com/EmanuelEnr60383)

---

## 🛠️ Cómo Personalizar

### 1. Cambiar tu foto de perfil (Avatar)
En el archivo [`index.html`](file:///c:/Users/Usuario/Desktop/redes/index.html#L31), reemplaza la URL de la etiqueta `<img>` por la ruta a tu propia foto (ej. `assets/foto.jpg`):

```html
<img src="tu-foto.jpg" alt="Ema Enríquez" class="avatar-img" />
```

### 2. Ajustar Colores de las Tarjetas
En el archivo [`styles.css`](file:///c:/Users/Usuario/Desktop/redes/styles.css#L10), puedes modificar las variables CSS principales al inicio del archivo:

```css
:root {
  --bg-yellow: #FFCF00;       /* Color de fondo principal */
  --tile-portfolio: #E08C84;  /* Color tarjeta Portafolio */
  --tile-github: #A78BFA;     /* Color tarjeta GitHub */
  --tile-linkedin: #526760;   /* Color tarjeta LinkedIn */
  --tile-instagram: #F4A261;  /* Color tarjeta Instagram */
  --tile-x: #90E0EF;          /* Color tarjeta X */
}
```

---

## 🚀 Cómo Desplegar Gratis

1. **Vercel**: Importa directamente esta carpeta en Vercel. Detectará `index.html` automáticamente.
2. **GitHub Pages**: Sube los archivos a un repositorio de GitHub y activa GitHub Pages en *Settings > Pages*.
3. **Netlify**: Arrastra y suelta la carpeta `redes` en Netlify Drop.
