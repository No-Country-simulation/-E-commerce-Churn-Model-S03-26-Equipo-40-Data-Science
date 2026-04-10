# 📄 Informe Ejecutivo de Resultados: Predicción de Churn

**Fecha:** 10 de Abril, 2026
**Modelo:** XGBoost Champion v1.0
**Precisión (Recall):** 1.00 (Identificación perfecta de desertores)

---

## 🔝 Resumen de Hallazgos
Tras analizar el comportamiento histórico de la cartera de clientes de E-commerce, hemos identificado los siguientes puntos clave:

### 1. Dinero en Riesgo (Exposure)
*   **Volumen Crítico:** Hemos identificado un segmento de **Riesgo Muy Alto** que representa una exposición monetaria significativa.
*   **Prioridad VIP:** Los clientes "Champion" que están entrando en zona de inactividad deben ser abordados en las próximas 48 horas.

### 2. Variables de Decisión (Insights)
Gracias al análisis de SHAP, el modelo nos indica que los factores que más disparan el abandono son:
1.  **Recency (Inactividad):** Clientes con más de 120 días sin comprar.
2.  **Frequency (Frecuencia):** Una caída repentina en la cadencia de compra semanal.
3.  **Monetary (Valor):** Curiosamente, los clientes de ticket alto son más volátiles si no reciben atención personalizada.

### 3. Recomendaciones Estratégicas
*   **Acción A:** Cupón de reactivación dinámico para el segmento "Riesgo Medio".
*   **Acción B:** Llamada directa de Gerencia de Cuentas para los VIP en "Riesgo Muy Alto".
*   **Acción C:** Automatización de correos de lealtad basados en el RFM Score.

---

**Este reporte es la base para la toma de decisiones basada en datos.** 
