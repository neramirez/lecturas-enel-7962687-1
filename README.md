# Lecturas hora a hora, cuenta Enel 7962687-1

Copia pública y permanente de la evidencia de la queja ante la Superintendencia de Servicios Públicos Domiciliarios contra Enel Colombia S.A. E.S.P., cuenta 7962687-1, medidor 22128053, Cajicá (Cundinamarca). Autogenerador a pequeña escala, CREG 174 de 2021.

- `index.html`: explorador día por día, octubre 2025 a septiembre 2026. Funciona sin conexión: todos los datos están dentro del archivo.
- `lecturas-horarias-7962687-1.csv`: 8.760 filas, una por hora, con las tres fuentes:
  - Enel: matriz horaria impresa en cada factura.
  - ECU APsystems: transformadores de corriente en la frontera con la red, muestra cada 5 minutos (registro local del equipo hasta el 1 sep 2026, nube APsystems EMA después).
  - Victron: consumo total de la casa, incluida la energía solar.
- `SHA256SUMS.txt`: huellas SHA-256 de los archivos publicados.

El historial de este repositorio fecha cada versión publicada.
