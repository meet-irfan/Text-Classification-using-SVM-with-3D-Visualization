#  ♻ Text-Classification-using-SVM-with-3D-Visualization

This project demonstrates a **Machine Learning** approach for classifying emails into different categories using a **Support Vector Machine (SVM)** algorithm. The dataset used is `emails.csv`, which contains emails with associated labels. To preprocess the data, **TF-IDF** is applied to convert the text into numerical features. Additionally, the project showcases a **3D visualization** of the data and SVM classifier's predictions using **Principal Component Analysis (PCA)**.

# Features:<br>
-  Text Preprocessing  <br>
  - Converts email text into numerical features using <br> TF-IDF Vectorization. <br>
  - Handles stopwords and limits features for efficient processing. <br>
   
- # Support Vector Machine (SVM) <br>
  - Implements **SVM with a linear kernel** for classifying emails into distinct categories. <br>
  - Evaluates performance using **accuracy score** and **classification report**. <br>

- # 3D Visualization
  - Uses **PCA** to reduce high-dimensional TF-IDF features into 3 principal components. <br>
  - Visualizes the model’s predictions in a **3D scatter plot** with labeled categories. <br>

# Technologies Used: <br>
- **Python** <br>
- **Pandas**: For data manipulation and handling. <br>
- **scikit-learn**: For implementing SVM, PCA, and metrics evaluation. <br>
- **Matplotlib & Seaborn**: For 2D and 3D graphical representation of the data and model performance. <br>
   
### How to Run: <br>
1. Clone the repository. <br>
2. Upload the `emails.csv` dataset (or any other text dataset) in the appropriate format. <br>
3. Open the notebook in **Google Colab** or any Jupyter environment. <br>
4. Run the cells to train the model and visualize the results. <br>

# Visualization: <br>
- 2D **Confusion Matrix** to display the model’s performance. <br>
- 3D **PCA Scatter Plot** to visualize the SVM classifier's decision boundaries and predictions. <br>
