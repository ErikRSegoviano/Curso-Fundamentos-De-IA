# Curso: Fundamentos de Inteligencia Artificial

Este repositorio contiene todos los subproyectos y prácticas realizadas en el curso **"Fundamentos de Inteligencia Artificial"** de la plataforma [Playground Digital House](https://playground.digitalhouse.com/), como parte de la certificación **"IA en Programación"**.

## 📚 Descripción

El curso cubre conceptos fundamentales de Inteligencia Artificial, incluyendo:
- Algoritmos de clustering y clasificación no supervisados
- Deep Learning y redes neuronales
- Computer Vision y reconocimiento facial
- Procesamiento de lenguaje natural (NLP)
- Análisis de datos con machine learning

## 📁 Estructura del Repositorio

```
FundamentosIA/
├── Notebooks/                          # Jupyter Notebooks con prácticas
│   ├── mi_primer_notebook.ipynb
│   ├── practica_No_supervisado_nb.ipynb
│   ├── practica_deep_learning_nb.ipynb
│   ├── practica_computer_vision_face_recognition.ipynb
│   ├── practica_computer_vision_pretrained_model.ipynb
│   ├── nlp_clustering_clasificacion_texto.ipynb
│   └── test_jupiter_notebook.ipynb
│
├── DataSource/                         # Datasets utilizados
│   ├── Mall_Customers.csv
│   ├── Mall_Customers_KMeans.csv
│   └── WA_Fn-UseC_-TelcoCustomer-Churn.csv
│
├── ImageClassification/                # Proyectos de clasificación de imágenes
│   ├── Imagenes Clasificacion/
│   │   ├── AVE/
│   │   ├── PERRO/
│   │   └── Pez/
│   └── Testeo Clasificacion/
│
├── PreTrainedModels/                   # Modelos pre-entrenados
│   ├── converted_keras/
│   ├── converted_tflite/
│   └── converted_tflite_quantized/
│
├── Orange/                             # Workflows de Orange Data Mining
│   ├── Practica Algoritmos No Supervisados.ows
│   ├── Practica Image Clustering Etiquetadas.ows
│   ├── Practica Image Clustering No etiquetadas.ows
│   └── Practica Text Mining.ows
│
├── TextMiningResources/                # Recursos para procesamiento de texto
│   ├── stopwords.txt
│   └── Comentarios Aerolinea.xlsx
│
├── PDFs/                               # Documentación y referencias
├── img/                                # Imágenes del proyecto
└── .gitignore
```

## 🎓 Contenido Principal

### 1. **Algoritmos No Supervisados**
- Clustering (K-Means)
- Análisis de segmentación de clientes
- Workflows en Orange Data Mining

### 2. **Deep Learning**
- Redes neuronales convolucionales (CNN)
- Clasificación de imágenes
- Modelos pre-entrenados

### 3. **Computer Vision**
- Reconocimiento facial
- Clasificación de imágenes (Aves, Perros, Peces)
- Modelos en Keras y TensorFlow Lite

### 4. **Procesamiento de Lenguaje Natural (NLP)**
- Text Mining
- Clustering de textos
- Análisis de stopwords

## 🔗 Repositorios Relacionados

Este repositorio es parte de la certificación **"IA en Programación"** de Digital House. Complementa al curso:
- **[Curso: IA en Programación](https://github.com/ErikRSegoviano/Curso-IA-En-Programacion)** - Aplicaciones prácticas de IA en programación

## 🛠️ Herramientas Utilizadas

- **Python 3.x** - Lenguaje principal
- **Jupyter Notebook** - Desarrollo interactivo
- **TensorFlow/Keras** - Deep Learning
- **Orange Data Mining** - Análisis visual de datos
- **scikit-learn** - Machine Learning
- **pandas, numpy** - Manipulación de datos
- **OpenCV** - Visión por computadora

## 📊 Datasets

- **Mall Customers** - Segmentación de clientes de mall
- **Telco Customer Churn** - Predicción de churn de clientes
- **Imágenes Clasificadas** - Dataset personalizado de aves, perros y peces
- **Comentarios de Aerolíneas** - Para análisis de texto

## 🚀 Cómo Usar Este Repositorio

1. Clona el repositorio:
```bash
git clone https://github.com/ErikRSegoviano/Curso-Fundamentos-De-IA.git
cd Curso-Fundamentos-De-IA
```

2. Instala las dependencias (si usas Python):
```bash
pip install -r requirements.txt  # (si existe)
```

3. Abre los notebooks con Jupyter:
```bash
jupyter notebook
```

4. Explora los workflows en [Orange Data Mining](https://orange.readthedocs.io/)

## 📝 Notas

- Los notebooks contienen documentación detallada de cada ejercicio
- Los modelos pre-entrenados están en formatos `.h5` (Keras) y `.tflite` (TensorFlow Lite)
- Los workflows de Orange (.ows) pueden abrirse directamente en la aplicación Orange

## 👤 Autor

**Erik R. Segoviano**

## 📚 Plataforma

Curso realizado en [Playground Digital House](https://playground.digitalhouse.com/) - Certificación "IA en Programación"

## 📄 Licencia

Proyecto educativo - Libre para fines académicos

---

**Última actualización:** Febrero 2026
