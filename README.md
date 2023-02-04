# TimeSeries_ANN_Project "CNC Mill Tool Wear"

This project was developed within the framework of AI studies. The main point was to show thought process behid model training and data understanding.



## Table Of Content
- [Project](#Project)
    - [About dataset](#About_Dataset)
    - [Scope](#Scope)
    - [Data analysis](#Data_Analysis)
    - [Model development](#Model_Development)
- [Libraries and Algorithms used](#Liabraries_and_Algorithms)
    - [Libraries](#Libraries)
    - [Algorithms](#Algorithms)
- [Future plans](#Future_plans)

## Project

This project was developed within the framework of study AI. The main point was to provide deep data analysis and train the model using Artificaial Neural Networks.

### About_Dataset


<img align="right" width="100" height="100" src="https://github.com/MarinaPak108/AI_TimeSeries_ANN_Project_CNC/blob/main/test_artifact.jpg">
A series of machining experiments were run on 2" x 2" x 1.5" wax blocks in a CNC milling machine in the System-level Manufacturing and Automation Research Testbed (SMART) at the University of Michigan. Machining data was collected from a CNC machine for variations of tool condition, feed rate, and clamping pressure. Each experiment produced a finished wax part with an "S" shape - S for smart manufacturing - carved into the top face, as shown in test_artifact.jpg (included in the dataset).



### Scope

To meet the deadline and perform analysis and model training properly project scope was limited to:

*   deep data exploratory analysis
*   data preprocessing (variables cleaning)
*   building time series  and ANN model, model hyperparameters tuning to detect inadequate clamping

### Data_Analysis

Data were visualized in several combinations:

*   variables per each experiment
*   variables in connection to completed vs not completed experiiment
*   requested vs actual variables in connecttion to completed vs not completed experiments

### Model_Development

Model was developed by checking optimal:

*   optimizer
*   learning rate
*   patience
*   model architecture

## Liabraries_and_Algorithms
### Libraries
libraries and their implementation in current project:

*   [pandas](https://pandas.pydata.org/) - for data manipulation and analysis
*   [numpy](https://numpy.org/) - for scientific computing with Python
*   [matplotlib](https://matplotlib.org/) - for creating static, animated, and interactive visualizations in Python
*   [seaborn](https://seaborn.pydata.org/) - for drawing attractive and informative statistical graphics
*   [holoviews](https://holoviews.org/) - for complex data annotation and seamless and simple visualization
*   [sklearn](https://scikit-learn.org/stable/) - to analyze results
*   [Module: tf.keras](https://www.tensorflow.org/api_docs/python/tf/keras) - for developing artificial neural network

### Algorithms

<p align="center">
  <img width="460" height="300" src="https://ars.els-cdn.com/content/image/3-s2.0-B0122274105008371-gr1.gif">
</p>

Artificial neural network (ANN) is a computational model that consists of several processing elements that receive inputs and deliver outputs based on their predefined activation functions.(1)

1.Journal of Environmental Management, 2015. ["Artificial Neural Network"](https://www.sciencedirect.com/topics/earth-and-planetary-sciences/artificial-neural-network)

## Future_plans

Later on it is planned to:
*   perform feature selection 
*   train model using recurrent neural network (RNN), that suits more for training timeseries dataset

repository image [source](https://laserstore.ru/images/thumbnails/533/400/blog/109/%D1%81%D0%BD%D1%81.jpg)
