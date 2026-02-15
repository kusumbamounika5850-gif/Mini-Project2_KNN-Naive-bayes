# Mini-Project2_KNN-Naive-bayes

<h1 align="center">🌸 Iris Species Classification Web Application</h1>

<p align="center">
  A Machine Learning powered Flask web application that predicts Iris flower species using KNN and Naïve Bayes algorithms.
</p>

<hr>

<h2>🧩 Tech Stack</h2>

<ul>
  <li>🐍 Python 3.8+</li>
  <li>🌐 Flask</li>
  <li>🤖 Scikit-learn</li>
  <li>🎨 Bootstrap 5</li>
  <li>☁️ Deployed on Render</li>
</ul>

<hr>

<h2>📌 Project Overview</h2>

<p>
This Flask-based web application classifies Iris flowers into three species:
</p>

<ul>
  <li>🌼 Setosa</li>
  <li>🌸 Versicolor</li>
  <li>🌺 Virginica</li>
</ul>

<p>
Users can input flower measurements and instantly receive:
</p>

<ul>
  <li>✔ Species prediction</li>
  <li>📊 Accuracy score</li>
  <li>📈 Classification report</li>
  <li>🔢 Confusion matrix</li>
</ul>

<hr>

<h2>🚀 Features</h2>

<h3>🖥️ Interactive Prediction Panel</h3>

<table>
<tr>
<th>Feature</th>
<th>Description</th>
<th>Example</th>
</tr>
<tr>
<td>Sepal Length</td>
<td>Length of sepal (cm)</td>
<td>5.1</td>
</tr>
<tr>
<td>Sepal Width</td>
<td>Width of sepal (cm)</td>
<td>3.5</td>
</tr>
<tr>
<td>Petal Length</td>
<td>Length of petal (cm)</td>
<td>1.4</td>
</tr>
<tr>
<td>Petal Width</td>
<td>Width of petal (cm)</td>
<td>0.2</td>
</tr>
</table>

<h4>🎯 Example Input</h4>

<pre>
Sepal Length: 5.1
Sepal Width: 3.5
Petal Length: 1.4
Petal Width: 0.2
Model: KNN
</pre>

<h4>✅ Example Output</h4>

<pre>
Predicted Species: Iris Setosa
Accuracy (Test): 100%
</pre>

<hr>

<h2>🤖 Machine Learning Models</h2>

<h3>🔵 K-Nearest Neighbors (KNN)</h3>
<ul>
<li>k = 3 neighbors</li>
<li>Distance-based classification</li>
<li>Simple and effective</li>
</ul>

<h3>🟢 Gaussian Naïve Bayes</h3>
<ul>
<li>Probability-based classifier</li>
<li>Assumes Gaussian distribution</li>
<li>Fast and lightweight</li>
</ul>

<hr>

<h2>📚 Dataset Information</h2>

<p><b>Source:</b> Iris Dataset (150 samples)</p>

<h3>📊 Feature Ranges</h3>

<table>
<tr>
<th>Feature</th>
<th>Range</th>
</tr>
<tr>
<td>Sepal Length</td>
<td>4.3 – 7.9</td>
</tr>
<tr>
<td>Sepal Width</td>
<td>2.0 – 4.4</td>
</tr>
<tr>
<td>Petal Length</td>
<td>1.0 – 6.9</td>
</tr>
<tr>
<td>Petal Width</td>
<td>0.1 – 2.5</td>
</tr>
</table>

<h3>🌸 Target Classes</h3>

<table>
<tr>
<th>Class</th>
<th>Label</th>
<th>Samples</th>
</tr>
<tr>
<td>Setosa</td>
<td>0</td>
<td>50</td>
</tr>
<tr>
<td>Versicolor</td>
<td>1</td>
<td>50</td>
</tr>
<tr>
<td>Virginica</td>
<td>2</td>
<td>50</td>
</tr>
</table>

<hr>

<h2>📈 Model Performance</h2>

<h3>🔵 KNN Results</h3>

<table>
<tr>
<th>Metric</th>
<th>Training</th>
<th>Testing</th>
</tr>
<tr>
<td>Accuracy</td>
<td>95%</td>
<td>100%</td>
</tr>
<tr>
<td>Setosa F1</td>
<td>1.00</td>
<td>1.00</td>
</tr>
<tr>
<td>Versicolor F1</td>
<td>0.93</td>
<td>1.00</td>
</tr>
<tr>
<td>Virginica F1</td>
<td>0.92</td>
<td>1.00</td>
</tr>
</table>

<hr>

<h2>📂 File Structure</h2>

<pre>
iris-classifier/
│
├── app.py
├── requirements.txt
├── Procfile
├── templates/
│   └── index.html
├── KNN.pkl
├── Navis.pkl
├── train_knn.json
├── test_knn.json
├── train_Navia.json
└── test_Navia.json
</pre>

<hr>

<h2>☁️ Deployment on Render</h2>

<h3>Step 1: requirements.txt</h3>

<pre>
Flask
scikit-learn
numpy
gunicorn
pandas
joblib
</pre>

<h3>Step 2: Procfile</h3>

<pre>
web: gunicorn app:app
</pre>

<h3>Step 3: Deploy</h3>

<ul>
<li>Push to GitHub</li>
<li>Create Web Service on Render</li>
<li>Build Command: pip install -r requirements.txt</li>
<li>Start Command: gunicorn app:app</li>
</ul>

<hr>

<h2>⚙️ Local Development</h2>

<pre>
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
</pre>

<p>Open in browser:</p>

<pre>
http://127.0.0.1:5000/
</pre>

<hr>

<h2>🔒 Security Considerations</h2>

<ul>
<li>Input validation</li>
<li>Safe JSON parsing</li>
<li>No sensitive data stored</li>
</ul>

<hr>

<h2>🚀 Future Enhancements</h2>

<ul>
<li>Add Decision Tree & Random Forest</li>
<li>Data visualization charts</li>
<li>CSV batch prediction</li>
<li>API endpoints</li>
<li>User authentication</li>
</ul>

<hr>

<h2>📬 Contact</h2>

<ul>
<li>📧 Email: Kusumbamounika5850@gmail.com</li>
<li>🔗 LinkedIn: Mounika Kusumba</li>
<li>💻 GitHub Repository: Mini-Project2</li>
</ul>

<hr>

<p align="center">❤️ Created by Mounika Kusumba</p>
