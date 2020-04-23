This is a repository that demonstrates Neural Style Transfer using TensorFlow 2.1 framework. The content of this repository is purely for education purposes.

# What is Neural Style Transfer?
The basic idea for Neural Style Transfer is to extract the learned representation from a pretrained neural network (typically Convolutional Networks), and optimise the **generated pixels** against a pair of images: Content(C) and Style(S). The synthesised image is expected to have the grooves and motives of the _style_ image, whilst preserving the original _content_.

You will need to provide a content:
![Content Image](./assets/content.jpg)

Pair this with a desired style:
![Style Images](./assets/styles-all.png)

To synthesis a new image:
![Content Image](./assets/tfhub-synthesis-all.png)
![Content Image](./assets/synthesis-all.png)

Happy learning!

The images, algorithms, and the base content belong to its original respective owners.
