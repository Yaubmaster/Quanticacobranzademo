# Yaub × Quantica · Demo de cobranza

Landing de demo (Bogotá 2026). Sitio estático: `index.html` + `assets/` (runtime, fuentes, logos) + `voces/` (muestras de audio).

- Desplegado en Vercel: https://quanticacobranzademo.vercel.app
- `source/standalone-export.html` es el export original de Claude Design (bundle); `index.html` se desempacó de ahí y se le agregó CSS responsive al final del bloque `<style>` del `<helmet>`.
- Los estilos inline los normaliza React (`font-size: 104px`), por eso los selectores responsive usan esa forma con espacio.
