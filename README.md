# Tarea TF-IDF — Vectorización del Lenguaje Natural

**Kevin Chaparro**  
Estadística — Universidad Santo Tomás  
Machine Learning con PySpark y Docker · Semestre 2026-I

## Descripción

Este notebook corresponde a la tarea del tercer corte sobre TF-IDF (Term Frequency - Inverse Document Frequency). Se trabajo con un corpus de 600 noticias en español divididas en tres categorías: deportes, economía y tecnología.

El objetivo fue aplicar el flujo completo de vectorización de texto usando PySpark: desde la tokenización y eliminación de stop words, hasta el cálculo de TF-IDF con `CountVectorizer` e `IDF`, para entender cómo esta técnica identifica las palabras más relevantes de cada documento y categoría.

## ¿Qué aprendí?

- Que los modelos de ML no reciben texto directamente, necesitan representaciones numéricas.
- Que contar palabras (TF crudo) no es suficiente porque las palabras más frecuentes suelen ser las más genéricas.
- Que TF-IDF resuelve esto combinando la frecuencia local de una palabra con qué tan rara es en el corpus, premiando así las palabras realmente discriminantes.
- También noté cómo el `RegexTokenizer` de PySpark tiene limitaciones con el español, ya que fragmenta las palabras acentuadas, generando ruido en el análisis.

## Archivos

- `TareaTFIDF_Kevin_Chaparro.ipynb` — Notebook con el desarrollo completo y las 10 respuestas conceptuales.
