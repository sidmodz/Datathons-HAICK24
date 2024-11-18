# HAICK-Image_Classification
<img src ='https://github.com/sidmodz/Datathons-HAICK24/blob/c8bdb91c9bf293d53318ce129d1ba82938aa1fc4/Arabic%20Sign%20Language%20Image%20Classification/sign_language.png'>
Sign language is crucial for communication between deaf and hearing individuals. Arabic Sign Language, which uses specific gestures corresponding to the Arabic alphabet, presents an intriguing problem for deep learning-based image classification.

The objective of this project is to develop a system capable of detecting and classifying Arabic Sign Language gestures accurately. Leveraging the state-of-the-art YOLOv8 classification model, this system has been fine-tuned on a dataset of Arabic sign language images, with each image representing a specific letter of the Arabic alphabet.

# Methodology

1. **Data preprocessing:**
The dataset was carefully prepared and formatted to align with the requirements of the YOLOv8 classification model.

2. **Transfer learning with YOLOv8:**
YOLOv8 offers a range of models catering to various computational needs, the nano, medium, and extra-large versions were used. Here’s an outline of the process:
- Pretrained Weights: Each model was initialized with pretrained weights from the COCO dataset, which contains over 1.2 million images and 80 classes, providing a robust starting point for our fine-tuning task.
- Hyperparameter Tuning: Models were tested with varying batch sizes to optimize training efficiency and performance.

3. **Performance evaluation:**
After training, the models were evaluated on a validation set to measure their accuracy and loss.

4. **Inference:**
The best-performing model was selected based on its validation performance, and its corresponding weights were used to conduct inference on the test set.

