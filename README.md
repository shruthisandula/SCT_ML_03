# 🐾 Cat vs Dog Name Classifier

This project is a simple Machine Learning task to classify whether a given name belongs to a Cat or a Dog.

# 📂 Dataset

A CSV file (cat_dog_names.csv) containing:

name → the pet’s name (e.g., “Tommy”, “Kitty”)

label → either "cat" or "dog"

# ⚙️ Workflow

Load dataset (upload if not found in Colab).

Preprocess names using Bag-of-Words (CountVectorizer).

Train a Logistic Regression model.

Evaluate with accuracy on the test set.

Save trained model (cat_dog_name_model.pkl) and vectorizer (vectorizer.pkl).

Load model and predict for new names.

# 📊 Example Results

Accuracy: ~85–95% (depends on dataset size).

Example:

Input: "Tommy" → Predicted: Dog

Input: "Kitty" → Predicted: Cat

# 🚀 How to Run

Upload your cat_dog_names.csv when prompted in Google Colab.

Run the notebook to train the model.

Test with your own pet names!
