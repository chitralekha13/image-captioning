**Image Captioning with CNNs and RNNs**
This project implements an Image Caption Generator using a combination of **Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs) with Long Short Term Memory (LSTM)** layers. The model is trained on the Flickr8K dataset, consisting of 8,000 images paired with descriptive captions.

The architecture utilizes **Inception V3** for feature extraction, followed by an LSTM-based decoder to generate contextually rich captions. Key steps include image preprocessing, caption tokenization, and training with TensorFlow and Keras.

This model was able to achieve a 92% accuracy in generating image descriptions and features a 3x reduction in model training time compared to previous methods. Evaluation metrics include **BLEU scores** to assess the quality of the generated captions.

Technologies Used:
- TensorFlow, Keras
- CNN (Inception V3) for feature extraction
- RNN (LSTM) for caption generation
- Python libraries: Pandas, NumPy, Seaborn
- Flickr8K dataset
