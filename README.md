# Final Year Project: Predicting Charpy Impact Energy from Microstructure Data of A508 steel with Machine Learning
## Abstract
# My changes(Rajat) 
Limited non-destructive methods exist to accurately assess the material properties of A508 steel, a commonly used material in nuclear reactor pressure vessels. This study aims to develop a machine learning-based model for predicting Charpy impact energy from microstructural data of A508 steel, addressing the need for improved material characterization techniques. Previous research has primarily focused on characterizing or predicting material properties based on process parameters but overlooked the potential of leveraging microstructural data for material property prediction. 

The study compares various feature extraction techniques, such as Histogram of Oriented Gradients (HOG), and transfer learning with VGG16 and EfficientNetB0, to extract relevant features from microstructural images. These features were subsequently combined with machine learning prediction models such as fully connected neural networks (FCNN), random forest (RF) regression, and support vector regression (SVR), to predict Charpy impact energy.

The analysis of experimental results demonstrated the potential of integrating microstructural images and machine learning approaches in predicting Charpy impact energy. Particularly, the RF regressor combined with the EfficientNetB0 feature extractor exhibited the lowest mean absolute error (MAE) of 4.5 J, outperforming other model combinations. In comparison to a baseline prediction MAE of 12.1J obtained without utilizing microstructural data, these findings demonstrate a clear correlation between microstructural images and Charpy impact energy, emphasizing the potential for machine learning in material characterization.

The novel approach of harnessing microstructural data and machine learning techniques for predicting material properties offers a non-destructive, cost-effective, and efficient method of material property prediction, which could have significant implications for materials science.

**Keywords:** Charpy test, microstructure, A508 steel, machine learning, transfer learning, EfficientNetB0, VGG16, histogram of oriented gradients, support vector regression, random forest regression
