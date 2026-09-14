# MetaTrader 5 installation

## Requirements

- 64-bit Windows
- updated MetaTrader 5 terminal
- demo account or Strategy Tester
- x64 Regular EX5 build

## Automatic installation

1. Download the ZIP from Releases and extract it.
2. Run `INSTALAR_AUTOMATICO.bat`.
3. Select the portable terminal if requested.
4. Restart MT5 or refresh the Navigator.
5. Attach the `_DEMO_ONLY.ex5` file to the documented symbol and timeframe.
6. Enable Algo Trading and check the Experts and Journal tabs.

## Manual installation

Copy the EX5 to `MQL5\Experts\T-Lab`. Copy every ONNX model to the `Common\Files` folder declared in `manifest.json`.

## Demo restriction

The EA runs in Strategy Tester and demo accounts. It returns `INIT_FAILED` on real accounts. Strategy Tester uses a simulated account even when historical data comes from a Live server.
