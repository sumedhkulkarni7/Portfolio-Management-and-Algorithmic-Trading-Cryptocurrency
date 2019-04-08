# INFO 7374 : Applied Machine Learning and Python in Finance - Final Project
## Title : Portfolio-Management-and-Algorithmic-Trading-Cryptocurrency

#### Contributed by:
##### 1. Sumedh Kulkarni
##### 2. Harshini Mashruwala
##### 3. Aahana Khajanchi
##### 4. Ravi Mundhe
##### 5. Jay Choksi
##### 6. Vividh Talesara

## Data
The datasets used for this task are of [Bitcoin](https://github.com/sumedhkulkarni7/Portfolio-Management-and-Algorithmic-Trading-Cryptocurrency/blob/master/BITCOIN_Final.xlsx), [Litecoin](https://github.com/sumedhkulkarni7/Portfolio-Management-and-Algorithmic-Trading-Cryptocurrency/blob/master/LITECOIN.xlsx) and [Ethereum](https://github.com/sumedhkulkarni7/Portfolio-Management-and-Algorithmic-Trading-Cryptocurrency/blob/master/ETHEREUM.xlsx). Other dataset used is [NVIDIA](https://github.com/sumedhkulkarni7/Portfolio-Management-and-Algorithmic-Trading-Cryptocurrency/blob/master/NVDA.xlsx).

## Analysis Performed
### Objective
Develop Trading strategies for crypto-currencies using machine learning techniques in Python and without using pre-built libraries but by defining functions.

### Approach
Using Python we develop strategies like:
1. Bootstraping 
2. Principal Component Analysis(PCA)
3. Kalman filter 
4. Monte-Carlo simulation 
5. Bollinger band
6. Moving Averages 
7. Linear Regression(OLS) 
8. Random Forest
9. Recurrent Neural Network 
10. Long-Short Term Memory

### Steps
1. Load the dataset into three different dataframes
2. Perform the necessary EDA and plot the graphs to visualize the analysis
3. Develop functions to deploy the Machine Learning techniques
4. Develop the strategies to calculate beta(β)
5. Plot graphs to compare different strategies

### Insight

![image](https://user-images.githubusercontent.com/35174083/55693479-56968580-597d-11e9-9e60-6f5e23a51e13.png)

![image](https://user-images.githubusercontent.com/35174083/55693536-8e053200-597d-11e9-95d4-85da910f43b5.png)

![image](https://user-images.githubusercontent.com/35174083/55693576-c1e05780-597d-11e9-8a5a-4f733f442835.png)


#### Trading Signals:

![image](https://user-images.githubusercontent.com/35174083/55693597-de7c8f80-597d-11e9-9f75-f2ab14bc51d6.png)

#### Cumulative and Total Returns:

![image](https://user-images.githubusercontent.com/35174083/55693652-226f9480-597e-11e9-9b58-3b2255355405.png)


### Conclusion
1. Random Forest performs very good as compared to Linear Regression, accuracy is 90%
2. Recurrent Neural Netwoks(RNN) and Long Short Term Memory(LSTM) strategies also perform very well with an accuracy of 88%
3. Simple trading strategies like Kalman filter, Monte-Carlo Simulation, Bollinger Bands, Moving Average also predict very well
