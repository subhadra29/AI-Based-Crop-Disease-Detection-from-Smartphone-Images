Comprehensive Readme

Project Name
Plant Disease Recognition System**

An end-to-end Machine Learning and Computer Vision application designed to identify plant diseases from leaf imagery. Built using TensorFlow/Keras and Streamlit, the system allows users to upload images of plant leaves, processes them through a trained Convolutional Neural Network (CNN), and predicts which of 38 distinct plant and disease classes the sample belongs to.



Key Features
Interactive Dashboard:** Accessible user interface created with Streamlit, including dedicated pages for Home, About, and Disease Recognition.
High-Accuracy Neural Network:** Deep CNN model architecture trained for 10 epochs using Adam optimizer and categorical cross-entropy loss.
38 Disease & Health Classes:** Supports detection across multiple crops including Apple, Tomato, Potato, Corn, Grape, Peach, Pepper, Strawberry, and more.
Real-time Predictions: Rapid image preprocessing ($128 \times 128$ RGB) and inference directly through the web UI.
Training History Tracking: Exported metrics (`training_hist.json`) capturing loss and accuracy trends across training and validation splits.

---

 Repository Structure

├── app.py                  # Main Streamlit web interface application
├── train_model.ipynb       # Jupyter Notebook for data loading, CNN architecture, and training
├── trained_model.keras     # Saved TensorFlow/Keras model file (generated after training)
├── training_hist.json      # JSON file storing accuracy/loss metrics across epochs
├── home image.jpg          # Homepage background/banner image
└── README.md               # Project documentation
