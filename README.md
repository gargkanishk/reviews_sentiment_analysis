
<h1>Sentiment Analysis on Movie Reviews</h1>
<br>
<body>

<h1>Project Overview</h1>
<p>This repository contains a Jupyter Notebook implementation for sentiment analysis on movie reviews. The task involves building a machine learning model to predict the sentiment of review texts based on a comprehensive dataset of movie reviews.</p>

<h2>Competition and Dataset</h2>
<p>The dataset comprises movie-review pairs with extensive details such as movie title, description, genres, duration, director, actors, users' ratings, review text, reviewer name, and more. The objective is to use these features to predict the sentiment of the review text, classified as either "POSITIVE" or "NEGATIVE".</p>

<h3>Dataset Description</h3>
<ul>
    <li><strong>Objective</strong>: Predict sentiment of movie reviews.</li>
    <li><strong>Files</strong>:
        <ul>
            <li><code>train.csv</code>: Training set with review sentiment and other features.</li>
            <li><code>test.csv</code>: Test set with review features but without the sentiment column.</li>
            <li><code>movies.csv</code>: Metadata on movies.</li>
        </ul>
    </li>
    <li><strong>Columns</strong>:
        <ul>
            <li><code>movieid</code>: Unique identifier for the movie.</li>
            <li><code>sentiment</code>: Target column indicating "POSITIVE" or "NEGATIVE".</li>
            <li>Other columns are self-explanatory.</li>
        </ul>
    </li>
</ul>

<h2>Implementation Details</h2>
<p>The Jupyter Notebook (<code>main.py</code>) comprises various components crucial for the machine learning pipeline. The following tasks were executed:</p>

<table>
    <tr>
        <th>Component Name</th>
    </tr>
    <tr><td>Imputation</td></tr>
    <tr><td>Feature Processing (scaling and encoding)</td></tr>
    <tr><td>Feature Engineering/Extraction</td></tr>
    <tr><td>Dimensionality Reduction, Feature Selection</td></tr>
    <tr><td>Pipeline</td></tr>
    <tr><td>Model</td></tr>
    <tr><td>Loss Function</td></tr>
    <tr><td>Training</td></tr>
    <tr><td>Inference</td></tr>
    <tr><td>Evaluation Metrics</td></tr>
    <tr><td>Detecting and Fixing Underfitting/Overfitting</td></tr>
    <tr><td>CV and Hyperparameter Tuning</td></tr>
</table>

<h3>Algorithms Used</h3>
<p>Multiple algorithms were utilized for the sentiment analysis, including:</p>
<ul>
    <li>Naive Bayes</li>
    <li>Decision Trees</li>
    <li>Stochastic Gradient Descent (SGD)</li>
    <li>XGBoost</li>
    <li>Regression, and more</li>
</ul>

<h3>Performance</h3>
<p>The model achieved an accuracy of 0.82 on the test dataset, indicating robust predictive performance.</p>

<h2>Usage</h2>
<p>To use this repository, clone it and run the <code>main.py</code> Jupyter Notebook. Ensure all dependencies are installed, as listed in the requirements file.</p>

</body>
</html>
