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

## Notas
1. El checklist guarda progreso en `localStorage` con clave **`rex-platzi-de-checklist-v2`**.
2. La landing lee esa misma clave y muestra el **porcentaje por fase automáticamente**.
3. Tema claro/oscuro sincronizado con `pref-theme`.