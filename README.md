Trabajo práctico basado en procesamiento de lenguaje natural que consiste en realizar un análisis de sentimientos a un set de datos de críticas de cine en español. El objetivo de este mismo, es armar un modelo que aprenda a reconocer si una reseña de una critica de cine es positiva o negativa. Este trabajo se realizó utilizando multiples modelos ya que el objetivo del trabajo práctico era encontrar el mejor clasificador. Los modelos que se utilizaron son: 

1. Bayes Naive
2. Random Forest
3. XGBoost
4. Red Neuronal 
5. Ensamble de tipo Stacking 1 (Teniendo como modelos base a los ya entrenados que fueron Bayes Naive, XGBoost y red neuronal y el estimador final usado fue XGBClassifier)
6. Ensamble de tipo Stacking 2 (Teniendo como modelos base a los ya entrenados que fueron Bayes Naive, XGBoost y red neuronal y el estimador final usado fue LogisticRegression)
7. Ensamble de tipo Stacking 3 (Teniendo como modelos base a los ya entrenados que fueron Bayes Naive, XGBoost y red neuronal y el estimador final usado fue XGBClassifier)
8. Ensamble de tipo Stacking 4 (Teniendo como modelos base a los ya entrenados que fueron Bayes Naive, XGBoost y red neuronal y el estimador final usado fue RandomForestClassifier)
9. Ensamble de tipo Stacking 5 (Teniendo como modelos base a los ya entrenados que fueron Bayes Naive, XGBoost y red neuronal y el estimador final usado fue SVC)
10. Ensamble de tipo Stacking 6 (Teniendo como modelos base a los ya entrenados que fueron Bayes Naive, XGBoost y red neuronal y el estimador final usado fue MLPClassifier (Clasificador basado en Perceptrón Multicapa))

Al final, el mejor clasificador que nos dió, fue el ensamble Stacking 6.

Actualización: Proximamente haré una mejora e intentaré realizar una versión de este mismo trabajo práctico pero que esta vez, clasifique reseñas en inglés.
