# Forja

App personal de entrenos, hábitos y finanzas. Web instalable (PWA) con cuentas y datos en Supabase.

- `index.html`: la app entera.
- `sw.js`: permite abrirla sin conexión.
- `manifest.webmanifest` e `icons/`: para instalarla en el móvil.

Los datos de cada usuario se guardan en la tabla `user_state` de Supabase, protegida para que cada cuenta solo vea lo suyo.
