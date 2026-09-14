# Metodología y lectura de resultados

## Etapas

- **IS:** etapa usada para búsqueda o ajuste de parámetros.
- **OOS:** segunda ejecución configurada por el workflow.
- **MAIN:** prueba de referencia guardada en el Banco de Estrategias.
- **Modelo 1:** OHLC de 1 minuto.
- **Modelo 4:** ticks reales disponibles en MetaTrader 5.

## Advertencia sobre el OOS actual

En cinco candidatos, el OOS está activo pero cubre 2016-01-01 a 2026-09-10, mientras el IS comienza en 2016 y termina cerca de esa misma fecha. Los periodos se superponen y, por ello, este OOS no es un holdout cronológico independiente.

En cinco candidatos, OOS estaba desactivado. Estos se identifican como **experimental · sin OOS operativo**.

## Métricas

- **Profit Factor:** beneficio bruto dividido entre pérdida bruta.
- **Drawdown:** retroceso máximo informado por la prueba.
- **Floating loss:** mayor pérdida flotante observada; no equivale al drawdown cerrado.
- **Win rate:** porcentaje de operaciones cerradas favorablemente.
- **Net profit:** resultado neto bajo la configuración probada.

No deben compararse beneficios monetarios sin considerar depósito inicial, lote, símbolo, divisa, bróker y costes. La selección para este repositorio exige estar fuera de portfolios, pero no implica aprobación para operar dinero real.
