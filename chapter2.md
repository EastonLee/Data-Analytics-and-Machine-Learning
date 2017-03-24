# Machine Learning

### Softmax

$$ S(y_i) = \frac{e^{y_i}}{\sume^{y_i}} $$

If scale $$y_i$$ up, the results get close to 0 or 1, if scale $$y_i$$ down, the results get uniformed.

### Cross entropy

### Numerical Stability

```python
a = 1000000000
for i in range(1000000):
    a+=0.000001
print a
```

### Stochastic Gradient Descent (S.G.D)

If your data is too big to process, don't process it as a whole, slice it into batches, train your model on batches, that will boost your training process.

Use momentum to replace straight gradient, the momentum is the running average of recent gradient. And keep learning rate decreasing.

### AdaGrad

### ReLU (Rectified Linear Units)

y = 0 when x<=0, y = x when x > 0

### Early Terminating

Watch the learning curve as you are training models, once the validation set performance error begins to rise, stop there, otherwise the model will be overfitted.

### L2 regularization

### Dropout

TODO: clarify
Randomly discard half of input data. If dropout doesn't work for you, you probably need a bigger neural network. (Deep Learning on Udacity)

Remember: Dropout should only be introduced during training, not evaluation, otherwise your evaluation results would be stochastic as well.

### Convolutional Networks

Patch/kernel

Stride same padding/valid padding

### Vanishing/Exploding Gradients

To solve exploding gradient, use Gradient Clipping
To solve vanishing gradient, use LSTM

### LSTM (Long/Short Term Memory)

### Embedding

Use cosine to calculate distance between embeddings.

### Word2Vec

### tSNE

In embedding, given you want to find similar words, if you use PCA(principle component analysis), much information will be lost, so use tSNE.

### RNN (Recurrent Neural Network)

### Beam Search

## Reinforce Learning

## Dictionary Learning

## Probability Graph Model

## Bayesian Method

## Deep Belief Network

## Autoencoder