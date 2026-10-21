# DDevWorks — sitio estático para GitHub Pages

Sitio estático creado con **HTML, CSS y JavaScript nativo**. No necesita frameworks, instalación de paquetes, compilación ni backend. La web presenta las aplicaciones propias publicadas por Damian Rojas Castillo; no ofrece servicios de desarrollo por encargo.

## Estructura

```text
/
├── index.html
├── privacy.html
├── terms.html
├── README.md
└── assets/
    ├── css/styles.css
    ├── js/main.js
    └── img/
        ├── ddevworks-logo-completo-negro-puro.svg  # Logotipo original
        ├── favicon.svg                             # Símbolo de marca
        └── num-easy-logo.png                       # Añade aquí el logo de Num Easy
```

## Publicar en GitHub Pages

1. Descarga y descomprime el ZIP.
2. Sube **el contenido** de esta carpeta a la raíz del repositorio de GitHub (no subas el ZIP dentro del repositorio).
3. En el repositorio abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona tu rama (por ejemplo, `main`) y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub Pages complete la publicación.

## Dónde editar

- Textos, enlaces y secciones: `index.html`.
- Colores, responsive, animaciones y estilos: `assets/css/styles.css`.
- Menú móvil, año automático y animaciones de entrada: `assets/js/main.js`.
- Política y términos: `privacy.html` y `terms.html`.
- Logo completo y favicon: `assets/img/`.
- **Logo de Num Easy:** guarda la imagen en `assets/img/num-easy-logo.png`. La tarjeta de la aplicación lo mostrará automáticamente cuando el archivo exista. Si tu imagen es JPG o SVG, cambia la extensión en la ruta `src` de la etiqueta `.num-easy-logo` en `index.html`.

## Revisión antes de publicar

Verifica que la política de privacidad refleje exactamente el comportamiento real de Num Easy, sus permisos y cualquier SDK integrado. La página legal incluida es una base editable, no una certificación de cumplimiento legal. Confirma también que los términos coincidan con las condiciones reales de distribución de la aplicación.
