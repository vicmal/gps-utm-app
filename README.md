# gps-utm-app

Aplicación GPS para teléfono: lector GPS / UTM para trabajo de campo.

- Seguimiento GPS en vivo (con fusión de lecturas y distintivo de calidad según la precisión reportada).
- Puntos de ruta manuales, distancia total y por tramos, exportación a CSV y GPX.
- Polígonos por digitalización en el mapa, grabación GPS vértice a vértice o tabla UTM manual; área en m², ha y km², y exportación a CSV.
- Guardado automático en el teléfono: al reabrir la app, la ruta y el polígono se restauran tal cual quedaron.
- Al abrir, el mapa se centra en el último punto GPS guardado o, si no hay ninguno, en Caracas (Venezuela).

Sin backend: todo se procesa en el navegador. Datum WGS84. Mapa base: Esri World Imagery y OpenStreetMap (requiere conexión a internet).
