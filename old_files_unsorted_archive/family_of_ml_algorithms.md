
# Family of ML Algorithms

All ML models are devided into 4 categories:

- Linear
- Tree based
- kNN
- Neural Networks

## Linear Models

Example:
- Logistic Regression
- SVM


![image.png](images/linear_model.png)


Pros:
- Good for sparse high dimensional data

Cons:
- There are cases where points can't be separated by plane, because linear models tries to separate models using line (some are more complex, some are simple)

## Tree based models

Example:
- Decision Trees
- Random Forest
- GBDT (Gradient Boosted Decision Trees)

![image.png](images/tree_model.png)

Pros:
- Good for tabular data

Cons:
- Hard to capture linear dependency, because requiries a lot of splits

## kNN

Intuition: 
- Points closer to each other likely to have similar labels
- k-neighbors, and select labels by majority. (if unknown label closer to white labels then it's white, if there are more gray labels near unknown label then unkonwn label will be gray)


![image.png](images/knn_model.png)

## Neural Nets

Special class of ML algorithms. A smooth curve compared to decision trees.

NN goods for images, sounds, text, sequences

Use PyTorch, because it's simple to use.


Online playground for neural nets. [Neural Nets Playground](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.53659&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)


```python

```
