# Abnormal-Mental-Health-Detector

The primary objective of this research is to develop an advanced machine learning architecture that facilitates the early detection of abnormal mental health conditions by integrating audio and visual cues through a teacher-student model framework. 

##1. Teacher Model (Emotion Mapping from Image/Video Data): Input: Facial images or video frames.
Architecture: Use a deep convolutional neural network (CNN) or a combination of CNN and recurrent layers to extract features from the visual data. This model learns to map facial expressions to emotional states.
Output: Emotion probabilities or embeddings numerical mapping to different emotional categories (e.g., happy, sad, neutral, etc.).
##2. Student Model (Emotion Mapping from Speech Data): Input: Audio samples (speech data).
Architecture: Employ a recurrent neural network (RNN) or a combination of CNN and recurrent layers to process the audio data. This model learns to map speech patterns to emotional states.
Output: Emotion probabilities or embeddings numerical mapping to different emotional categories (e.g., happy, sad, neutral, etc.).
##3. Abnormal Behaviour Detection: During inference, compare the emotional predictions made by the student model using speech data with those made by the teacher model using image or video data.
Detection: If the emotional predictions from audio and visual modalities significantly differ (beyond a predefined threshold), it could indicate abnormal behaviour or abnormal mental health condition.
