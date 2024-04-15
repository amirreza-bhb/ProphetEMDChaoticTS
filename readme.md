# ProphetEMD Chaotic TimeSeries Prediction
Authors : **Hossein Abbasimehr**, **Amirreza Behboodi**, **Aram Bahrini**

A novel hybrid model to forecast seasonal and chaotic time series,<br>
Expert Systems with Applications,<br>
Volume 239,
2024,
122461,
ISSN 0957-4174,<br>
https://doi.org/10.1016/j.eswa.2023.122461.<br>
(https://www.sciencedirect.com/science/article/pii/S0957417423029639)<br><br>

**Abstract**: Accurate time series forecasting is crucial, particularly in real-world application areas such as demand forecasting. The Prophet model successfully predicts time series containing well-known seasonal patterns but performs less effectively on time series exhibiting chaotic patterns. To overcome this, we propose a novel methodology that combines the empirical mode decomposition (EMD) technique and its noise-assisted variations with the Prophet model. One key property of this methodology is its ability to analyze the seasonality and chaos present in each time series and recommend a suitable forecasting method accordingly. The proposed methodology decomposes chaotic time series into multiple sub-series at various frequencies using EMD and its two noise-assisted extensions: Complete Ensemble Empirical Mode Decomposition with Adaptive Noise (CEEMDAN) and Improved CEEMDAN. Subsequently, models are fitted for each sub-series using the Prophet model, and the resulting forecasts are aggregated to generate a final prediction. We conducted an empirical study using seven time series datasets. Experimental results indicate that the proposed methodology generates accurate models that outperform benchmark methods when applied to time series with chaotic characteristics. Furthermore, the models obtained using our proposed methodology exhibit higher accuracy compared to the best models selected from the existing literature.
Keywords: Time series forecasting; EMD; CEEMDAN; Prophet; Seasonality; Chaos
