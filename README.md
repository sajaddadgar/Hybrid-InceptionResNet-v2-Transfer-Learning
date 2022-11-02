# Hybrid-InceptionResNet-v2-Transfer-Learning

### Abstract

Lung cancer stands as the most common cancer in men and has 2<sup>nd</sup> rank in women worldwide. Detecting the type of cancer and running the appropriate treatments in the early stages play a pivotal role in the survival of patients. As obtaining a considerable number of lung cancer sample data is challenging and expensive due to privacy constraints, the majority of classifiers have encountered overfitting issues due to the difficulty of the small sample size. In this paper, we proposed a comparative hybrid convolutional deep transfer learning model, including VGG16, ResNet152V2, MobileNetV3 (small and large), InceptionResNetV2, and EfficientNetV2 to detect three widespread lung cancer types: Squamous Cell Carcinoma (SCC), Large Cell Carcinoma (LCC), and Adenocarcinoma. Furthermore, we developed and compared five architectures of the pre-trained convolutional deep learning model combined with Fully connected, Dropout, and Batch-Normalisation layers, and the hyper-parameters were adjusted. We used 1000 CT scans from the public dataset after proper pre-processing. The best-performed model was InceptionResNetV2 with transfer learning, and it achieved 91.1% accuracy, 84.9% precision, 95.8% AUC, and 81.5% F1-score to classify three different lung cancers from normal samples.

![architecture_resize4](https://user-images.githubusercontent.com/47991444/199283626-27164cf7-c685-48c2-82b7-5d53433f6ad2.png)