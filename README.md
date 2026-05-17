# part-2-cnn-computer-vision

dataset sources = https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs?usp=sharing

##============TASK 6 = CNN CONCEPT EXPLAINATION===============


# What is convolution?

The convolution step in CNN involves sliding a small filter or kernel across an image to extract meaningful information such as edges, texture, patterns, or shapes.

The filter sweeps across various portions of the image and generates a feature map for analysis.

Examples of information extracted include:
- Edge detection
- Shape recognition
- Pattern identification in images

# Why is pooling used?

Pooling is applied for reducing the dimensionality of feature maps created after convolutions.

It can be helpful in:
- lowering computations
- saving memory
- accelerating the training process
- avoiding overfitting

Max Pooling is the most popular form of pooling that selects the maximum value from a small portion of the feature map.

# Why is ReLU commonly used in CNNs?

Definition of ReLU
The term ReLU refers to Rectified Linear Units.

This is a type of activation function that changes all negative numbers to zero while keeping the positive numbers as they are.

Formula
f(x) = max(0, x)

Applications of ReLU include:
- fast learning by the model
- helps in learning non-linear relationships
- prevents the issue of vanishing gradients

# Why are CNNs better than regular feed-forward networks for image data?

CNNs work best for image data since they have the capability of automatically extracting relevant information from images.

Benefits of CNNs include the following:
- Maintaining spatial relationships among image pixels
- Identifying image patterns such as edges and textures
- Having a lower number of parameters than traditional fully-connected networks
- Being more efficient for image classification purposes

Standard feed-forward networks consider images to be flat data points, whereas CNNs analyze images much better.
