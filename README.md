# Chest X-Ray Image Classification (DS 4002 Project 3)

## 📌 Project Overview

This project applies image classification using a pre-trained EfficientNetV2S model to distinguish between **normal** and **pneumonia** chest X-ray images. The dataset is split into training, validation, and test sets, and a transfer learning approach is used to improve performance with limited computational resources.
  
## 🎯 Goals

- Classify chest X-rays as either **normal** or **pneumonia**
- Fine-tune a pre-trained CNN to maximize performance
- Evaluate the model using precision, recall, accuracy, and F1-score

## 🛠️ Tool Stack
- Platform: Google Colab
- Libraries: tensorflow, keras, matplotlib, pandas, seaborn, numpy, sci-kit learn
  
## 🧠 Model

**EfficientNetV2S**
- Epochs: Set to 30, **stopped early at 21** using early stopping
- Fine-tuned base model (after initial training)

## 📊 Performance Summary (on Test Set

| Metric            | Value     |
|-------------------|-----------|
| Accuracy          | 93.9%   |
| Normal Recall     | 91.5%     |
| Pneumonia Recall  | 95.4%     |
| F1 Score (Avg)    | ~93.5%    |


```
DS4002_Project3/
├── DATA/                        
│
├── OUTPUT/                      
│   ├── classification_report.csv
│   ├── confusion_matrix.png
│   └── training_history_plot.png
│
├── SCRIPT/                      
│   └── DS4002_Project_3.ipynb
│
├── LICENSE.md                   
└── README.md                    
```

## 📦 How to Run 

1. Open the `SCRIPTS/DS4002_Project_3.ipynb` notebook in Google Colab.
2. Mount your Google Drive and upload the dataset.
3. Run all (analysis section) cells 
