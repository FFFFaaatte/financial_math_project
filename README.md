# Implemantation of Article: Hedging Simulation with Linear Regressions and Neural Networks

![Project Image](https://cdn.media.amplience.net/i/epammarketplace/hedging?maxW=1200&qlt=80&fmt=jpg&bg=rgb(255,255,255)&version=1689755316226)

This project is a simulation of article hedging using linear regressions and neural networks. The goal of the simulation is to explore the performance of different hedging strategies and compare the effectiveness of linear regression and neural network models in predicting option prices and minimizing risks.

## Report
Please refer to the [report.pdf](report.pdf) file for detailed explanations of the concepts used in this project, as well as the results and visualizations generated by the codes.

## Data Simulation
The data used for this simulation is provided in the "data" folder after running "NB1_Simulate_Data.ipynb". The folder contains the following files:

1. **train_validation_data.csv**: The training and validation data containing simulated option prices, stock prices, and other relevant features used for model training and tuning.

2. **test_data.csv**: The test data used to evaluate the performance of the models on unseen data.

3. **info_data.txt**: A text file containing additional information about the data, such as feature descriptions and data sources.

## Project Notebooks
The project is organized using Jupyter Notebooks:

1. **NB1_Simulate_Data.ipynb**: This Jupyter Notebook contains the code to simulate the necessary data for the hedging simulation. It generates synthetic data representing option prices, stock prices, and other relevant features for the hedging models.

2. **NB2_Neural_Network.ipynb**: This Jupyter Notebook focuses on implementing and training the neural network model for hedging. It includes code for hyperparameter tuning, model training, and evaluation.

3. **NB3_Linear_Regression.ipynb**: In this Jupyter Notebook, the linear regression approach for hedging is implemented and evaluated. It includes rolling linear regression, and computation of hedging mean squared errors (HMSE) in order to comparison with neural network results.

## Getting Started
To run the notebooks and replicate the simulation, follow these steps:

1. Clone this repository to your local machine.
2. Make sure you have Python 3 installed along with the required libraries specified in the `requirements.txt` file.
3. Open Jupyter Notebook and navigate to the directory where you cloned the repository.
4. Run the notebooks in the specified order (NB1_Simulate_Data.ipynb, NB2_Neural_Network.ipynb, NB3_Linear_Regression.ipynb) to reproduce the results.

## Note
Please note that the simulation results and performance of the models may vary depending on the data used for simulation and the specific configurations of the models.

## License
Feel free to explore the code and experiment with different settings to gain a deeper understanding of article hedging and the application of machine learning models in finance.

Happy coding! 🚀
