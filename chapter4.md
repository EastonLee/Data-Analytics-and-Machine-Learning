# TensorFlow

## Graph

## Tensor

```ipython3
%pylab # will automatically import numpy as np; from matplotlib import pyplot as plt
plt.style.use('ggplot')

```

Instead of a numpy.array, we are returned a tf.Tensor. The name of it is "LinSpace:0". Wherever we see this colon 0, that just means the output of. So the name of this Tensor is saying, the output of LinSpace.

For image convolution in Tensorflow, we need our images to be 4 dimensional. Remember that when we load many iamges and combine them in a single numpy array, the resulting shape has the number of images first.