<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heart Disease Prediction README</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            margin: 40px auto;
            max-width: 800px;
            padding: 0 20px;
            color: #333;
            background-color: #f6f8fa;
        }
        .container {
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            border-bottom: 2px solid #eaecef;
            padding-bottom: 0.3em;
            margin-top: 24px;
        }
        pre {
            background-color: #f0f0f0;
            padding: 16px;
            border-radius: 6px;
            overflow-x: auto;
        }
        code {
            background-color: #e0e0e0;
            padding: 2px 4px;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Heart Disease Prediction using ANN 🩺</h1>
        <p>This project uses an Artificial Neural Network (ANN) to predict heart disease. The model is trained on a dataset containing various medical parameters.</p>
        <hr>
        <h2>Project Overview 📊</h2>
        <p>The goal of this project is to build a classification model that can accurately predict the presence of heart disease in patients. An ANN is implemented using the Keras and TensorFlow libraries.</p>
        <h3>Dataset</h3>
        <p>The dataset used is <code>Dataset--Heart-Disease-Prediction-using-ANN.csv</code>. It includes 303 entries and 14 columns, with <code>target</code> as the feature to be predicted. Key features in the dataset include:</p>
        <ul>
            <li><strong>age</strong>: Patient's age</li>
            <li><strong>sex</strong>: Patient's sex</li>
            <li><strong>cp</strong>: Chest pain type</li>
            <li><strong>trestbps</strong>: Resting blood pressure</li>
            <li><strong>chol</strong>: Serum cholesterol</li>
            <li><strong>fbs</strong>: Fasting blood sugar</li>
            <li><strong>restecg</strong>: Resting electrocardiographic results</li>
            <li><strong>thalach</strong>: Maximum heart rate achieved</li>
            <li><strong>exang</strong>: Exercise induced angina</li>
            <li><strong>oldpeak</strong>: ST depression induced by exercise relative to rest</li>
            <li><strong>slope</strong>: The slope of the peak exercise ST segment</li>
            <li><strong>ca</strong>: Number of major vessels (0-3) colored by fluoroscopy</li>
            <li><strong>thal</strong>: A blood disorder called thalassemia</li>
            <li><strong>target</strong>: Presence of heart disease (1) or not (0)</li>
        </ul>
        <hr>
        <h2>Methodology ⚙️</h2>
        <p>The project follows a standard machine learning workflow:</p>
        <ol>
            <li><strong>Data Loading and Exploration</strong>: The dataset is loaded into a pandas DataFrame.</li>
            <li><strong>Data Preprocessing</strong>: The features are scaled using <code>StandardScaler</code> from scikit-learn.</li>
            <li><strong>Model Building</strong>: A sequential ANN model is built using Keras. It consists of multiple dense layers with <code>relu</code> activation functions and a final output layer with a <code>sigmoid</code> activation function for binary classification.</li>
            <li><strong>Training</strong>: The model is compiled with the <code>adam</code> optimizer and <code>binary_crossentropy</code> loss function. It is then trained on the preprocessed data.</li>
            <li><strong>Evaluation</strong>: The model's performance is evaluated using a confusion matrix, classification report, and accuracy score. The model achieves an accuracy of approximately <strong>88%</strong> on the test set.</li>
        </ol>
        <hr>
        <h2>Required Libraries 📚</h2>
  <ul>
            <li><code>pandas</code></li>
            <li><code>numpy</code></li>
            <li><code>matplotlib</code></li>
            <li><code>seaborn</code></li>
            <li><code>tensorflow</code></li>
            <li><code>keras</code></li>
            <li><code>scikit-learn</code></li>
  </ul>
</div>
</body>
</html>
