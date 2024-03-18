<h1>Problem Description:</h1>

This repository provides a solution to a problem related to modeling viral outbreaks using the susceptible-infected-recovered (SIR) model, with a focus on the dynamics of COVID-19 spread in India.

<h2>Task:</h2>

(a) <b>Parameter Estimation:</b>

Utilize available data on COVID-19 spread dynamics in India to estimate the parameters 𝑅𝑅0 (reproduction number) and 𝛾𝛾 (recovery rate) for the first, second, and potentially third waves of the pandemic.

(b) <b>Neural Network Modeling:</b>

Develop an optimized neural network model to correlate the number of infected and recovered individuals with time, starting from mid-March 2020.
Employ the long short-term memory (LSTM) time series network model or other recurrent network models for this task.
Divide the dataset, available from March 2020 till present, into training and testing data. The training dataset could span the first 'x' number of months (e.g., 0-30 months) or follow a different delineation (e.g., first wave as training and second wave as testing).
Ensure that the mean squared error on the test dataset exceeds 0.9, and refrain from randomly selecting data points for testing to maintain temporal continuity.

(c) <b>Node Optimization:</b>

Determine the optimized number of nodes required for the problem, considering only one hidden layer in the neural network architecture.

(d) <b>Future Forecasting:</b>

Utilize the trained neural network model to forecast the infection dynamics for the next two years, starting from the current date.

<b>Instructions:</b>

Clone this repository to your local machine.

Collect relevant data on COVID-19 spread dynamics in India from reliable sources.

Execute the provided code files to estimate parameters, develop and train the neural network model, optimize the number of nodes, and make future forecasts.
