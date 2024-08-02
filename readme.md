# Emotion Detection using Machine Learning

- My project focuses on developing an emotion detection model capable of recognizing seven distinct emotions: **anger, happy, sad, surprise, disgust, shock, and neutral**. 
- The process involves dataset preprocessing, data splitting, model initialization using TensorFlow and Keras, model training, model accuracy, model accuracy and loss graph, and model saving.
- The project aims to provide a comprehensive understanding of emotions through a machine learning model, with the training progress visualized using loss graphs.

### Dataset Preprocessing
- The initial step involves preprocessing datasets specific to each emotion, including cleaning, normalization, and feature extraction to ensure a consistent and meaningful representation of emotional cues in the data.

### Model Initialization and Training
- TensorFlow and Keras frameworks are employed to construct a neural network tailored for emotion detection.
- The model architecture is designed to accommodate the nuances of different emotions.
- Training involves feeding the preprocessed datasets into the model and iteratively optimizing its parameters to achieve accurate emotion classification.

### Training Progress Visualization
- Training and validation loss graphs are generated to visually assess the model's performance, offering insights into the convergence and generalization of the model, aiding in fine-tuning and optimization.

## Libraries used:
- Tensorflow.
- Keras.
- Joblib.
- Preprocessing.
- numpy.
- CV2.
- Image.
- Pytorch.

# Flow of Execution:

### Preprocessing Images:
- Preprocessed individual emotion images for enhanced model performance, including normalization, resizing, and feature extraction.

  <img src="https://github.com/NikhilTeja21/Emotion_Detection/assets/88529671/3127076e-59ee-487f-a796-8eebdaffe826" width=600 height=350>

### Dataset Splitting:
- Split the dataset into training and validation sets to facilitate model training and evaluation.

### Model Initialization:
- Initialized a sequential model using TensorFlow and Keras to effectively capture the intricacies of emotion detection.

### Model Training with 139 Epochs:
- Trained the model for 139 epochs to strike a balance between achieving convergence and preventing overfitting, based on iterative experimentation and observing the trade-off between training time and model accuracy.

### Accuracy:
- Achieved an accuracy of 86% during model evaluation, demonstrating the model's proficiency in accurately classifying emotions.

### Graphs Printing:
- Displaying visual representation of the model's accuracy and loss during the validation process, providing insights into its performance and convergence.

  #### Model accuracy graph:
  <img src="https://github.com/NikhilTeja21/Emotion_Detection/assets/88529671/6144246c-70f2-414b-a6cc-17b2c5b6aa02" width="600" height="350">
  
  #### Model loss graph:
  <img src="https://github.com/NikhilTeja21/Emotion_Detection/assets/88529671/58d4f4eb-25bc-4c75-ada3-5e6ee9616259" width="600" height="350">

### Model Dumping:
- Saved the trained model in a joblib file for future use or to improve the performance of my emotion classifier model, ensuring ease of deployment and integration into applications requiring emotion detection capabilities.
