# Text-Classification

This is a Streamlit web application that performs zero-shot text classification using the Facebook BART model fine-tuned on the MNLI dataset. Zero-shot classification allows the model to classify text into classes that it has never seen during training.

# Install Requirements

    !pip install requirements

# Running the App

    !streamlit run app.py & npx localtunnel --port 8501

# HOW TO USE

1. Enter the sentence you want to classify in the provided text area.

2. Enter the related words (candidate labels) in the sentence, separated by commas, in the provided text input.

3. Click the "Classify" button to trigger the classification.

The application will then perform zero-shot classification on the input sentence using the specified candidate labels and display the classification results.

# About Zero-Shot Text Classification

Zero-shot text classification is a technique that allows a model to classify text into classes it has never seen during training. In this application, we use the Facebook BART model fine-tuned on the MNLI dataset to perform zero-shot classification.

# contact

For any questions, suggestions, or issues related to this application, feel free to contact, Email : ceo@adople.com
