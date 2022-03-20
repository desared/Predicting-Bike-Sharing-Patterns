# Predicting-Bike-Sharing-Patterns
Project for [Deep Learning Nanodegree](https://www.udacity.com/course/deep-learning-nanodegree--nd101), unit 2 (Neural Networks).

Using Numpy, forward and back propagation is implemented to predict Bike-Sharing Patterns. This is the first Udacity Project from the Deep Learning Nanodegree. 
![GitHub Logo](/assets/neural_network.png)
## Setup:
1. Create a virtual conda environment:
Install these libraries: numpy matplotlib pandas jupyter notebook 
```
conda create --name deep-learning python=3
conda install numpy matplotlib pandas jupyter notebook
```

2. Activate your environment:
* Windows:
```
activate deep-learning
```
* Mac/Linux:
```
source activate deep-learning
```

3. Run the notebook server in the root directory of the project:
```
jupyter notebook
```

4. Open the Jupyter notebook called: [Your_first_neural_network.ipynb](/Your_first_neural_network.ipynb)
* The data comes from: [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
## Results to expect:
### Training and validation loss:
![GitHub Logo](/assets/loss.PNG)
### Predictions after training:
![GitHub Logo](/assets/predictions.PNG)
## Conclusions
The predictions are satisfactory given that the dataset does not have sufficient holiday training examples. 
The training loss has a value of 0.066 and the validation loss is 0.170. 
