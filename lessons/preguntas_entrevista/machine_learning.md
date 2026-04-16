# Machine Learning

Preguntas sobre conceptos fundamentales de Machine Learning: definiciones, tipos de aprendizaje, evaluación de datos y métricas.

---

??? question "¿Qué es la Inteligencia Artificial?"

    Es el área de las ciencias de la computación que se centra en implementar procesos que permitan a las máquinas razonar.

??? question "¿Qué es el Machine Learning?"

    Es el área de la inteligencia artificial que permite a las máquinas "aprender" a razonar a partir de datos.

??? question "¿Qué tipos de Machine Learning conoces?"

    En cuanto al tipo de aprendizaje: **Supervisado** y **No Supervisado**. Dentro de Supervisado: Clasificación y Regresión.

??? question "¿Cómo sabes si unos datos son buenos para entrenar un modelo?"

    Primero, mirando los datos manualmente y entendiendo su significado. Segundo, haciendo un análisis exploratorio que, por medio de estadística y visualización, permita ver su comportamiento en términos de dato.

??? question "¿Cómo haces un análisis exploratorio?"

    Primero viendo el comportamiento de cada variable (**análisis univariable**) para ver si se comportan correctamente. Segundo viendo el comportamiento entre variables (**análisis multivariable**) para ver la dependencia entre ellas. Ambos con estadísticas y visualizaciones.

??? question "¿Cómo evalúas si un modelo es bueno o no?"

    Con las métricas. Para modelos de **regresión** se suelen usar métricas como Root Mean Square Error (RMSE). Para **clasificación**, Accuracy, Precision, Recall y F1-score.

??? question "¿Cuál es la diferencia entre Precision y Recall?"

    - Para problemas donde fallar un positivo es muy grave (decir a un enfermo de cáncer que no tiene cáncer) es más importante el **Precision**.
    - Para problemas donde fallar un negativo es más grave (perder a un cliente que sí se iba a ir) es mejor el **Recall**.

??? question "¿Qué librerías conoces?"

    **Scikit-Learn** para modelos de ML y **Pandas** para manipulación de datos.
