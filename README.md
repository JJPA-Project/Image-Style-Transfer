# Image style transfer AI (Deep Learning)


**Authors : Paul-Antoine Inghelbrecht, Joël Hamilcaro, Jie Tu**

## Project Summary:

The objective of this project was to develop an image style transfer algorithm. After studying different research papers, we concluded that the types of structures that can be used to develop a style transfer algorithm are the following:

- **(1) « A Neural Algorithm of Artistic Style »** ([Gatys, Ecker, Bethge](https://arxiv.org/abs/1508.06576))
- **(2) A trained model for the transfer of a single style** ([Johnson, Alahi, Fei-Fei](https://arxiv.org/abs/1603.08155))
- **(3) Pre-trained model for any type of arbitrary transfer** [Huang](https://arxiv.org/abs/1703.06868) et [Ghiasi](https://arxiv.org/abs/1705.06830).

In this project, we opted for the first method. Then, as an extension, we tried to implement the other two.

## Notebooks :

- `1_Projet_HAMILCARO_TU_INGHELBRECHT.ipypnb` :Contains the whole project in which we implemented the **(1)** model. We created it step by step, then we tried to improve it and to optimize it in the finest possible way (variation of hyperparameters, tests with different optimizers, etc.). We obtained very satisfactory results both in terms of speed of execution and image quality. Indeed, this approach is very fast (even without GPU), and the output images are very satisfactory.


- `2_Annexe_HAMILCARO_TU_INGHELBRECHT.ipypnb` : As an extension, we have made an attempt to implement a specialized architecture in a single style (which it will be able to transfer to any image). This is the model cited in the article by [Johnson, Alahi and Fei-Fei](https://arxiv.org/abs/1603.08155). Similarly, we have done research on the implementation of a model which, in a single training step, adapts to any type of transfer: the "Arbitrary Style Transfer", described in particular in the papers by [Huang](https://arxiv.org/abs/1703.06868) and [Ghiasi](https://arxiv.org/abs/1705.06830).
