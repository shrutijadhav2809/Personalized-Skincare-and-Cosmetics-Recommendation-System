🧴 Personalized Skincare and Cosmetics Recommendation System
📘 Project Overview

This project presents a Machine Learning–based recommendation system that provides personalized skincare and cosmetic product suggestions. It analyzes product ingredients and user skin profiles to deliver accurate, data-driven recommendations.

The system integrates TF-IDF Vectorization, Cosine Similarity, and a Random Forest Classifier to generate and validate recommendations — achieving an impressive 99.09% accuracy.

👩‍💻 Authors

Shruti Vasantrao Jadhav – shrutijadhav0928@gmail.com

🧠 Key Features

TF-IDF Vectorization: Converts unstructured product descriptions and ingredients into structured numerical features.

Cosine Similarity: Matches user profiles with products based on semantic similarity.

Random Forest Classifier: Validates and refines the final recommendations.

User Input Interface: Collects skin type, age, preferred product type, and budget.

Feedback System: Improves recommendations dynamically through user feedback.

🏗️ System Architecture
User Input  →  Data Preprocessing  →  TF-IDF Vectorization
     ↓                     ↓
 Recommendation Engine ← Cosine Similarity
     ↓
 Random Forest Classifier  →  Recommendation Output
     ↓
  Feedback & Model Update

⚙️ Technologies Used

Language: Python

Libraries:

pandas, numpy – Data preprocessing

scikit-learn – TF-IDF, Random Forest

nltk – Text cleaning and tokenization

matplotlib, seaborn – Data visualization

Dataset: 500+ skincare and cosmetic products with attributes like ingredients, price, and skin suitability

🧩 How It Works

Data Collection & Cleaning: Removes missing values, punctuation, and stopwords.

TF-IDF Feature Extraction: Converts text into numerical feature vectors.

User Profile Vectorization: Transforms user input into TF-IDF space.

Cosine Similarity Calculation: Finds the most relevant products for each user.

Random Forest Classification: Validates product suitability for each user.

Feedback Integration: Continuously improves recommendations.

🧾 Project Structure
📁 Personalized-Skincare-Recommendation/
│
├── data/
│   └── skincare_products.csv
│
├── notebooks/
│   └── skincare_recommendation.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── vectorization.py
│   ├── recommendation_engine.py
│   ├── classifier_model.py
│   └── feedback_module.py
│
├── results/
│   └── model_accuracy_report.png
│
├── requirements.txt
├── README.md
└── main.py

▶️ How to Run
# 1️⃣ Clone the repository
git clone https://github.com/<your-username>/Personalized-Skincare-Recommendation.git

# 2️⃣ Navigate to the project directory
cd Personalized-Skincare-Recommendation

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run the project
python main.py

📊 Results

Random Forest Classifier Accuracy: 99.09%

Outperformed baseline models like keyword matching and collaborative filtering.

Continuous learning through feedback-based retraining.

🚀 Future Enhancements

Integration of Deep Learning models (e.g., BERT, CNN) for semantic understanding.

Incorporation of image-based skincare analysis.

Deployment as a web application using Flask or Streamlit.

Use of cloud-based feedback data for real-time learning.
