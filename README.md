# MNIST_custom_metric
Data Science project: proposing a custom metric that improves performances compared to L2 on MNIST.

It's a pretty big Jupyter Notebook file, and all written in French.

The proposed metric basically checks the distance between two images using L2, but one of the image will be translated in all directions by 1 pixel: the minimal distance found when doing that is the one returned.
