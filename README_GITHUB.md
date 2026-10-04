# Soluciones Logísticas S & M

Página corporativa estática para GitHub Pages.

## Publicación

1. Sube `index.html`, `robots.txt` y `sitemap.xml` al repositorio de GitHub Pages.
2. En GitHub, selecciona **Settings → Pages** y publica desde la rama principal.
3. Verifica que el dominio productivo esté configurado como `www.transvago.mx`.
4. En FormSubmit, valida la cuenta del correo `contacto@transvago.mx` para activar el envío del formulario vía API.
5. (Opcional recomendado) Conecta Google Tag Manager o `gtag` para aprovechar los eventos de analítica (`cta_click`, `section_view`, `quote_request_success`, `quote_request_error`, `web_vital`).
6. Para métricas de rendimiento, el sitio reporta Core Web Vitals (LCP, CLS, INP, FCP, TTFB) a través de `web-vitals` y los envía como evento `web_vital`.
7. Se incluyó marcado estructurado JSON-LD tipo `LocalBusiness` en `index.html`.

La página no usa framework ni instalación adicional. Las fotografías de fondo se cargan desde Unsplash.
