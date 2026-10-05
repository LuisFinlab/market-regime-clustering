# Market Regime Detection & Technical Analysis via Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TU_USUARIO/market-regime-clustering/blob/main/market-regime-clustering.ipynb)

Este proyecto aplica técnicas de aprendizaje no supervisado (**K-Means Clustering**) e indicadores técnicos para identificar y clasificar automáticamente los regímenes de mercado (*Alcista, Bajista, Consolidación*) en diferentes activos financieros (**NVDA, NKE, BRK-B**).

## 🚀 Resultados Clave

* **NVDA (NVIDIA):** Clara diferenciación entre regímenes de impulso alcista ($RSI > 60$, $MACD > 5$) y fases de consolidación.
* **NKE (NIKE):** Identificación de tendencias bajistas fuertes ($ADX > 30$, $RSI \approx 34$).
* **BRK-B (Berkshire Hathaway):** Detección precisa de fases de expansión y contracción de rango.

## 🛠️ Instalación y Uso Local

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/market-regime-clustering.git](https://github.com/TU_USUARIO/market-regime-clustering.git)
   cd market-regime-clustering