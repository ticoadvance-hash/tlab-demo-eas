# Catálogo inicial de EA demo

Selección realizada el 14 de septiembre de 2026 desde el Banco de Estrategias IA. Ninguna de estas estrategias pertenece actualmente a un portfolio. Depósito de referencia de los workflows: USD 10,000. Proveedor de la prueba MAIN: Darwinex-Live. MAIN usa modelo 4 (ticks reales).

> Estas cifras describen pruebas históricas guardadas en T-Lab. No representan expectativas ni garantías.

## Resumen

| ID | Estrategia | Mercado | Dirección | MAIN | PF | Neto USD | DD % | Floating USD | Trades | Win rate |
|---:|---|---|---|---|---:|---:|---:|---:|---:|---:|
| 25 | ADX + Dirección | XTIUSD H1 | BUY | 2016-01-01 → 2026-09-07 | 6.91 | 7,034.07 | 7.96 | 839.90 | 473 | 67.86% |
| 44 | Reversión VWAP | XTIUSD H1 | BUY | 2016-01-01 → 2026-09-08 | 5.14 | 3,974.75 | 6.48 | 809.78 | 430 | 87.21% |
| 728 | Barrido de sesión | GBPUSD H1 | SELL | 2016-01-01 → 2026-09-09 | 7.28 | 675.08 | 1.07 | 115.35 | 210 | 88.57% |
| 754 | Barrido de sesión | GBPUSD H1 | BUY | 2016-01-01 → 2026-09-10 | 2.11 | 981.53 | 9.09 | 996.56 | 269 | 80.67% |
| 212 | Bollinger + RSI | GBPUSD H1 | SELL | 2016-01-01 → 2026-09-08 | 7.20 | 1,045.65 | 3.45 | 327.43 | 262 | 92.75% |
| 492 | Bollinger + RSI | GBPUSD H1 | BUY | 2016-01-01 → 2026-09-14 | 2.52 | 991.70 | 6.68 | 771.16 | 415 | 88.67% |
| 787 | Bollinger: reentrada | GBPUSD H1 | SELL | 2016-01-01 → 2026-09-10 | 2.77 | 753.82 | 3.17 | 224.36 | 221 | 79.19% |
| 755 | Bollinger: reentrada | GBPUSD H1 | BUY | 2016-01-01 → 2026-09-10 | 2.38 | 1,103.55 | 7.75 | 844.95 | 232 | 78.45% |
| 878 | Ruptura Donchian | GBPUSD H1 | BUY | 2016-01-01 → 2026-09-10 | 2.56 | 1,047.12 | 2.05 | 217.73 | 337 | 68.25% |
| 840 | Ruptura Donchian | GBPUSD H1 | SELL | 2016-01-01 → 2026-09-10 | 2.35 | 1,218.63 | 6.95 | 787.95 | 240 | 72.50% |

## Fichas

### 1. XTIUSD ADX + Dirección BUY — ID 25

Busca entradas BUY cuando la fuerza ADX y la dirección de mercado coinciden. IS: 2016-01-01 → 2024-12-31, modelo 1; PF 7.78, neto USD 5,700.95 y 384 trades. OOS estaba desactivado. MAIN: ticks reales hasta 2026-09-07. **Estado: experimental, sin OOS operativo.**

### 2. XTIUSD Reversión VWAP BUY — ID 44

Busca reversión hacia VWAP después de una separación parametrizada mediante ATR. IS: 2016-01-01 → 2026-09-07, modelo 1; PF 5.76, neto USD 4,024.14 y 432 trades. OOS estaba desactivado. MAIN: ticks reales hasta 2026-09-08. **Estado: experimental, sin OOS operativo.**

### 3. GBPUSD Barrido de sesión SELL — ID 728

Busca una salida bajista después de un barrido del rango de sesión. IS: 2016-01-01 → 2026-09-07, modelo 1; PF 7.82, neto USD 685.98 y 210 trades. OOS estaba desactivado. MAIN: ticks reales hasta 2026-09-09. **Estado: experimental, sin OOS operativo.**

### 4. GBPUSD Barrido de sesión BUY — ID 754

Busca recuperación alcista después del barrido del rango. IS: 2016-01-01 → 2026-09-07, PF 2.17 y 269 trades. OOS activo: 2016-01-01 → 2026-09-10, modelo 4; PF 2.11, neto USD 981.53 y 269 trades. Los periodos se superponen. MAIN coincide con las métricas OOS.

### 5. GBPUSD Bollinger + RSI SELL — ID 212

Combina desviación de Bollinger con confirmación RSI para ventas. IS: 2016-01-01 → 2026-09-07, modelo 1; PF 7.40, neto USD 1,061.82 y 262 trades. OOS estaba desactivado. MAIN: ticks reales hasta 2026-09-08. **Estado: experimental, sin OOS operativo.**

### 6. GBPUSD Bollinger + RSI BUY — ID 492

Combina desviación de Bollinger con confirmación RSI para compras. IS: 2016-01-01 → 2026-09-07, modelo 1; PF 2.66, neto USD 1,053.36 y 420 trades. OOS estaba desactivado. MAIN: ticks reales hasta 2026-09-14. **Estado: experimental, sin OOS operativo.**

### 7. GBPUSD Bollinger Reentrada SELL — ID 787

Busca una reentrada bajista confirmada tras interacción con Bollinger. IS: 2016-01-01 → 2026-09-07; PF 3.14 y 214 trades. OOS: 2016-01-01 → 2026-09-10 con ticks reales; PF 2.77, neto USD 753.82 y 221 trades. Existe superposición IS/OOS.

### 8. GBPUSD Bollinger Reentrada BUY — ID 755

Busca una reentrada alcista confirmada. IS: 2016-01-01 → 2026-09-07; PF 2.58 y 229 trades. OOS: 2016-01-01 → 2026-09-10 con ticks reales; PF 2.38, neto USD 1,103.55 y 232 trades. Existe superposición IS/OOS.

### 9. GBPUSD Ruptura Donchian BUY — ID 878

Opera rupturas alcistas del canal Donchian. IS: 2016-01-01 → 2026-09-07; PF 2.38 y 338 trades. OOS: 2016-01-01 → 2026-09-10 con ticks reales; PF 2.56, neto USD 1,047.12 y 337 trades. Existe superposición IS/OOS.

### 10. GBPUSD Ruptura Donchian SELL — ID 840

Opera rupturas bajistas del canal Donchian. IS: 2016-01-01 → 2026-09-07; PF 2.51 y 239 trades. OOS: 2016-01-01 → 2026-09-10 con ticks reales; PF 2.35, neto USD 1,218.63 y 240 trades. Existe superposición IS/OOS.

## Alcance de la selección

La selección busca diversidad de señal, dirección y mercado, no únicamente el PF más alto. Todos deben recompilarse como DEMO ONLY, validar la carga de ONNX y superar una prueba final antes de crear su Release.
