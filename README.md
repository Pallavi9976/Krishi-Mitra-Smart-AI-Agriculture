🌾 Krishi Mitra – AI-Based Smart Agriculture Assistant

Krishi Mitra is an AI-based agriculture assistant project developed during the Short-Term Training in Artificial Intelligence and Data Science at CDAC Patna in June 2025. The project explores how Machine Learning and Deep Learning techniques can support farmers in making better agricultural decisions.

Agriculture depends on several important factors, including soil conditions, crop suitability, and market trends. Krishi Mitra focuses on using data-driven approaches to address these challenges through crop recommendation and soil image classification, with market price forecasting considered as a potential future enhancement.

The project includes model training code, dataset organization, and machine learning workflows for agricultural applications.



🌱 Project Overview

Krishi Mitra aims to explore the application of Artificial Intelligence in agriculture by developing models that work with agricultural data and soil images.

The project focuses on two main machine learning components:

1. Crop Recommendation Model: A Feedforward Neural Network (FNN) implemented using PyTorch to predict a suitable crop from the input features supported by the model.
2. Soil Image Classification Model: A Convolutional Neural Network (CNN) designed to classify soil types from images.

A third component, market price forecasting using LSTM, is considered a potential extension and should be treated as a future feature unless its implementation is completed and verified.


The overall goal is to demonstrate how AI techniques can contribute to smarter and more informed agricultural decision-making.

🎯 Problem Statement

Farmers face several challenges that can affect agricultural productivity and decision-making.

- Crop Selection: Choosing a suitable crop requires consideration of soil conditions and other agricultural factors.
- Soil Identification: Understanding soil characteristics is important when planning agricultural activities.
- Data-Driven Decisions: Access to useful data analysis can support more informed farming decisions.
- Market Price Awareness: Understanding price trends may help farmers plan when and where to sell their produce.

Traditional farming knowledge remains valuable, but data-driven tools can provide additional support.

Krishi Mitra explores AI-based approaches to crop recommendation and soil image classification, with the possibility of extending the system to agricultural market analysis.

🎯 Project Objectives

- To explore the use of Machine Learning and Deep Learning in agriculture.
- To develop a neural network-based crop recommendation model.
- To build a CNN-based approach for soil image classification.
- To organize agricultural datasets for model training and evaluation.
- To understand how AI can support agricultural decision-making.


🧠 Key Features

1. Crop Recommendation Model

The crop recommendation component uses a Feedforward Neural Network (FNN) implemented with PyTorch.

The model processes supported input features and predicts a crop category based on its training data.

Key points:

- Neural network-based classification.
- Uses tabular agricultural data.
- Designed to support crop selection.
- Prediction quality depends on the dataset, input features, and model training.

2. Soil Image Classification

The soil classification component uses a Convolutional Neural Network (CNN) to analyze soil images and classify them into the categories represented in its training dataset.

Key points:

- Image-based classification.
- Uses deep learning techniques for visual feature extraction.
- Supports experimentation with soil image datasets.
- Can explore soil identification when structured soil measurements are unavailable.

The model's output represents image-based classification; it should not be treated as a complete laboratory soil analysis.

🏗️ Model Architecture

Crop Recommendation — Feedforward Neural Network

The general workflow is:

1. Load and prepare the agricultural dataset.
2. Process the input features into the format required by the model.
3. Pass the processed features through the neural network.
4. Generate the model's predicted crop category.
5. Evaluate predictions using suitable classification metrics.

Technology: Python and PyTorch.

Soil Image Classification — Convolutional Neural Network

The general workflow is:

1. Load the soil image dataset.
2. Prepare and preprocess images according to the model's requirements.
3. Extract visual features using convolutional layers.
4. Generate class predictions through the classification layers.
5. Evaluate performance using suitable metrics.

Technology: Python and the deep learning framework actually used by the implementation.

🛠️ Technologies Used

Technology| Purpose
Python| Core programming language
PyTorch| Crop recommendation model
TensorFlow / Keras| Include if used by the soil classification implementation
NumPy| Numerical operations
Pandas| Tabular data processing
Matplotlib| Data visualization
CNN| Soil image classification approach
FNN| Crop recommendation approach


📂 Project Structure


Krishi-Mitra-Smart-AI-Agriculture/
│
├── Final_Code_Combined.ipynb
│   └── Combined soil classification
│       and crop recommendation workflow
│
├── project_crop_iimageipynb_cdac (1).py
│   └── Soil image classification code
│
├── project_cropipynb_cdac_py.ipynb
│   └── Crop recommendation model
│
└── README.md
    └── Project documentation




⚙️ Installation and Setup

Step 1: Clone the Repository

git clone https://github.com/Pallavi9976/Krishi-Mitra-Smart-AI-Agriculture.git

Step 2: Open the Project Directory

cd Krishi-Mitra-Smart-AI-Agriculture

Step 3: Install Dependencies

pip install -r requirements.txt

If installation fails, check the Python version and the package versions required by the project. Deep learning frameworks may require compatible versions.


🌍 Applications

Potential applications of the project's techniques include:

- Supporting crop selection through data-driven predictions.
- Exploring soil image classification using deep learning.
- Demonstrating the application of neural networks to agriculture.
- Helping students understand AI and ML workflows for agricultural problems.
- Providing a foundation for future agricultural decision-support systems.

The models are experimental decision-support tools and should not replace professional agricultural advice or laboratory soil testing.

🚀 Future Scope

The project can be extended in several directions:

- Market Price Forecasting: Implement and evaluate an LSTM-based forecasting model using historical market price data.
- Weather Integration: Integrate a weather API to explore how weather conditions can support agricultural decisions.
- Soil Nutrient Analysis: Extend the system with verified soil measurements such as pH and nutrient levels.
- Web Application: Build a user-friendly interface for entering agricultural data and viewing predictions.
- Model Evaluation: Add accuracy, precision, recall, F1-score, and suitable visualizations where applicable.
- Deployment: Explore deployment as a web-based agricultural decision-support application.
- Dataset Improvement: Test the models on diverse, representative datasets to assess generalization.



👩‍💻 Team Members

This project was developed collaboratively by:

- Pallavi Bharti
- Harshit Kashyap(Team Leader)
- Ayush Kumar
- Sonu Kumar

🙏 Acknowledgements

We sincerely acknowledge CDAC Patna (Centre for Development of Advanced Computing) for providing the opportunity to participate in the Short-Term Training in Artificial Intelligence and Data Science in June 2025.

We are grateful to our mentors, trainers, and team members for their guidance, collaboration, and support throughout the learning and project development process.

This project provided an opportunity to explore Python programming, machine learning, deep learning, and their potential applications in agriculture.

📄 License

Project: Krishi Mitra – AI-Based Smart Agriculture Assistant
Domain: Artificial Intelligence, Machine Learning, Deep Learning, and Agriculture
Developed during: Short-Term AI and Data Science Training, CDAC Patna, June 2025
