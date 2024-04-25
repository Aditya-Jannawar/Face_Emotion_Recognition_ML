Facial Emotion Recognition
This project aims to recognize facial emotions using deep learning techniques. It utilizes convolutional neural networks (CNNs) implemented with Keras and TensorFlow to classify emotions such as anger, disgust, fear, happiness, neutral, sadness, and surprise.

Overview
The project consists of the following components:
Data Collection: The dataset comprises images of facial expressions, categorized into different emotion labels.
Data Preprocessing: Images are loaded, converted to grayscale, and resized to a standard size. The pixel values are normalized to improve model training.
Model Training: A CNN model is constructed using Keras, consisting of convolutional layers followed by max-pooling and dropout layers to prevent overfitting. The model is trained on the preprocessed image data.
Model Evaluation: The trained model's performance is evaluated on a separate test dataset to assess its accuracy in predicting emotions.
Inference: The trained model is then used to predict emotions in new images. Sample images are provided for inference, along with their predicted emotion labels.

Dependencies
Python 3.x
TensorFlow 2.x
Keras
NumPy
Pandas
Matplotlib
tqdm
Usage

Data Preparation: Ensure that your dataset is organized with images categorized into folders corresponding to different emotion labels.
Training: Run the provided script to train the model using the prepared dataset.
Evaluation: Evaluate the trained model's performance on a separate test dataset to assess its accuracy.
Inference: Use the trained model to predict emotions in new images. Sample code is provided for inference, along with pre-trained weights.

Sample Predictions
Original Image: ![Sad Emotion 1](D:/New folder (2)/face emotion recognition prj/images/test/sad/231.jpg)
Predicted Emotion: Sad
Original Image: ![Sad Emotion 2](D:/New folder (2)/face emotion recognition prj/images/test/sad/987.jpg)
Predicted Emotion: Sad
Original Image: ![Disgust Emotion](D:/New folder (2)/face emotion recognition prj/images/test/disgust/1115.jpg)
Predicted Emotion: Disgust
Original Image: ![Happy Emotion](D:/New folder (2)/face emotion recognition prj/images/test/happy/213.jpg)
Predicted Emotion: Happy
Original Image: ![Surprise Emotion](D:/New folder (2)/face emotion recognition prj/images/test/surprise/675.jpg)
Predicted Emotion: Surprise
