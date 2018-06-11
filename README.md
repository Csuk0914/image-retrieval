# DLforCBIR
<<<<<<< HEAD
Deep Learning for content-based image retrieval with TensorFlow.

## Image preprocessing

**img_trans.py:**

skimage and keras are required in this file. The following transformations are included:

- adjust brightness
- shit, rotate, flip, zoom
- dilation, erosion
- add oblique line
- add salt noise


## LeNet-5
LeNet-5 is a classical CNN model proposed by Yann LeCun. 

See [Gradient-based learning applied to document recognition](https://ieeexplore.ieee.org/abstract/document/726791/) for more details.

**lenet5_model.py:**

LeNet-5 implementation. ReLu is used as the activate function for convlayer and fclayer. And a drop-out layer is added before softmax in this implementation.

**lenet_train.py:**

Train lenet-5 on MNIST.

**retrieval.py:**

Extract features of query image and all retrieval images from fully-connected layer.

Performe feature similarity computation for retrieval task. Cosine similarity is adopted in this implementation.

**retrieval_.py:**

Example of using images stored on disk as tf inputs.

**usage: python retrieval.py -h**
=======
Deep learning for content-based image retrieval with TensorFlow
>>>>>>> f2f8323989939c12f04ecfbaaada9c53fb90557a
