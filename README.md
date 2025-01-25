# Speech Emotion Recognition

This repository contains code and resources for a [**Speech Emotion Recognition**](https://github.com/notEasyBeingAnushka/Speech-Emotion-Recognition-WiDS-2024) project. The goal is to classify emotions in speech data using machine learning techniques.

## Week 1: Python Basics
In **Week 1**, the focus was on foundational Python libraries:
- [**NumPy**](https://numpy.org/devdocs/user/index.html): Array manipulation for scientific computing.
- [**Librosa**](https://librosa.org/doc/latest/index.html): Music and audio analysis.
- [**Pandas**](https://pandas.pydata.org/docs/): Data manipulation using DataFrames.
- [**Matplotlib**](https://matplotlib.org/stable/index.html): Visualization and plotting.

## Week 2: Building models from scratch
In **Week 2**, we applied the libraries learned in Week 1 to build a **Logistic Regression Model** and a **Support Vector Machine** from scratch:
- [**Logistic Regression**](https://www.geeksforgeeks.org/implementation-of-logistic-regression-from-scratch-using-python/): Implementing logistic regression algorithm on the breast cancer dataset from **scikit-learn**.
- [**Support Vector Machine**](https://www.geeksforgeeks.org/support-vector-machine-algorithm/): Building a SVM, training it on custom data and plotting the results.

## Week 3: Neural Networks and Recurrent Neural Networks (RNN)
In **Week 3**, we advanced to building more complex models:
- **Building a Neural Network from Scratch**: Implementing a basic [feedforward neural network](https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/) to understand the underlying mechanics of deep learning.
- **Creating a Recurrent Neural Network (RNN)** using **TensorFlow**: Exploring RNNs, which are especially suited for sequential data, and building an [**RNN**](https://www.cse.iitb.ac.in/~swaprava/courses/cs217/scribes/CS217_2024_lec13.pdf) for time series forecasting.

## Week 4: Final Speech Emotion Recognition Model
In **Week 4**, we integrated everything to develop the final Speech Emotion Recognition model:
- **Audio Feature Extraction**: Using **Librosa** to extract key features from speech audio files, such as Mel-frequency cepstral coefficients ([**MFCCs**](https://www.sciencedirect.com/topics/computer-science/mel-frequency-cepstral-coefficient#:~:text=The%20Mel%2Dfrequency%20cepstral%20coefficients,characteristics%20of%20the%20human%20voice.)) and [**spectrograms**](https://en.wikipedia.org/wiki/Spectrogram#:~:text=A%20spectrogram%20is%20a%20visual,may%20be%20called%20waterfall%20displays.).
- **Voice Actor Dataset**: Leveraging [online voice actor datasets](https://zenodo.org/records/1188976#.XsAXemgzaUk), extracting relevant audio features for training.
- **Model Compilation and Testing**: Compiling and fine-tuning the model, training it using the extracted features, and performing testing to evaluate its performance in classifying emotions in speech.

## How to Use

1. **Clone the Repo**:
   ```bash
   git clone https://github.com/tejask-42/Speech-Emotion-Recognition-Project.git
2. **Run the Notebooks**:
   - Navigate to the appropriate week folder (e.g., `Week_1` or `Week_2`).
   - Open the `.ipynb` files using a Jupyter Notebook environment or Google Colab:
     - For Jupyter Notebook, run:
       ```bash
       jupyter notebook
       ```
     - Or, upload the notebook to [Google Colab](https://colab.research.google.com/).
