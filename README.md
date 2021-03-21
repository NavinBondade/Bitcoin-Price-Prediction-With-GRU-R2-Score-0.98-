# Bitcoin-Price-Prediction-With-GRU-R2-Score-0.98-
<img src="https://masterthecrypto.com/wp-content/uploads/2019/11/BITCOIN-PRICE.jpg" width="900" height="530">
<p>Bitcoin is one of the world's most popular and valued cryptocurrency since its invention in 2008 bitcoin has shown a massive jump in its price and established itself as a potential investment for investors. But the major thing that goes against investing in Bitcoin is its volatile nature, and it's not the authority of someone. Also, bitcoin is quite volatile, which makes it more difficult to predict its price. To eliminate this cumbersome task, I have created a deep learning system that is capable of predicting and forecasting bitcoin prices with a <b>mean square error of just 1.77.</b></p>
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
<p>The deep learning model at its core uses Gated Recurrent Units (GRU) which is a type of Recurrent Neural Network (RNN) for learning long-term dependencies and avoiding vanishing gradient problems. GRU also has a fewer number of gates than Long Short Term Memory (LSTM), which facilitates less memory usage and much faster traning. The model uses three GRU layers for learning long-term dependencies and three dense neural network layers for decision making. All the layers use RELU as an activation function except the last one.During training, the model uses Adam as an optimizer for performing backpropagation and uses mean squared error as the loss function. 
<h2>Model Training</h2>
<img src="https://github.com/NavinBondade/Bitcoin-Price-Prediction-With-GRU-R2-Score-0.98-/blob/main/Bitcon%20Price%20Predection%20Plus%20Forecasting/Graph/loss.png" width="450" height="300">
<p>The model was trained for 20 epochs with batch size of 1000. After training process the model has shown <b>loss of 9.9850e-04.</b></p>
<h2>Model Evaluation</h2>
<ul>
  <li>Mean Squared Error: 3.13</li>
  <li>Root Mean Squared Error: 1.77</li>
  <li>R2 Score: 0.98</li>

