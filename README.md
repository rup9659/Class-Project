# Class-Project
Deep-Learning Class Project
# Trained image classification & Detection model

This repository contains code for the following Keras models:
- ResNet50
- Inception v3
- Faster R-CNN

Pre-trained weights can be automatically loaded upon instantiation (`weights='imagenet'` argument in model constructor for all image models). Weights are automatically downloaded if necessary, and cached locally in `~/.keras/models/`.







## References

- [Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556) - please cite this paper if you use the VGG models in your work.
- [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385) - please cite this paper if you use the ResNet model in your work.
- [Rethinking the Inception Architecture for Computer Vision](http://arxiv.org/abs/1512.00567) - please cite this paper if you use the Inception v3 model in your work.




## License

- All code in this repository is under the MIT license as specified by the LICENSE file.
- The ResNet50 weights are ported from the ones [released by Kaiming He](https://github.com/KaimingHe/deep-residual-networks) under the [MIT license](https://github.com/KaimingHe/deep-residual-networks/blob/master/LICENSE).

`
