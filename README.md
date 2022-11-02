# Hybrid-InceptionResNet-v2-Transfer-Learning

### Abstract

Lung cancer stands as the most common cancer in men and has 2<sup>nd</sup> rank in women worldwide. Detecting the type of cancer and running the appropriate treatments in the early stages play a pivotal role in the survival of patients. As obtaining a considerable number of lung cancer sample data is challenging and expensive due to privacy constraints, the majority of classifiers have encountered overfitting issues due to the difficulty of the small sample size. In this paper, we proposed a comparative hybrid convolutional deep transfer learning model, including VGG16, ResNet152V2, MobileNetV3 (small and large), InceptionResNetV2, and EfficientNetV2 to detect three widespread lung cancer types: Squamous Cell Carcinoma (SCC), Large Cell Carcinoma (LCC), and Adenocarcinoma. Furthermore, we developed and compared five architectures of the pre-trained convolutional deep learning model combined with Fully connected, Dropout, and Batch-Normalisation layers, and the hyper-parameters were adjusted. We used 1000 CT scans from the public dataset after proper pre-processing. The best-performed model was InceptionResNetV2 with transfer learning, and it achieved 91.1% accuracy, 84.9% precision, 95.8% AUC, and 81.5% F1-score to classify three different lung cancers from normal samples.

-------------

![architecture_resize4](https://user-images.githubusercontent.com/47991444/199283626-27164cf7-c685-48c2-82b7-5d53433f6ad2.png)

-------------

### Result
| Models  | Accuracy  | Precision | Recall | AUC | F-Score |
| :------------ |:---------------:| -----:| -----:| -----:| -----:|
| InceptionResNetV2-TL-1      | 0.8436 | 0.6878 | 0.6857 | 0.8496 | 0.6869 |
| InceptionResNetV2-TL-2      | 0.8642 | 0.7311 | 0.7228 | 0.8985 | 0.7270 |
| InceptionResNetV2-TL-3      | 0.8876 | 0.7902 | 0.7504 | 0.9385 | 0.7697 |
| InceptionResNetV2-TL-4      | 0.8475 | 0.7353 | 0.6114 | 0.9044 | 0.6667 |
| InceptionResNetV2-TL-5      | 0.7991 | 0.7638 | 0.2965 | 0.8558 | 0.4195 |



### Experimental Settings
* Python: 3.7.15
* TensorFlow: 2.9.2
* Keras: 2.9.0
* GPU: NVIDIA Tesla T4


```
Conference: 14th International Conference on Soft Computing and Pattern Recognition (SoCPaR 2022)
Paper title: Comparative Hybrid Deep Convolutional Learning Framework with Transfer Learning for Diagnosis of Lung Cancer
Proceedings: Proceedings will be published by Springer in the "Lecture Notes in Networks and Systems"
Year: 2022
```

###### This project has been carried out under my supervision from the Australian Centre for Precision Health, University of South Australia Cancer Research Institute, University of South Australia, Adelaide, SA, 5000, Australia.
