# Procesamiento del Lenguaje Natural

Preguntas sobre preprocesamiento de texto, tokenización y representación numérica de lenguaje.

---

??? question "¿Conoces alguna técnica de preprocesamiento de texto?"

    Normalización de texto según el problema (eliminar *stopwords*, lematizar, *stemming*...) y **tokenización**.

??? question "¿Qué es un tokenizador?"

    Es un algoritmo que descompone un texto en las unidades que lo componen y les asigna un valor numérico a cada una de ellas (token ID).

??? question "¿Qué tipos de tokenizadores conoces?"

    - **Word tokenizer** — divide por palabras
    - **Character tokenizer** — divide por caracteres
    - **N-gram tokenizer** — genera secuencias de N unidades
    - **Byte Pair Encoding (BPE)** — divide por subpalabras, usado en LLMs modernos

??? question "¿Qué es un vectorizador de texto?"

    Consiste en convertir un texto tokenizado en una **representación numérica** para que pueda ser usado por un modelo de Machine Learning.

??? question "¿Cuáles son los problemas más comunes cuando trabajas con lenguaje natural?"

    Generalmente el **out-of-vocabulary**: pueden aparecer palabras nuevas, errores ortográficos, URLs, errores de encoding... Es importante saber gestionarlo.

??? question "¿Qué librerías conoces?"

    **spaCy** y **NLTK**.
