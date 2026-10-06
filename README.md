# IMDB Sentiment Analysis 🎬

This project implements a simple neural network model to perform sentiment analysis on IMDB movie reviews, classifying them as either `positive` or `negative`.

## 🛠 Tech Stack
* **Python**
* **Pandas** (Data manipulation and cleaning)
* **Scikit-learn** (`TfidfVectorizer` and data splitting)
* **TensorFlow / Keras** (Neural network model creation and training)
* **Google Colab**

## 📊 Project Pipeline
1. **Text Cleaning:** Removing extra whitespaces and formatting issues from the reviews.
2. **Train/Test Split:** Splitting the dataset into training (80%), validation (10%), and test (10%) sets.
3. **TF-IDF Vectorization:** Converting text data into numerical feature matrices (`max_features=1000`).
4. **Model Training:** Training a Keras Sequential model over 5 epochs.
5. **Evaluation:** Assessing the model on the test dataset (Achieved ~84% accuracy).

## 🚀 How to Run
1. Clone the repository or open it in Google Colab.
2. Ensure the required libraries are installed (`tensorflow`, `scikit-learn`, `pandas`, `tqdm`).
3. Run the cells step-by-step (`Shift + Enter`) to execute the pipeline.
