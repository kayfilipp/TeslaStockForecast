# Tesla Stock Forecast 
## UCLA Econ 144, 2018

### Authors: Georges Ip, Aditya Gorla, Filipp Krasovsky, Vincent Chenneveau

In this paper, students from the UCLA Time Series Analysis class conducted a preliminary assessment of Tesla's stock price and built out a short term forecasting model that integrated stock price seasonality and trend.

Part of the modeling process involved building out several models as baselines - specifically, a linear and nonlinear model, neither of which included any STL decomposition.

<h2><b>Final STL Model </b></h2>
<img src=https://user-images.githubusercontent.com/36943200/166328411-cadcb418-48b3-460b-8da2-7affa5778fd0.png>

<h2> Residuals: </h2>
<img src=https://user-images.githubusercontent.com/36943200/166329246-adf032b2-d857-401f-9327-42c07f324647.png>

<h2><b>Conclusion</b></h2>
<p>This project was meant to demonstrate that STL decomposition and nonlinear/linear modeling alone is generally unreliable at producing residuals that do not exhibit a signal or structure for stock prices, and was part of a further attempt to integrate ARMA modeling into our analysis moving forward.</p>
