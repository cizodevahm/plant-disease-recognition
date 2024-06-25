# Plant Disease Recognition System

![Home Page](home_page.jpeg)

## Introduction

Welcome to the Plant Disease Recognition System! 🌿🔍

Our mission is to help in identifying plant diseases efficiently. Upload an image of a plant, and our system will analyze it to detect any signs of diseases. Together, let's protect our crops and ensure a healthier harvest!

## Features

- **Upload Image:** Go to the **Disease Recognition** page and upload an image of a plant with suspected diseases.
- **Analysis:** Our system will process the image using advanced algorithms to identify potential diseases.
- **Results:** View the results and recommendations for further action.

## Why Choose Us?

- **Accuracy:** Our system utilizes state-of-the-art machine learning techniques for accurate disease detection.
- **User-Friendly:** Simple and intuitive interface for seamless user experience.
- **Fast and Efficient:** Receive results in seconds, allowing for quick decision-making.

## How to Use

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/cizodevahm/plant-disease-recognition.git
    cd plant-disease-recognition
    ```


2. **Download the Dataset:**
    Download the dataset from [Kaggle](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset) and place it in the appropriate directory.

3. **Run the Application:**
    ```bash
    streamlit run main.py
    ```

## Application Pages

### Home

The home page provides an overview of the system and its capabilities. 

### About

The about page gives detailed information about the dataset used in training the model and other project details.

### Disease Recognition

Upload an image of a plant leaf and let our model predict the disease.

## Model Information

The model is trained on a custom-built Keras model using a dataset of 87K images, categorized into 38 different classes. The dataset is divided into 80/20 ratio for training and validation, with a separate test set for predictions.

## Dataset

- **Train Set:** 70,295 images
- **Validation Set:** 17,572 images
- **Test Set:** 33 images

The dataset can be found [here](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the contributors of the original dataset.
- Special thanks to the developers of TensorFlow and Streamlit for providing such powerful tools for machine learning and web applications.


