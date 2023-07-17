# Convolution Neural Network

## Topics covered in today's module
* Convolution neural network components
* Visualizing kernels
* Visualizing feature maps
* Pooling
* Dropout
* Batch norm

## Main takeaways from doing today's assignment

1. **Convolutional Neural Networks (CNNs)**: How CNNs work, including the role of convolutional layers, pooling layers, and dense layers. Convolutional layers apply filters to an input image to extract features, pooling layers reduce the spatial dimensions while preserving the most important information, and dense layers perform classification based on the extracted features.

2. **Filter movement in CNNs**: Learned how the 3x3 filters in a Conv2D layer "slide" across a 28x28 input image to generate feature maps. The filters are smaller than the input image and move across it to cover the entire area.

3. **Keras Sequential model**: How to define a Sequential model in Keras, how to add layers to it, and how to compile and summarize it. 

4. **Extracting and visualizing layer outputs**: How to create a new model that outputs the activations of a specific layer and how to visualize these activations.


## Challenging, interesting, or exciting aspects of today's assignment
It was hard at the start to visualize exactly how the CNNs extracted featurs with each pass, but this lesson did a great job at showing that and it was amazing to see it!

## Additional resources used 
[Fashion MNIST github](https://github.com/zalandoresearch/fashion-mnist)

[Batch Normalization post](https://stackoverflow.com/questions/41269570/what-is-batch-normalizaiton-why-using-it-how-does-it-affect-prediction)

