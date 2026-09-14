# Lista de control para publicar una Release

## Antes de compilar

- Exportar como **Sólo cuentas demo**.
- Confirmar que el nombre termina en `_DEMO_ONLY`.
- Compilar en **x64 Regular** y con cero errores.
- No incluir el MQ5 operativo.
- Probar el EX5 en Strategy Tester y en una cuenta demo.
- Confirmar que una cuenta real muestra el bloqueo de licencia.
- Confirmar que todos los ONNX cargan correctamente.

## ZIP

Debe contener:

- `*_DEMO_ONLY.ex5`
- carpeta `onnx`
- `manifest.json`
- `INSTALACION_ES.txt`
- `INSTALLATION_EN.txt`
- instalador opcional
- `SHA256.txt`

## Release

Título: `Símbolo · Señal · Dirección · TF · v1.0.0`

Etiqueta: `nombre-corto-v1.0.0`

La descripción debe enlazar la ficha del bot en el catálogo, indicar que es DEMO ONLY y repetir que los resultados históricos no garantizan resultados futuros.
