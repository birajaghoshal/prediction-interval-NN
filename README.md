# prediction-interval-NN
Confidence and prediction intervals for regression problems with neural networks.

Confidence intervals are generated by training multiple neural networks simultaneously, each with a bootstrapped version of the training data. 

Prediction intervals are generated by outputting predictions of user defined quantiles from the network as well as the mean prediction.

Implementations of feedforward NN and Recurrent Neural Net included. 

See [blog](www.economai.com) for details. Papers to follow.

# Usage

Three example scripts are included: example_nn.py, example_nn_timeseries.py and example_rnn.py which demonstrate usage for a feedforward NN, feedforward NN for time series prediction, and RNN for time series prediction respectively. 

# Output

### Example output predicting a sin-based function with a feedforward NN
![Example output](Figure_2.png?raw=true "Example output")

### Example output predicting time series data with a Recurrent NN
![Example output](Figure_1.png?raw=true "Example output")

# License
Covered by the CreativeCommons license which allows for research and personal use only. For a commercial license contact the authors. See https://creativecommons.org/licenses/by-nc/4.0/

