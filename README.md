# kairooagtech.com

Sitio estático de Kairoo AgTech (HTML + CSS + JS, sin build).

- `index.html` — home
- `akkademy.html` — landing del curso AKKADEMY
- `img/` — imágenes

Cada push a `main` se publica solo en kairooagtech.com (Cloudflare Pages).

## Números de impacto
Las hectáreas de la sección "Impacto" y del hero se leen al cargar la página desde la app Kairoo
(Supabase, función `estadisticas_publicas_web`: solo devuelve totales de órdenes finalizadas/pdf_listo).
Agua = ha pulverizadas × 63,5 L. CO₂ = ha totales × 26/5250 Tn. Clientes = tabla `web_stats` (clave `clientes`), que una tarea programada actualiza cada semana desde la planilla "1 - Archivo master" (hoja Facturación, clientes distintos de Servicios).
Los números escritos en el HTML son el respaldo si Supabase no responde.
