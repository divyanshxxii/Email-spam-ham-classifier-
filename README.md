# Email-spam-ham-classifier-

A simple machine learning project to classify emails or text messages as Spam or Ham (Not Spam).

This project demonstrates the use of Natural Language Processing (NLP) and machine learning techniques to build a binary text classification model. It is capable of distinguishing between spam and legitimate (ham) messages.
   You can use it to:
   Detect spam messages
   Understand basic NLP preprocessing
   Train and evaluate ML models for classification tasks

project structure:

spam-ham-classifier/
│
├── data/                   # Dataset directory
│   └── spam.csv            # CSV file containing labeled messages
│
├── notebooks/              # Jupyter Notebooks for EDA and modeling
│   └── spam_classifier.ipynb
│
├── models/                 # Saved models (optional)
│   └── spam_model.pkl
│
├── src/                    # Source code
│   ├── preprocess.py       # Text cleaning and preprocessing
│   ├── train.py            # Training script
│   └── predict.py          # Prediction script
│
├── requirements.txt        # Project dependencies
├── README.md               # You're here!
└── LICENSE
