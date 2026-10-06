# Pasarela NEC

Aplicativo web interactivo para estimar cargas y reacciones gravitacionales de una pasarela metálica independiente y verificar zapatas corridas en sentidos X e Y.

## Uso

Abra `index.html` en un navegador. No requiere instalación ni compilación. También puede servir esta carpeta con cualquier servidor web estático.

Para GitHub Pages: en Settings > Pages seleccione Deploy from a branch, la rama main y la carpeta / (root).

## Modelo actual

- Tres pisos sin cubierta; altura inicial de entrepiso 3,25 m.
- Geometría y perfiles editables.
- Peso estructural separado de piso metálico, barandas y escaleras; todas estas cargas participan en las reacciones.
- Modelo matricial lineal de pórticos 2D para cargas gravitacionales.
- Dimensionamiento y verificación preliminar de zapatas corridas por eje, con actualización de ancho y espesor.

Las comprobaciones son preliminares. El modelo no sustituye un diseño estructural integral; no incluye análisis sísmico, viento, P-delta, vibraciones, conexiones ni asentamientos. Los perfiles propuestos y las hipótesis de cimentación requieren revisión profesional.

## Archivos

- index.html: interfaz.
- app.js: interacción, resultados y verificación de zapatas.
- structural.js: geometría, perfiles, inventario y cargas.
- frame2d.js: solucionador matricial de pórticos.
- Imágenes PNG: referencias de implantación y cortes.
