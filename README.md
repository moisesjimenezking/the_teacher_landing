# The Teacher — Landing Page

Landing page informativa para la app **The Teacher** — un profesor de inglés con IA.

## Estructura

```
landing/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos
├── js/
│   └── main.js         # JavaScript (nav, smooth scroll)
├── img/
│   ├── hero.png        # Screenshot de la app
│   ├── logo.png        # Logo
│   ├── favicon.svg     # Favicon SVG
│   └── favicon.png     # Favicon PNG
├── .gitignore
└── README.md
```

## Secciones

- **Hero** — Titulo, descripcion, CTA de descarga APK, stats
- **Caracteristicas** — 6 cards con iconos SVG (voz, texto, TTS, lecciones, tiempo real, OpenRouter)
- **Tecnologías** — 8 cards del stack (React, Capacitor, Vite, FastAPI, Whisper, Edge TTS, OpenRouter, WebSocket)
- **Descarga** — Requisitos, boton APK, mockup animado del chat
- **Contacto** — Email, GitHub, LinkedIn con iconos SVG
- **Footer** — Branding

## Ver localmente

```bash
cd landing
python3 -m http.server 8080
```

Abre http://localhost:8080

## APK

El APK se descarga desde GitHub Releases:
https://github.com/moisesjimenezking/APK/releases/download/App_RapiConsulta/app-release.apk

## Personalizar

- **Contacto**: Edita las URLs en la seccion `#contact` del `index.html`
- **Colores**: Las variables CSS estan en `:root` dentro de `css/style.css`
- **Assets**: Reemplaza los archivos en `img/`
