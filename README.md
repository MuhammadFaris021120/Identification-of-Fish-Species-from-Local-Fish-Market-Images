# **Identification of Fish Species from Local Fish Market Images**

Development of a fish identification system using machine learning. This project employs various deep learning algorithms with images captured from Malaysia's local fish markets, including image pre-processing.

## **Abstract**

In Malaysian local markets, fish identification can be challenging for unfamiliar consumers. Recent advancements in deep learning offer promising solutions in aquaculture. This research aims to develop a fish species identification system using images from local markets. Challenges include the lack of comprehensive datasets and the complexity of identifying fish under varying conditions. The dataset consists of 4500 images representing 15 different species. We trained and evaluated deep-learning algorithms including DenseNet121, VGG16, and MobileNetV2. DenseNet121 achieved the highest accuracy.

## **Problem Statement & Objectives**

### Problem Statement
- **Inaccuracies with Manual Identification**: Mistakes such as buying the wrong fish. Relying on human observation is time-consuming and error-prone.
- **Addressing Data Challenges**: Tackling varying imaging conditions, such as camera angles, contrast, and image quality.
- **Challenges with Distinct Characteristics**: Similarity in fish characteristics makes identification difficult.

### Objectives
1. To collect a database of local fish species from a local market.
2. To conduct a comparative study of selected machine learning algorithms for fish identification.
3. To evaluate the performance of these algorithms using a curated dataset.

## **Research Methodology**

The research methodology involved:
- Data collection from local markets.
- Image pre-processing and augmentation.
- Implementation of deep learning models.
- Evaluation of the model's performance.

![Research Methodology](https://github.com/user-attachments/assets/2b39c268-bf50-4e9f-a324-47e99f563802)

## **Implementation & Evaluation**

### Model Performance

Results for model performance of DenseNet121, VGG16, and MobileNetV2.

![Model Performance](https://github.com/user-attachments/assets/ac864301-2427-453e-a96d-c84337af5558)

### Training & Validation Graph (DenseNet121)

![Train and Validation Accuracy](https://github.com/user-attachments/assets/7a903e09-bed0-473a-a76c-4795c78348a4)

## **Conclusion**

This project successfully identified fish species from images obtained from local markets using three deep learning models: DenseNet121, VGG16, and MobileNetV2. After preprocessing and data augmentation, DenseNet121 achieved the highest accuracy of 99.78%, with a low test loss of 0.01%.

