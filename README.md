# iris-internship-task-
# 🌸 Iris Dataset Classification using KNN and Decision Tree

This project demonstrates the use of **K-Nearest Neighbors (KNN)** and **Decision Tree** algorithms for classifying the famous Iris dataset using the `scikit-learn` library. It includes data preprocessing, model training, evaluation, and visualization of the decision tree.

## 📁 Project Structure

```bash
iris-classification/
├── README.md
├── iris_knn_decisiontree.py
├── requirements.txt
└── images/
    └── decision_tree.png (optional if you save the plot)
```

---

## 📊 Dataset

* **Name**: Iris Flower Dataset
* **Source**: `sklearn.datasets.load_iris`

* **Features**:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width

* **Target Classes**:

  * Setosa
  * Versicolor
  * Virginica

##  Features

* Split dataset into training and test sets using stratified sampling
* Data standardization using `StandardScaler`
* Evaluate KNN with different values of `k` and with/without distance weighting
* Decision Tree Classifier with depth control
* Visualize the trained decision tree using `matplotlib`

# Getting Started
1. Clone the Repository
```bash
git clone https://github.com/your-username/iris-classification.git
cd iris-classification
```
 2. Install Dependencies

Make sure Python 3.7+ is installed. Then run:

```bash
pip install -r requirements.txt
```

Or manually install required packages:

```bash
pip install scikit-learn matplotlib
```
3. Run the Code

```bash
python iris_knn_decisiontree.py
```

##  Output

* Accuracy and F1-score for KNN with k = 1, 3, 5 (uniform and distance-based weighting)
* Decision tree plotted for visualization of feature importance and decision paths


##  Sample Visualization

*(Optional: Add image if saved)*
![Decision Tree](images/decision_tree.png)

##  Requirements

* Python 3.7+
* scikit-learn
* matplotlib

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

## 🙋‍♂️ Author

* **Your Name**
* GitHub: [@your-username](https://github.com/your-username)

