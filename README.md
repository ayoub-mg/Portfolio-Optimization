# Portfolio Optimization Techniques : A Comparative Study

This personal project explores advanced portfolio optimization strategies techniques to enhance risk-adjusted returns. By evaluating the performance of various strategies, ranging from traditional finance methods to modern machine learning techniques, the project provides insights into how data-driven methods can enhance portfolio construction. Each technique is compared against the MASI Index, enabling a comprehensive analysis of their effectiveness in achieving superior risk-adjusted returns.

Through these innovative techniques, the project seeks to provide a comprehensive analysis of various portfolio strategies, demonstrating the effectiveness of combining traditional finance principles with modern machine learning methodologies.

## Dataset Overview

The dataset consists of 74 Moroccan stock prices along with the MASI Index, covering the period from 2017 to 2022. Additionally, the dataset includes information about each company, such as market capitalization and sector classification.

## Features

This project implements a variety of portfolio optimization strategies, utilizing advanced techniques to analyze and construct investment portfolios:

- **Equal-Weighted Portfolio**: This straightforward approach allocates an equal amount of capital to each asset in the portfolio. While simple to implement, it provides a baseline for comparison against more complex strategies.

- **Market-Cap Weighted Portfolio**: In this method, assets are weighted according to their market capitalization. Larger companies have a greater influence on the portfolio's performance, which reflects the actual market dynamics.

- **Sharpe Ratio Optimization**: This technique focuses on maximizing the Sharpe Ratio, which measures risk-adjusted returns. By optimizing the weights of the assets, this strategy seeks to achieve the best return for each unit of risk taken, thus enhancing overall portfolio performance.

- **Mean-Variance Optimization**: Based on modern portfolio theory, this approach aims to optimize the trade-off between risk and return by calculating the expected returns and covariance of asset returns. The goal is to construct a portfolio that minimizes risk for a given expected return.

- **KMeans Clustering (Euclidean and DTW metrics)**: KMeans clustering is used to group assets based on their return patterns. The Euclidean metric captures distance in a standard geometric sense, while the Dynamic Time Warping (DTW) metric accounts for shifts in time series data, allowing for a more nuanced clustering of assets with similar temporal behaviors.

- **Autoencoder + KMeans Clustering**: In this innovative approach, autoencoders are used to compress the asset return data into a lower-dimensional latent space. This compression helps to capture essential features while reducing noise. KMeans clustering is then applied to the compressed data, enabling the selection of diversified assets based on learned representations.

## Interactive Access

For an interactive experience with the Jupyter notebooks, visit the following link to the [Web-based editor](https://github.dev/ayoub-mg/Portfolio-Optimization/blob/main/Portfolio%20Optimization.ipynb).
