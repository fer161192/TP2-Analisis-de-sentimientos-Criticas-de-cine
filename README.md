# Análisis de Sentimientos en Críticas de Cine (Español)

## Objetivo
[1-2 líneas: clasificar reseñas como positivas/negativas usando NLP]

## Enfoque
Se entrenaron y compararon múltiples modelos, incluyendo ensambles (stacking) 
combinando los mejores clasificadores base.

## Modelos evaluados
- Bayes Naive, Random Forest, XGBoost, Red Neuronal
- 6 variantes de ensamble Stacking (distintos estimadores finales)

## Resultado
🏆 El mejor clasificador fue **Stacking 6** (estimador final: MLPClassifier), 
con [métrica clave, ej: accuracy/F1 de X%]

## Tecnologías
Python, Scikit-learn, XGBoost, [NLTK/spaCy si usaste], Pandas

## Informe completo
Ver [7506R_TP2_GRUPO27_CHP1_REPORTE.pdf](link) para el detalle metodológico completo.

## Cómo correrlo
[instrucciones básicas]


