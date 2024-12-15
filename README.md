The "Emotion AI" project involved the development of two deep learning models that work together to predict human emotions based on facial expressions. The project was designed with the following key components:

Key Facial Points Detection:

This model focused on identifying key facial landmarks such as the eyes, eyebrows, nose, mouth, and chin. The task was to detect specific points on the face that are indicative of various emotional expressions.
The model was built using Convolutional Neural Networks (CNNs) and Residual Networks (RESNET). The RESNET architecture, with its residual blocks, helped improve the model's accuracy by enabling it to learn deeper representations without the risk of overfitting.

Facial Expression Detection (Emotion Classification):

This model classified facial expressions into distinct emotional categories such as happiness, sadness, anger, surprise, and others. The classification was achieved using a CNN-based approach with softmax activation to output probabilities for each emotion label.
The model was trained on a labeled dataset of facial images, where each image was tagged with the corresponding emotion.

Combined Prediction:

The two models were integrated to make a combined emotion prediction. First, the Key Facial Points Detection model identified key landmarks, and then the Facial Expression model classified the emotion based on the detected facial features.
This combination enabled the AI to accurately recognize and interpret emotions from facial expressions, with the key points serving as crucial input for the emotion classification task.
Overall, the project aimed to build a robust system that could understand human emotions through facial cues, which can be applied in various fields such as human-computer interaction, healthcare, security, and customer service.
