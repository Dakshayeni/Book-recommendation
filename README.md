# Book-recommendation
Developed a book recommendation system using the K-Nearest Neighbors (KNN) algorithm

# **Book Recommendation System using KNN**
This project implements a **book recommendation system** using the **K-Nearest Neighbors (KNN) algorithm**. The system analyzes user ratings and book metadata to recommend similar books based on user preferences.

## **Project Overview**
### **Objective**
- Build a **collaborative filtering-based** book recommendation system.
- Use **K-Nearest Neighbors (KNN)** to find books similar to a given book.
- Provide personalized recommendations based on user ratings.

### **Dataset**
The project uses a dataset containing three main files:
1. **Books.csv** – Contains book metadata such as ISBN, title, and author.
2. **Ratings.csv** – Contains user ratings for books.
3. **Users.csv** – Contains user demographic details.

## **Implementation Steps**
### **1. Data Preprocessing**
- Read and clean **Books.csv**, **Ratings.csv**, and **Users.csv**.
- Handle missing values and filter out books with insufficient ratings.
- Convert categorical data (such as book titles) into numerical formats.

### **2. Building the Recommendation System**
- Convert the dataset into a **sparse matrix** using **Scipy's csr_matrix** for memory efficiency.
- Apply **K-Nearest Neighbors (KNN)** from **Scikit-Learn** to find similar books.
- Use a distance metric (**cosine similarity**) to measure book similarity.

### **3. Generating Book Recommendations**
- Select a book based on user input.
- Retrieve the top **n similar books** using the trained KNN model.
- Display recommendations with book details.

## **Technologies Used**
- **Python (Pandas, NumPy, Scipy)**
- **Machine Learning:** K-Nearest Neighbors (KNN)
- **Visualization:** Matplotlib, Seaborn
- **Jupyter Notebook**

## **How to Run the Project**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Book-recommendation.git
   cd Book-recommendation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Book-recommendation.ipynb
   ```

## **Future Enhancements**
- Implement **content-based filtering** using **TF-IDF**.
- Integrate **deep learning** for better recommendations.
- Deploy the model using **Streamlit or Flask** for a web-based interface.

## **Contributors**
- **Dakshayeni Bujunuru**

