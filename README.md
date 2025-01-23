# euros
Predictor for the Euros 2024

Hello, this was an individual project that I did in the summer of my freshman year and it is a model that simulates and predicts the Euros 2024.

Here are the steps that I took to build this model:

**1. Data Collection**
This was the most time consuming part of the project. I needed a metric to determine the winner of a football game and decided that the threshold that I can base the win probability off is the betting odds/ percentage chance of winning from betting websites. Therefore I formed the training data set based off winning percentages from betting websites. As for the other features such as ranking and points, I went to the official FIFA website to gather the data for that exact point of time.

**2. EDA**
I conducted EDA on the training data along with Feature Selection based on the EDA. 

**3. Model training**
I used a Linear Regression model. I realised that this was suitable because it would be more suitable for smaller datasets, as it is less prone to overfitting and fewer parameters

**4. Simulating the tournament**
I used the model that I trained to simulate the entire tournament using OOP, creating games between every game from the group stages.

**Conclusion:** This project is very simple but it taught me OOP in python and the basics of Pandas, Numpy and ways to use Scikitlearn, after this project I became more interested in Data Science and how it helps us visualize the subjective aspects of sport. 
