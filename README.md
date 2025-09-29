# 🫁 Bioingeniería: Detección de Enfermedades Pulmonares con Deep Learning  

Este proyecto aborda la **clasificación automática de sonidos respiratorios** mediante técnicas de **procesamiento de señales** y **modelos de Deep Learning**.  
El objetivo es contribuir al diagnóstico asistido de enfermedades pulmonares como **asma, EPOC, neumonía** y **respiración normal**.  

---

## 🚀 Descripción del Proyecto  
- Diseño de **pipelines ETL** para audios respiratorios: extracción, control de calidad, balanceo y normalización de señales.  
- Extracción de características acústicas con **coeficientes cepstrales en la escala Mel (MFCC)**, representando patrones bioacústicos relevantes.  
- Implementación y entrenamiento de **modelos de Deep Learning**:  
  - CNN  
  - CNN-LSTM  
  - CNN-BLSTM  
- Se alcanzarzó una exactitud de **~81% (80.83%) de exactitud**, mostrando el potencial de las redes neuronales en aplicaciones biomédicas.  

---

## 📊 Resultados Destacados  
- Accuracy > **80%** en todos los modelos.  
- Evaluación con **matrices de confusión, Exactitud, precisión, sencibilidad, F1, AUC, y curvas ROC**.  
- Generalización validada con **conjuntos de entrenamiento, validación y prueba**.  

---

## 🛠️ Tecnologías Utilizadas  
- **Lenguaje:** Python  
- **Librerías principales:** Keras, NumPy, Pandas, Matplotlib  
- **Procesamiento de audio:** MFCC (Mel-Frequency Cepstral Coefficients)  

---

## 📂 Estructura del Repositorio  
- `pulmonary_disease_detection.ipynb` → Notebook con pipeline y entrenamiento de uno de los modelos: CNN-LSTM.  
- `data/` → Carpeta sugerida para almacenar audios (no incluida en este repo por privacidad).  
- 

---

## 📌 Autor  
👨‍💻 Iván Tolaba  
Data Science & Deep Learning aplicado a señales biomédicas   

🔗 [LinkedIn](https://www.linkedin.com/in/iv%C3%A0n-tolaba-b161927b) | [Portfolio Web](https://ivantolaba.github.io/Portfolio-IA) | Email: ivn.tlb@gmail.com  
