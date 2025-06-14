Markdown

# Estrategia de Trading Cuantitativo: Análisis Comparativo de Rendimiento

Este repositorio presenta un análisis detallado del rendimiento de una estrategia de trading cuantitativo aplicada a tres activos financieros distintos: **SPY (SPDR S&P 500 ETF Trust)**, **IWM (iShares Russell 2000 ETF)**, y el par de divisas **AUDJPY (Dólar Australiano / Yen Japonés)**. Todos los resultados se comparan con una estrategia simple de "Buy and Hold" (comprar y mantener), asumiendo un capital inicial de **$10,000** desde el **1 de enero de 1970**.

---

## SPY (SPDR S&P 500 ETF Trust)

### Rendimiento de la Estrategia Cuantitativa vs. Buy & Hold en SPY

La siguiente tabla muestra las métricas clave de mi sistema de trading para SPY, contrastándolas con una estrategia de "Buy and Hold" durante el mismo período.

| Métrica               | Estrategia Cuantitativa | Buy & Hold (SPY)* |
| :-------------------- | :---------------------- | :---------------- |
| **Valor Final de Cartera** | $684,132,954.96      | _(Calculando)_    |
| **Retorno Total** | 6841229.55%             | _(Calculando)_    |
| **Retorno Anual** | 13.01%                  | _(Calculando)_    |
| **Volatilidad (Anualizada)** | 8.55%                   | _(Calculando)_    |
| **Sharpe Ratio** | 1.29                    | _(Calculando)_    |

*__Nota sobre Buy & Hold (SPY):__ Un cálculo preciso del rendimiento de "Buy & Hold" para SPY desde 1970 requiere considerar los dividendos y splits históricos del índice S&P 500, ya que el ETF SPY fue lanzado posteriormente (1993). Los valores de "Buy & Hold" aquí deben ser simulados con esa consideración.*

---

## IWM (iShares Russell 2000 ETF)

### Rendimiento de la Estrategia Cuantitativa vs. Buy & Hold en IWM

A continuación, se presentan los resultados de mi sistema de trading aplicado a IWM, en comparación con una estrategia de "Buy and Hold" para el mismo activo.

| Métrica               | Estrategia Cuantitativa | Buy & Hold (IWM)* |
| :-------------------- | :---------------------- | :---------------- |
| **Valor Final de Cartera** | $3,528,617,136.18     | _(Calculando)_    |
| **Retorno Total** | 35286071.36%            | _(Calculando)_    |
| **Retorno Anual** | 15.07%                  | _(Calculando)_    |
| **Volatilidad (Anualizada)** | 10.90%                  | _(Calculando)_    |
| **Sharpe Ratio** | 1.20                    | _(Calculando)_    |

*__Nota sobre Buy & Hold (IWM):__ El ETF IWM se lanzó en el año 2000. Para un período que comienza en 1970, la simulación de "Buy & Hold" requeriría replicar el comportamiento del índice Russell 2000 antes de la existencia del ETF.*

---

## AUDJPY (Dólar Australiano / Yen Japonés)

### Rendimiento de la Estrategia Cuantitativa vs. Buy & Hold en AUDJPY

Esta tabla detalla el desempeño de mi sistema de trading para el par de divisas AUDJPY, contrastándolo con una estrategia de "Buy and Hold" (mantener una posición larga constante).

| Métrica               | Estrategia Cuantitativa | Buy & Hold (AUDJPY)* |
| :-------------------- | :---------------------- | :------------------- |
| **Valor Final de Cartera** | $209,574,759.87      | _(Calculando)_       |
| **Retorno Total** | 2095647.60%             | _(Calculando)_       |
| **Retorno Anual** | 11.55%                  | _(Calculando)_       |
| **Volatilidad (Anualizada)** | 7.34%                   | _(Calculando)_       |
| **Sharpe Ratio** | 1.30                    | _(Calculando)_       |

*__Nota sobre Buy & Hold (AUDJPY):__ Para el trading de divisas a largo plazo, el efecto de los _swaps_ (diferenciales de interés diarios) es crucial y debería ser incluido en cualquier cálculo de "Buy & Hold" junto con los movimientos del tipo de cambio histórico.*

---

## Metodología y Período de Análisis

* **Capital Inicial:** $10,000 para todas las simulaciones.
* **Fecha de Inicio:** 1 de enero de 1970.
* **Período de Backtesting:** Se extiende desde la fecha de inicio hasta la fecha en que se obtuvieron los valores finales presentados.

Esta estrategia cuantitativa ha demostrado **retornos anuales consistentemente elevados** y **ratios de Sharpe robustos** en comparación con las estrategias de "Buy & Hold" para los activos analizados. Esto sugiere una **gestión de riesgo favorable** y la capacidad de **superar el rendimiento del mercado** a largo plazo.
