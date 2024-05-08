# maleria_cell_prediction

This Dataset is taken from the official NIH Website: https://ceb.nlm.nih.gov/repositories/malaria-datasets/

 Detecting Parasitized Cells using Convolutional Neural Networks

The project aimed to develop a deep learning model to classify cell images as either parasitized or uninfected. The dataset comprised 27,600 images of cells, with a balanced distribution between parasitized and uninfected classes.

The process began with data preprocessing, which involved resizing the images and standardizing pixel values to enhance model performance. A Convolutional Neural Network (CNN) architecture was chosen for its effectiveness in learning spatial hierarchies in image data.

The CNN model consisted of several convolutional layers followed by max-pooling layers for feature extraction. Dropout layers were included to prevent overfitting, and dense layers were employed for classification. The final layer utilized softmax activation to output class probabilities.

The dataset was split into training and testing sets, with a portion of the data reserved for validation to monitor model performance during training. The model was trained using the training set and evaluated on the test set to assess its generalization capability.

After training for multiple epochs, the model achieved satisfactory performance metrics, including accuracy, precision, recall, and F1-score. Visualization techniques such as confusion matrices and ROC curves were employed to analyze the model's performance and identify areas for improvement.

In conclusion, the developed CNN model demonstrated promising results in accurately distinguishing between parasitized and uninfected cells. Further refinement and optimization could potentially enhance its performance for real-world applications in the diagnosis of infectious diseases.
