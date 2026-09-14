# Instalación en MetaTrader 5

## Requisitos

- Windows de 64 bits
- MetaTrader 5 actualizado
- cuenta demo o Strategy Tester
- EA compilado en modo x64 Regular

## Instalación automática

1. Descarga el ZIP desde Releases.
2. Descomprímelo completamente.
3. Ejecuta `INSTALAR_AUTOMATICO.bat`.
4. Selecciona la terminal portable si el instalador lo solicita.
5. Reinicia MetaTrader 5 o actualiza el Navegador.
6. Arrastra el EA terminado en `_DEMO_ONLY.ex5` al símbolo y timeframe indicados.
7. Activa Algo Trading y revisa las pestañas Expertos y Diario.

## Instalación manual

1. Copia el EX5 a `MQL5\Experts\T-Lab`.
2. Copia los ONNX a la ruta `Common\Files` indicada en `manifest.json`.
3. Reinicia MT5.
4. Comprueba que Consejero, Entradas y Cierres indiquen que sus ONNX están cargados.

## Licencia DEMO

El EA permite Strategy Tester y cuentas demo. En una cuenta real devuelve `INIT_FAILED` y no procesa ticks. El Strategy Tester siempre utiliza una cuenta simulada aunque tome datos de un servidor Live.

## Solución de problemas

- **SIN LECTURA:** verifica los ONNX y espera la carga de históricos H1/H4.
- **ONNX false:** confirma la carpeta exacta de `Common\Files`.
- **CPU incompatible:** utiliza el EX5 x64 Regular.
- **EA bloqueado:** confirma que la cuenta sea realmente demo.
