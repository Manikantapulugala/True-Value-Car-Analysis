<!DOCTYPE html>
<html lang="en">
<body>
<div class="container">

<h2>📘 Project Title</h2>
<p><strong>Exploratory Data Analysis of Maruti True Value Used Car Dataset</strong></p>

<h2>📌 Project Summary</h2>
<p>
This project involves a detailed Exploratory Data Analysis (EDA) of the Maruti True Value used car dataset to identify patterns and trends influencing vehicle resale prices.
The dataset contains 595 rows and 8 columns, including attributes such as model, price, fuel type, kilometers driven, EMI, year of manufacture, and location.
</p>

<h2>🎯 Problem Statement</h2>
<p>
To analyze how various factors affect car pricing, including:
</p>
<ul>
    <li>Kilometers Driven</li>
    <li>Fuel Type</li>
    <li>Manufacturing Year</li>
    <li>Car Condition</li>
    <li>EMI</li>
</ul>

<h2>⚙️ Technologies Used</h2>
<ul>
    <li>Python</li>
    <li>Pandas & NumPy</li>
    <li>Matplotlib & Seaborn</li>
    <li>Jupyter Notebook</li>
</ul>

<h2>🛠 Methodology</h2>

<h3>1. Data Cleaning</h3>
<ul>
    <li>Removed special characters from Price & KMS Driven columns</li>
    <li>Handled missing values using mean and mode</li>
    <li>Standardized formats and corrected datatypes</li>
    <li>Dropped irrelevant columns</li>
</ul>

<h3>2. Data Manipulation</h3>
<ul>
    <li>Outlier handling using IQR method</li>
    <li>Feature Engineering:
        <ul>
            <li>Car Age</li>
            <li>Car Condition</li>
        </ul>
    </li>
    <li>Converted EMI to integer for numerical accuracy</li>
</ul>

<h2>📊 Analysis Performed</h2>

<h3>Univariate Analysis</h3>
<ul>
    <li>Most frequent model: Wagon R VXI</li>
    <li>Petrol is the dominant fuel type</li>
    <li>Common EMI range: ₹10,000 - ₹12,000</li>
</ul>

<h3>Bivariate Analysis</h3>
<ul>
    <li>Price decreases as kilometers driven increases</li>
    <li>2022–2024 models have higher prices</li>
    <li>Mumbai cars are in better condition</li>
</ul>

<h3>Multivariate Analysis</h3>
<ul>
    <li>Cars under ₹2 lakh & below 40,000 km are mostly Petrol</li>
    <li>Alto and Zen Estilo show better resale value</li>
    <li>Correlation matrix used to study numerical relationships</li>
</ul>

<h2>📈 Key Findings</h2>
<ul>
    <li>Lower KM cars retain higher value</li>
    <li>Newer models have better resale potential</li>
    <li>Petrol dominates economical segment</li>
</ul>

<h2>✅ Outcome</h2>
<p>
The project provides insights into factors influencing used car pricing, helping buyers, sellers, and dealers make informed decisions based on data-driven analysis.
</p>
