# Informe de marketing · Estrella Insurance #375

Informe mensual de resultados de marketing digital elaborado por Boudin Agency.

- `index.html`: el informe completo (página estática, sin dependencias de compilación).
- Los datos de cada mes están dentro de `index.html`, en el bloque `<script id="datos-informe" type="application/json">`.
- Se despliega en Vercel como sitio estático: no requiere comando de build ni carpeta de salida.

Para actualizar un mes, se reemplaza `index.html` por la versión nueva y Vercel publica el cambio automáticamente.
