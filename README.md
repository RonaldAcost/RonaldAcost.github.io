# GitHub Pages — /docs
Publicación desde la carpeta **/docs**.

## Estructura
```
docs/
├── assets/
│   ├── favicon.ico
│   ├── og-image.png
│   └── style.css
├── data-engineer.html
└── index.html
```

## Cómo publicar
1. Sube este repo a GitHub.
2. En **Settings → Pages** elige **Source = Deploy from a branch** y **Branch = main** y **/docs**.
3. Guarda. Tu sitio quedará disponible como `https://<tu-usuario>.github.io/` (o `/<repo>` si no usas repo de usuario).
4. El **modo claro/oscuro** se guarda en `localStorage` con clave `pref-theme`.
5. El checklist se guarda en `localStorage` con clave `rex-platzi-de-checklist-v2` y la landing lee esa clave para el **roadmap por fases**.
6. cambio para descargar en vsc
