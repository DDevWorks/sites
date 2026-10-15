# DDevWorks — sitio estático

Sitio web estático preparado para GitHub Pages, usando únicamente HTML, CSS y JavaScript nativo. No requiere Node.js, frameworks, compilación ni backend.

## Estructura

```text
/
├── index.html                 # Página principal
├── privacy.html               # Política de privacidad
├── terms.html                 # Términos y condiciones
├── README.md                  # Documentación del proyecto
└── assets/
    ├── css/
    │   └── styles.css         # Estilos, paleta, diseño responsive
    ├── js/
    │   └── main.js            # Menú móvil y año del footer
    └── img/
        └── favicon.svg        # Icono del sitio
```

## Publicar en GitHub Pages

1. Descomprime el ZIP.
2. Sube el contenido de la carpeta `ddevworks_web_mejorado` a la raíz de tu repositorio (no subas el ZIP dentro del repositorio).
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama que usas (por ejemplo, `main`) y la carpeta `/ (root)`. Guarda.
6. Espera a que GitHub Pages publique el sitio.

## Personalización

- Paleta y diseño responsive: `assets/css/styles.css`, en las variables CSS de `:root`.
- Navegación móvil y año automático: `assets/js/main.js`.
- Contenido principal: `index.html`.
- Privacidad: `privacy.html`.
- Términos: `terms.html`.
- Enlaces y correo: busca `ddevworks@gmail.com`, `ddevworks.blogspot.com` o el enlace de Google Play en los HTML.

## Antes de publicar

Revisa que la descripción de privacidad corresponda exactamente con el comportamiento real y los SDK/permisos incluidos en la versión publicada de Num Easy. Las páginas legales son una base editable, no asesoría legal.
