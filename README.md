# Week-1-Green-Skills-AI
To Develop a CNN Model To Classify Images Of Plastic Waste

This project focuses on developing a Convolutional Neural Network (CNN) to classify images of plastic waste into distinct categories, facilitating automated waste segregation. The model leverages labeled datasets of plastic waste to learn visual patterns and characteristics for accurate classification. Key steps include dataset collection, preprocessing, model design, training, and evaluation. The outcome aims to support recycling initiatives and environmental sustainability by streamlining plastic waste management through AI-driven solutions.

Dataset link (kaggle) : https://www.kaggle.com/datasets/techsash/waste-classification-data/data

Model : "plastic_waste_model" 

link (drive) : https://drive.google.com/file/d/1tKc2_6zUo-LB9A96bSfhimyE3cd02j6s/view?usp=sharing


Comments on Improvisations

1. Viewing Dataset Details:
The inclusion of steps to explore the dataset structure, such as listing classes and counting images in each class, is crucial for understanding the data distribution. This helps identify potential issues like class imbalance or missing data. Additionally, visualizing random images from the dataset provides an intuitive understanding of the data's characteristics, such as variations in lighting, size, or orientation, which is essential for designing a robust model. These steps lay the groundwork for effective preprocessing and model training.

2. Data Preprocessing:
Preprocessing the data is vital to standardize inputs and enhance the model's generalization ability. By incorporating normalization and augmentation techniques like rotation, flipping, and zooming, the model becomes more robust to real-world variations. This step ensures that the data is not only clean but also augmented to simulate diverse conditions, improving the model's ability to learn from limited samples while reducing overfitting.

3. Modifying the Model Architecture:
Building or modifying the CNN architecture ensures the model is tailored to the complexity and size of the dataset. The suggested architecture, with layers like convolution, max pooling, dropout, and dense layers, balances feature extraction and overfitting prevention. This modular and adjustable approach enables experimentation with different configurations, allowing for incremental improvements in performance. Additionally, summarizing the model provides a clear view of its structure, aiding in debugging and optimization.
