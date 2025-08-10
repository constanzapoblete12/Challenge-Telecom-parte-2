# Challenge-Telecom-parte-2

Análisis de la cancelación de los clientes y modelos predictivos
El propósito de este proyecto es identificar los factores claves que influyen en la cancelación del servicio por parte de los clientes y evaluar distintos modelos de machine learning para predecir estos casos.
A partir de los resultados, se proponen estrategias de retención que ayuden a reducir el churn y mejorar la experiencia del cliente.

Metodología
Datos tratados: Archivo limpio, variables transformadas y sin valores nulos.
Modelos aplicados: Árbol de Decisión, Random Forest y KNN.
Balanceo de clases: Undersampling para equilibrar la proporción de casos.
Métricas evaluadas: Accuracy, Precision, Recall y F1-score.
Evaluación: Conjunto de validación (30%) estratificado.

Comparación de los Resultados
| Modelo            | Accuracy | Precision | Recall | F1-score |
| ----------------- | -------- | --------- | ------ | -------- |
| **Random Forest** | 0.751    | 0.544     | 0.662  | 0.597    |
| KNN (normalizado) | 0.732    | 0.516     | 0.645  | 0.573    |
| Árbol de Decisión | 0.656    | 0.424     | 0.642  | 0.510    |

Variables Relevantes
| Variable              | Importancia (%) |
| --------------------- | --------------- |
| Duración en meses     | 18.5%           |
| Monto facturado total | 16.2%           |
| Uso promedio mensual  | 12.7%           |
| Edad del cliente      | 10.3%           |
| Reclamos últimos 6m   | 8.9%            |
| Descuentos aplicados  | 7.6%            |
| Días último contacto  | 5.1%            |

Conclusión Final
La cancelación de los clientes puede predecirse de forma confiable utilizando modelos como Random Forest. Este análisis permite a las empresas anticiparse y aplicar medidas preventivas que reduzcan el churn, optimizando así la experiencia y fidelización del cliente.
