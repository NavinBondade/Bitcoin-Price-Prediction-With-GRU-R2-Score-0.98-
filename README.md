# Bitcoin Price Prediction & Forecasting With <br> R2 Score Of 0.98 & Root Mean Squared Error Of 1.17
<p align="center">
<a href="https://nbviewer.jupyter.org/github/NavinBondade/Forecasting-The-Bitcoin-Price-With-An-R2-Score-Of-0.98-MSE-Of-1.17/blob/main/Bitcon%20Price%20Predection%20Plus%20Forecasting/NoteBook/Bitcoin_Price_Prediction_With_GRU_%28R2_Score_%3D_0_98_%29_.ipynb" target="_blank">
  <img align="center"  src="https://github.com/NavinBondade/Distinguishing-Fake-And-Real-News-With-Deep-Learning/blob/main/Graphs/button_if-github-fails-to-load-the-notebook-click-here%20(4).png?raw=true"/>
</a>
</p>
<img src="https://masterthecrypto.com/wp-content/uploads/2019/11/BITCOIN-PRICE.jpg" width="900" height="530">
<p>Bitcoin is one of the world's most popular and valued cryptocurrencies since its invention in 2008 bitcoin has shown a massive jump in its price and established itself as a potential investment for investors. But the major thing that goes against investing in Bitcoin is its volatile nature, and it's not the authority of someone. Also, bitcoin is quite volatile, which makes it more difficult to predict its price. To eliminate this cumbersome task, I have created a deep learning system that is capable of predicting and forecasting bitcoin prices with a <b>root mean square error of just 1.77.</b></p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Numpy</li>
  <li>Sklearn</li>
</ul> 
<h2>Data Visualization</h2>
<h3>Bitcoin Price (High) Complete Time Series</h3>
<img src="https://github.com/NavinBondade/Bitcoin-Price-Prediction-With-GRU-R2-Score-0.98-/blob/main/Bitcon%20Price%20Predection%20Plus%20Forecasting/Graph/Bitcoin%20Price%20High.png?raw=true">
<h3>Bitcoin Price (High) Train Time Series</h3>
<img src="https://github.com/NavinBondade/Bitcoin-Price-Prediction-With-GRU-R2-Score-0.98-/blob/main/Bitcon%20Price%20Predection%20Plus%20Forecasting/Graph/Bitcoin%20Price%20High%20(Train).png">
<h3>Bitcoin Price (High) Test Time Series</h3>
<img src="https://github.com/NavinBondade/Bitcoin-Price-Prediction-With-GRU-R2-Score-0.98-/blob/main/Bitcon%20Price%20Predection%20Plus%20Forecasting/Graph/Bitcoin%20Price%20High%20(Test).png">
<h2>Model Detail</h2>
<p>The deep learning model at its core uses Gated Recurrent Units (GRU) which is a type of Recurrent Neural Network (RNN) for learning long-term dependencies and avoiding vanishing gradient problems. GRU also has a fewer number of gates than Long Short Term Memory (LSTM), which facilitates less memory usage and much faster traning. The model uses three GRU layers for learning long-term dependencies and three dense neural network layers for decision making. All the layers use RELU as an activation function except the last one.During training, the model uses Adam as an optimizer and uses mean squared error as the loss function. 
<h2>Model Training</h2>
<img src="https://github.com/NavinBondade/Bitcoin-Price-Prediction-With-GRU-R2-Score-0.98-/blob/main/Bitcon%20Price%20Predection%20Plus%20Forecasting/Graph/loss.png" width="450" height="300">
<p>The model was trained for 20 epochs with batch size of 1000. After training process the model has shown <b>loss of 9.9850e-04.</b></p>
<h2>Model Evaluation</h2>

<ul>
  <li><b>Mean Squared Error: 3.13</b></li>
  <li><b>Root Mean Squared Error: 1.77</b></li>
  <li><b>R2 Score: 0.98</b></li> 
</ul>  
<h2>Model Prediction</h2>
<img src="https://github.com/NavinBondade/Bitcoin-Price-Prediction-With-GRU-R2-Score-0.98-/blob/main/Bitcon%20Price%20Predection%20Plus%20Forecasting/Graph/Forecasting%20and%20Prediction.png?raw=true">
<p>Even without having trend, season, and patterns in time-series, the GRU based deep learning model has forecasted the next 50 days price of Bitcoin very accurately.</p>  
<h2>Conclusion</h2>
<p>In this project, I have created a Gated Recurrent Units based deep learning model which is capable of predicting and forecasting bitcoin prices with a Root Mean Squared Error of 1.7 and R2 Score of 0.98.</p>
