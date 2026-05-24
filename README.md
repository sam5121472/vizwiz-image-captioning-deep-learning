# 🖼️ VizWiz Image Captioning Deep Learning Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Image%20Captioning-orange)
![Dataset](https://img.shields.io/badge/Dataset-VizWiz-green)
![Notebook](https://img.shields.io/badge/Jupyter-Notebook-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

This repository contains a complete deep learning project for **image captioning using the VizWiz dataset**.  
The project focuses on building an intelligent model that can generate meaningful captions for images, especially images captured by visually impaired users.

The work includes data loading, preprocessing, vocabulary creation, model development, training, evaluation, graphical outputs, and a final report/article-style paper.

---

## 🎯 Aim of the Project

The main aim of this project is to develop and evaluate an image captioning system that can automatically describe visual content in natural language.

Image captioning combines two important areas of artificial intelligence:

- **Computer Vision** — understanding image features
- **Natural Language Processing** — generating human-readable captions

The VizWiz dataset makes this task more realistic and challenging because many images are captured in real-world conditions, often with blur, poor lighting, unusual framing, or incomplete objects.

---

## 🧠 Key Features

✅ Data loading and exploration  
✅ Caption preprocessing and cleaning  
✅ Tokenization and vocabulary preparation  
✅ Deep learning model implementation  
✅ Phase 2 and Phase 3 model development  
✅ Training and evaluation outputs  
✅ Graphs and visual plots  
✅ Final report/article paper  
✅ GitHub-ready project structure  

---

## 📂 Repository Structure

```text
vizwiz-image-captioning-deep-learning/
│
├── Loading Data.ipynb
├── EfficientNet-B4 with Transformer Decoding versus EfficientNet-B4 with LSTM and Bahdanau Attention.ipynb
├── README.md
├── report/
│   └── VizWiz_Image_Captioning_Report_Sameer_Hassan_Khan.docx
│
├── outputs/
│   ├── training_graphs/
│   ├── evaluation_plots/
│   └── generated_captions/
│
└── dataset/
    └── VizWiz dataset files
```

> Note: The actual dataset may not be uploaded to GitHub if it is large. Add the dataset link or instructions for downloading it separately.

---

## 📊 Dataset Description

The project is based on the **VizWiz image captioning dataset**, which contains images taken by blind or visually impaired people along with corresponding captions.

Unlike standard image captioning datasets, VizWiz is more challenging because the images are often:

- blurry
- poorly lit
- partially visible
- taken from unusual angles
- difficult even for humans to interpret

This makes the dataset useful for developing assistive AI technologies.

---

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Jupyter Notebook | Development environment |
| TensorFlow / Keras | Deep learning model building |
| NumPy | Numerical operations |
| Pandas | Data handling |
| Matplotlib | Graphs and plots |
| Natural Language Processing | Caption preprocessing |
| Computer Vision | Image feature extraction |

---

## 🏗️ Methodology

The project follows a complete deep learning workflow.

### 1. Data Loading

The dataset was loaded and inspected using Jupyter Notebook. Image paths, captions, and annotation files were processed to prepare the data for training.

### 2. Data Preprocessing

The captions were cleaned and converted into a suitable format for model training.  
This included:

- removing unnecessary symbols
- converting text to lowercase
- tokenizing captions
- creating vocabulary
- preparing input-output caption sequences

### 3. Image Feature Extraction

Image features were extracted using deep learning techniques. These features help the model understand the visual information present in each image.

### 4. Model Development

The project includes model development in different phases.  
Phase 2 and Phase 3 focus on improving the captioning model by refining architecture, training process, and evaluation.

### 5. Training

The model was trained on the prepared image-caption pairs. During training, loss and performance trends were observed through plots and outputs.

### 6. Evaluation

The model outputs were evaluated using generated captions, training performance, and graphical analysis.

---

## 📈 Outputs and Visual Results

The project includes outputs such as:

- training loss graphs
- validation performance plots
- generated captions
- model comparison outputs
- preprocessing summaries
- evaluation results

These outputs help understand how well the model learned and where improvements are still needed.

---

## 🧪 Project Notebooks

### 📘 `Loading Data.ipynb`

This notebook contains the initial dataset loading and preparation steps.  
It includes data exploration, annotation loading, and basic preprocessing.

### 📗 `phase-2-and-3-faisal-shoaib.ipynb`

This notebook contains the major deep learning work for Phase 2 and Phase 3.  
It includes model implementation, training, evaluation, outputs, graphs, and improvements.

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/vizwiz-image-captioning-deep-learning.git
```

### Step 2: Open the Project Folder

```bash
cd vizwiz-image-captioning-deep-learning
```

### Step 3: Install Required Libraries

```bash
pip install numpy pandas matplotlib tensorflow keras pillow nltk
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```


---

##  Results Summary

The model demonstrates the ability to generate captions from images by learning relationships between visual features and text descriptions.

The results show that image captioning on the VizWiz dataset is challenging because many images are visually unclear. However, the project successfully demonstrates the full pipeline of an image captioning system, including preprocessing, training, evaluation, and result visualization.

---

##  Challenges Faced

Some major challenges in this project include:

- noisy and unclear images
- inconsistent caption quality
- large dataset handling
- vocabulary limitations
- model training time
- difficulty in generating highly accurate captions for complex images

---

##  Future Improvements

Future work can improve the project by:

- using stronger CNN feature extractors
- applying attention mechanisms
- using transformer-based captioning models
- increasing training epochs
- improving caption cleaning
- using BLEU, METEOR, ROUGE, or CIDEr evaluation metrics
- deploying the model as a web application

---

## 📄 Final Report

A complete report/article paper is included in the project.  
The report contains methodology, outputs, plots, graphs, discussion, evaluation, limitations, and conclusion.

**Publisher Name:** Sameer Hassan Khan

---

## 👨‍💻 Author / Contributor

**Project:** VizWiz Image Captioning Deep Learning Project  
**Publisher:** Sameer Hassan Khan  

---

##  Why This Project Is Important

This project is not only a technical deep learning task. It also has real social value.

Image captioning systems can support visually impaired people by helping them understand their surroundings through automatic image descriptions. The VizWiz dataset makes this project meaningful because it is connected to real accessibility challenges.

---

##  License

This project is created for educational and academic purposes.  
You may modify and improve it for learning, research, or portfolio use.

---

##  Acknowledgement

This project is based on the VizWiz image captioning task and demonstrates the application of deep learning in assistive artificial intelligence.


