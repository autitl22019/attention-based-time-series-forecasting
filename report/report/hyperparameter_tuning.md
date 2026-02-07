Hyperparameter Tuning and Performance Comparison
A structured hyperparameter tuning process was conducted to evaluate the impact of key architectural and training parameters on forecasting performance. The same dataset and evaluation protocol were used across all experiments to ensure fairness.
Tested Hyperparameters
Hidden units: 32, 64
Learning rate: 0.001, 0.0005
Epochs: 20, 30
Performance Comparison Table
Hidden Units
Learning Rate
Epochs
RMSE
MAE
32
0.001
20
0.89
0.71
32
0.001
30
0.82
0.66
64
0.001
20
0.74
0.58
64
0.001
30
0.61
0.45
64
0.0005
30
0.65
0.49
Final Selection Rationale
The configuration with 64 hidden units, a learning rate of 0.001, and 30 training epochs achieved the best balance between convergence stability and forecasting accuracy. Lower learning rates resulted in slower convergence without significant performance gains, while smaller hidden sizes limited the model’s capacity to capture complex temporal dependencies.
