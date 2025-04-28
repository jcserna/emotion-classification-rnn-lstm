# Análisis Comparativo de RNN vs LSTM para Clasificación de Emociones

Este proyecto tiene como objetivo implementar y comparar dos modelos de redes neuronales secuenciales — una Red Neuronal Recurrente tradicional (RNN) y una Red Neuronal con Memoria a Largo Plazo (LSTM) — en la tarea de clasificación de emociones a partir de frases escritas en inglés.

## Dataset

Se utilizó el dataset **Emotion** disponible en Hugging Face, que contiene frases etiquetadas en seis emociones principales: alegría, enojo, tristeza, miedo, amor y sorpresa.

## Metodología

- **Preprocesamiento:**  
  Tokenización de frases, construcción del vocabulario, codificación numérica y aplicación de padding dinámico.

- **Modelado:**  
  - Implementación de un modelo RNN tradicional.
  - Implementación de un modelo LSTM con dos capas ocultas.

- **Entrenamiento:**  
  - RNN entrenado durante 20 épocas.
  - LSTM entrenado durante 50 épocas.

- **Evaluación:**  
  - Accuracy.
  - F1-score.
  - Matriz de confusión.

## Resultados

- El modelo LSTM superó ampliamente al RNN en precisión y capacidad de generalización, alcanzando un **accuracy superior al 90%** y un **F1-score superior al 90%**.
- El modelo RNN mostró limitaciones severas en la diferenciación de clases emocionales.

## Visualizaciones

Se incluyen gráficas de la evolución de la pérdida y la precisión durante el entrenamiento, así como matrices de confusión para el análisis detallado de resultados.

## Conclusiones

El uso de arquitecturas avanzadas como LSTM se justifica plenamente en tareas de procesamiento de lenguaje natural que requieren la modelación de dependencias de largo plazo.

## Autor

- Juan Camilo Serna R.

## ¿Cómo ver este proyecto?

Puedes clonar este repositorio y abrir el archivo `.ipynb` directamente en Jupyter Notebook, VSCode o Google Colab.
