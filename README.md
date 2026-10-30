# *✅✨ GathSession*

***Landing page de **GathSession**, desarrollada para la segunda tarea entregable de CSS. El proyecto presenta una comunidad en línea mediante un encabezado con navegación, una sección principal y una galería asimétrica de cinco retratos.***

## *✅✨ Presentación*

***La propuesta sigue la composición, los textos y la paleta oscura con acentos rosas de la diapositiva de referencia. Se trabajó con HTML semántico y Sass organizado por componentes; la hoja CSS compilada permite abrir y publicar el sitio directamente, sin instalar dependencias en producción.***

***Las ilustraciones de la galería son SVG locales creados para esta versión. Los iconos de beneficios y la flecha también son SVG. No se incluyen recursos externos.***

## *✅✨ Contenido del proyecto*

- **Navegación:** Home, Features, Blog, Contact y About Us.
- **Hero:** titular, texto descriptivo, botones Get Started y Learn More.
- **Beneficios:** Build Community, Share Events y Get Information.
- **Galería:** cinco retratos en columnas asimétricas con fondos de color.
- **Interacción:** estados hover y foco visible en enlaces y botones.
- **Adaptabilidad:** la composición se acomoda a distintos anchos de pantalla sin desbordamiento horizontal.

## *✅✨ Estructura*

```text
📂Proyecto-GS
├── .github
│   └── 📂workflows
│       └── deploy.yml          # Compilación y publicación en GitHub Pages
├── 📂gathsession-project
│   ├── .gitignore
│   ├── package.json
│   ├── package-lock.json
│   └── 📂mi-proyecto-spa
│       ├── index.html
│       ├── 📂assets/images      # Cinco ilustraciones SVG locales
│       ├── 📂css/style.css       # CSS listo para usar y publicar
│       └── 📂scss               # Fuentes Sass por componente
├── LICENSE
└── README.md
```

***La carpeta `gathsession-project` reúne el código, los recursos y las herramientas propias de la página. El README, la licencia y el flujo de publicación quedan en la raíz del repositorio para que GitHub los detecte correctamente.***

## *✅✨ Ejecutar y compilar*

***Se requiere Node.js y npm. Desde `gathsession-project`:***

```bash
npm ci
npm run build
```

***Esto genera `mi-proyecto-spa/css/style.css` a partir de Sass. Para recompilar mientras se edita:***

```bash
npm run watch
```

***Abre `mi-proyecto-spa/index.html` en el navegador; el sitio no necesita servidor ni JavaScript.***

## *✅✨ Repositorio y publicación*

- **Repositorio:** [Proyecto-GS-SCSS-CSS-TAREA](https://github.com/valentinoaguiarhirales1-art/Proyecto-GS-SCSS-CSS-TAREA)
- **Sitio:** `https://valentinoaguiarhirales1-art.github.io/Proyecto-GS-SCSS-CSS-TAREA` (disponible cuando GitHub Pages esté habilitado y termine el flujo de publicación).

***El flujo de la carpeta `.github/workflows` intenta habilitar GitHub Pages automáticamente, compila Sass y publica `gathsession-project/mi-proyecto-spa` al subir cambios a `main` o `master`. Si la cuenta no permite habilitar Pages automáticamente (por ejemplo, por la visibilidad privada del repositorio o el plan de GitHub), configura **Settings → Pages → Build and deployment → GitHub Actions** o cambia la visibilidad según lo que requiera la entrega. Cuando el despliegue termine, comparte el repositorio y la dirección publicada, y adjunta la captura en la plataforma de clase.***

## *📄✨ Licencia*

***El proyecto está bajo licencia MIT. Consulta el archivo [LICENSE](./LICENSE).***
