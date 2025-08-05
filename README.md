# Pneumonia Detection from Chest X-ray Images

This project focuses on the detection and classification of pneumonia from chest X-ray images using deep learning. The goal is to build and evaluate various Convolutional Neural Network (CNN) models to accurately distinguish between normal and pneumonia-infected lungs.


## ✨ Features

  * **Multiple CNN Models**: Implemented and trained several state-of-the-art CNN architectures, including **ResNet50**, **InceptionV3**, and **VGG16**.
  * **Transfer Learning**: Leveraged pre-trained models on the ImageNet dataset to improve feature extraction and achieve higher accuracy.
  * **Data Augmentation**: Applied various data augmentation techniques to increase the diversity of the training dataset and prevent overfitting.
  * **Performance Evaluation**: Assessed model performance using key metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.
  * **Visualization**: Generated confusion matrices and plots of training/validation accuracy and loss to visualize model performance.

## 🛠️ Technology Stack

  * **Language**: Python
  * **Libraries**:
      * TensorFlow
      * Keras
      * Scikit-learn
      * Pandas
      * NumPy
      * Matplotlib
      * Seaborn
      * OpenCV

## 🚀 Getting Started

To get this project up and running on your local machine, follow these steps.

### Prerequisites

  * Python 3.x
  * pip (Python package installer)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/pneumonia_detection.git
    cd pneumonia_detection
    ```
2.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You will need to create a `requirements.txt` file that lists all the project's dependencies.)*

### Usage

1.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook "Pneumonia_detection_from_Chest_X-ray_Images.ipynb"
    ```
2.  Follow the steps in the notebook to load the dataset, preprocess the images, train the models, and evaluate their performance.

## 🤝 Contributing

Contributions are welcome\! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.
