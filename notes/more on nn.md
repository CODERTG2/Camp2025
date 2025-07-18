# CNN
Mainly for image and video data - learn patterns from visual data. 0 or 1 for each pixel for black and white image.
Convolution layer is the first layer that makes those matrices. Then pooling (max of 2 by 2 or average of 2 by 2 in the convolution matrix)

1. There is a filter(n filters for n number of pixel of values) - a smaller sized which has random 0 and 1 values like weights
2. Filter slides over the input image and multiplies the numbers in the input image
3. then it adds up all the results and the bias for one number for each spot the kernel could be.
4. then the kernel slides one pixel - and repeats
5. the new resulting matrix will not be the same the size of the image. - decomposition
6. pass the matrix through an activation function usually a relu
7. then we pass it through a neural network
8. then bpa back through the NN and the filter

## Hyperparameters
- filter size - 3x3 or 5x5 etc.
- stride - how many steps that the filter moves - 1 px or 2 px, etc.
- padding - add padding to the edges so that the feature map is the same size as all your images and it can focus on the edges as well. adds rows and columns if u want to go the other way, u can just crop it.
- pooling size - how we reduce size - max pooling or avg pooling and to what size.
- dropout rate - too many convulation and pooling layers - solves overfitting - randomly deactivates neurons in random layers
- Num of layers
- activation functions
- optimizer - how to adjust weights - Adam!

# RNN

Limitations of previous models:
1. cannot capture order and dependencies in sequence
2. typically expect fixed size input
3. lack mechs to remember past info

Use cases
- sequential data
- past info

output of a neuron cycles back as another weight in the neuron for the next pass.

Limitations of RNN
- vanishing gradient - weights are too small so the network learns very slowly
- exploding gradient - weights are too big so the opposite
