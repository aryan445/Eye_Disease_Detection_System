# Eye_Disease_Detection_System
A machine learning project aimed at detecting common eye diseases, including glaucoma, diabetic retinopathy, and cataract, using image processing and a Convolutional Neural Network (CNN). The system leverages medical imaging to help in the early diagnosis of these diseases. Built with Python, TensorFlow, and OpenCV.

# Technologies Used
Python: Programming language.
TensorFlow/Keras: Deep learning framework used to build and train the CNN model.
OpenCV: For image preprocessing and real-time image capture.
Flask: Web framework for deploying the application.
Matplotlib/Seaborn: For data visualization and results plotting.

# Model Architecture
The model is based on a CNN architecture, consisting of the following layers:

Convolutional Layers: To extract features from the input images.
Pooling Layers: To downsample the feature maps.
Fully Connected Layers: For classification of eye diseases.
The model is trained using medical datasets of labeled eye images.

# Dataset
The dataset contains thousands of labeled images of eyes, classified into three categories: Glaucoma, Diabetic Retinopathy, and Cataract. These images have been preprocessed and augmented to improve the performance of the model.

You can download the dataset from sources like:

Kaggle

# Future Enhancements
Improve accuracy by using more advanced architectures (e.g., ResNet, EfficientNet).
Add more diseases for detection, such as Macular Degeneration.
Deploy the model on the cloud for better accessibility.
Integrate with mobile applications for real-time detection.
