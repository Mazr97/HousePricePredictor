# HousePricePredictor
>
><!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>House Price Predictions</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0 auto;
            max-width: 800px;
            padding: 20px;
        }
        
        h1 {
            color: #333366;
        }
        
        h2 {
            border-bottom: 2px solid #333366;
            color: #333366;
            padding-bottom: 5px;
        }
        
        ul, ol {
            margin: 0;
            padding: 0 20px;
        }
        
        code {
            background-color: #f4f4f4;
            border: 1px solid #ddd;
            border-radius: 3px;
            font-family: monospace;
            padding: 2px 5px;
        }
        
        a {
            color: #333366;
            text-decoration: none;
        }
    </style>
</head>

<body>

    <h1>House Price Predictions: A Data-Driven Approach</h1>

    <h2>Introduction</h2>
    <p>This project focuses on predicting house prices using various features such as the size of the house, number of bedrooms, bathrooms, and location coordinates. The project employs linear models to analyze the relationship between features and house prices, and to make predictions.</p>

    <h2>Data Description</h2>
    <p>The dataset used in this project contains information about various houses, including:</p>
    <ul>
        <li><code>house_size</code>: The size of the house in square feet.</li>
        <li><code>bed</code>: The number of bedrooms.</li>
        <li><code>bath</code>: The number of bathrooms.</li>
        <li><code>Latitude</code>: The latitude coordinate of the house.</li>
        <li><code>Longitude</code>: The longitude coordinate of the house.</li>
        <li><code>price</code>: The price of the house.</li>
    </ul>



<h2>Results</h2>
<p>The project employs linear regression models, including Lasso regression, to predict house prices. The models were evaluated using cross-validation. Lasso regression with tuned hyperparameters achieved the best performance with a testing score of 87.26%.</p>



</body>

</html>


