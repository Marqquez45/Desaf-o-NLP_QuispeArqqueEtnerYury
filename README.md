# 📊 Estudio Exploratorio de Modelos para Clasificación de Emociones en Tweets

## 📅 Fecha de entrega
Hoy

## 👋 Introducción
Este proyecto consiste en realizar un **estudio exploratorio** de 3 modelos aplicados a la tarea de **clasificación de emociones** utilizando el dataset [EmoEvent](https://github.com/fmplaza/EmoEvent/tree/master/splits).  

El dataset contiene **8409 tweets** anotados en una de las siguientes categorías de emoción:  
- 😡 Anger  
- 😢 Sadness  
- 😃 Joy  
- 🤢 Disgust  
- 😱 Fear  
- 😲 Surprise  
- 🗯️ Offensive  
- ❓ Other  

Además, los tweets están relacionados con **eventos específicos** encontrados en Twitter.

---

## 🎯 Objetivos
1. Explorar y entrenar **3 modelos diferentes**:
   - Modelos propios (ej. RNN, Seq2Seq).  
   - Fine-tuning de modelos preentrenados (ej. BERT, T5).  
   - Uso de modelos listos (ej. GPT-4o).  

2. Reportar los resultados por **emoción (categoría)** y también realizar:  
   - Análisis por evento.  
   - Matriz de confusión.  
   - Otros análisis pertinentes.  

3. Publicar lo desarrollado en un **notebook en GitHub** (este repositorio).  

4. Documentar cada paso de forma clara y detallada en el notebook.  

---

## 🛠️ Requerimientos
- Python 3.x  
- Jupyter Notebook  
- Librerías principales:  
  - `pandas`, `numpy`  
  - `matplotlib`, `seaborn`  
  - `scikit-learn`  
  - `torch` o `tensorflow` (dependiendo de los modelos)  
  - `transformers` (para fine-tuning de BERT/T5)  
