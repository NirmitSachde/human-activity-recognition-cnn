### Human Action Recognition Project

**Description:**
This project focuses on human action recognition using a Convolutional Neural Network (CNN) model trained on the Kinetics dataset. The model uses a pre-trained ResNet-34 architecture for feature extraction and classification of human activities from video frames.

**Key Features:**
- **Model Architecture:** Utilizes a CNN with convolutional layers, max pooling, and dense layers, with a total of 3,305,414 trainable parameters.
- **Training:** Trained for 20 epochs with a batch size of 32, achieving a test accuracy of 56.55%.
- **Data Processing:** Images are resized to 128x128 pixels, normalized, and processed into batches for efficient training.
- **Usage:** The notebook includes code for loading data, preprocessing, model definition, training, evaluation, and prediction on new images.

**Setup:**
1. **Environment:** Ensure you have Python 3.x installed with TensorFlow, Keras, Pandas, and Matplotlib.
2. **Data:** Download the Kinetics dataset or use a similar dataset for human action recognition.
3. **Execution:** Run the notebook in a Jupyter environment or Google Colab with GPU support for faster training.

**How to Use:**
- Load the dataset and preprocess images as described in the notebook.
- Train the model using the provided code, adjusting hyperparameters if necessary.
- Evaluate the model's performance on a test set.
- Use the trained model to predict actions from new images or video frames.

**Contributing:**
- Contributions to improve model accuracy, add new datasets, or enhance visualization are welcome. Please fork the repository and submit pull requests.

**License:**
- This project is licensed under the MIT License.

