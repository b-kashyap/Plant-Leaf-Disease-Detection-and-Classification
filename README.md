# Plant-Leaf-Disease-Detection-and-Classification
The project employs Convolutional Neural Networks (CNN) to revolutionize plant leaf disease detection, providing farmers a powerful tool for accurate identification and classification. This deep learning technology enhances crop management, minimizing yield losses.

![image](https://github.com/b-kashyap/Plant-Leaf-Disease-Detection-and-Classification/assets/155677382/b1bb67b0-efce-485d-ba1e-75034671c3e6)

## Technologies and Libraries used:

1. Programming Language - Python <br>
2. Tensorflow - Used for training and building Dee learning models <br>
3. Keras - High level neural network API <br>
4. OpenCV - Used for Image processing tasks <br>
5. matplotlib : Plotting library for creating visualizations <br>
6. seaborn : Data visualization library based on matplotlib, for statistical graphics <br>
7. NumPy - For scientific computing, handles large numerical data <br>
8. scikit-learn - Python library, providing an array of machine learning algorithms and utilities <br>

## Dataset:
The dataset is obtained from Kaggle - PlantVillage Dataset, which is organised into 3 distinct folders-Train,Test, and Validation. Each of these folders contains a total of 15 subfolders, corresponding to 15 unique classes of plant diseases.The distribution of images in each subset is visualized to understand the dataset's composition.

## Model Architecture:
The CNN model is designed with the following architecture: <br>
1. Input layer with a shape of (256, 256, 3) for color images. <br>
2. Convolutional layers with ReLU activation and max-pooling layers for feature extraction.<br>
3. Flattening layer to convert the output into a one-dimensional array.<br>
4. Dense layers with ReLU activation for classification.<br>
5. Output layer with softmax activation for multiclass classification (15 classes).<br>

## Training and Model Evaluation:
The model is trained using the training dataset with data augmentation techniques. The Adam optimizer, categorical crossentropy loss, and accuracy as the metric are used for compilation. The ModelCheckpoint callback is employed to save the weights of the model with the highest validation accuracy.<br>
The training process is visualized, and the best epoch is identified based on validation accuracy.<br>
The trained model is evaluated on the test dataset, and metrics such as test accuracy and test loss are reported. The best weights saved during training are loaded to ensure the evaluation is performed on the model with the highest validation accuracy.<br>

## Results:
The trained model achieves a high test accuracy of 97%, indicating its effectiveness in classifying plant leaf diseases. The test loss is also low (0.093), further confirming the model's performance.

## Future Scope:
1. Enhanced Feature Development: Expanding the project by incorporating additional features and functionalities based on evolving requirements and user feedback. <br>
2. Machine Learning Model Improvement: Iteratively refining and enhancing the machine learning models by incorporating new algorithms, optimizing parameters, and exploring advanced techniques to improve prediction accuracy.<br>
3. User Interface and Experience Upgrades: Enhancing the user interface and experience to make the project more intuitive, user-friendly, and visually appealing.<br>
4. Real-time Data Processing: Investigating the feasibility of real-time data processing capabilities, enabling the project to provide timely insights and adapt to dynamic data changes.<br>


