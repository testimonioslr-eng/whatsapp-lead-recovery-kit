# Calculadora de oportunidades perdidas

Una calculadora de una página, sin backend, sin tracking y sin envío de datos a ningún servidor. Todo el cálculo corre en tu navegador.

## Qué hace

Toma tres números que vos ya conocés:

1. **Consultas nuevas por semana** (tu WhatsApp o el de tu equipo).
2. **Ticket promedio** en tu moneda.
3. **Tasa de cierre que tendrías si respondieras en menos de 5 minutos.**

Y un cuarto dato que ya elegís en un desplegable:

4. **Tu tiempo de respuesta actual** (cinco opciones, con los mismos factores del documento `revenue-at-risk.md`).

Devuelve tres columnas: lo que capturarías respondiendo rápido, lo que capturás hoy y la diferencia, por semana y por año.

## Por qué es una estimación, no un resultado auditado

La tabla de penalización por tiempo de respuesta es un default razonable que podés ajustar. La tasa de cierre rápida es 25% por default pero no está medida contra clientes reales tuyos. Cuando tengas tus propios números (después de medir una o dos semanas), reemplazá los valores y el cálculo te va a dar algo más cercano a tu realidad.

## Cómo usarla

- Abrí `calculator.html` desde el navegador, o desde la URL pública del repo si está hosteado en GitHub Pages.
- Modificá los números. El cálculo se actualiza mientras escribís.
- El resultado no se guarda ni se envía. Si recargás, empezás de nuevo.

## Privacidad

- No hay cookies.
- No hay red. El HTML y el JS están autocontenidos.
- No hay analítica. No hay pixel. No hay requests salientes.
- El único enlace saliente es al diagnóstico gratuito de LandingPixel, y solo se abre si vos hacés clic.

## Si te sirvió

Si te sirvió, lo más útil que podés hacer es enviársela a un conocido que tenga un negocio que atienda por WhatsApp y se queje de mensajes perdidos. Eso vale más que cualquier like.

## Si querés ver la versión integrada

La versión integrada (anuncio + landing + WhatsApp + tracking de tiempo de respuesta en un solo flujo) está disponible como diagnóstico gratuito en [LandingPixel](https://www.landingpixel.com/tiktok/). No requiere registro.
