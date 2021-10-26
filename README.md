# Privilaged-GAN
A new way to Train the Classical GAN model for consistent and stable result using such a combination of framework consisting two GAN and auto encoder


# Short description
It is a unsupervised learning framework based on adverserial training consisting of two GAN and a autoencoder acts as generator for child GAN.


# Long description
## version 1:
The architecture used in version 1 is shown in figure below:
![version one architecture ](https://github.com/basantbhandari/Privilaged-GAN/blob/main/Privilaged%20GAN/previlaged_GAN_v1/nested_GAN_with_autoencoder.png)


As we can see on the above diagram,there is parent GAN in which generator start from random noise and the child GAN, in which the generator consist of autoencoder that takes the generated outcomes of parent GAN that why it is privilaged GAN. The both GAN follows the the classical GAN training approach. In each epoch, first train parent GAN and then child GAN. The child learn from the parent GAN success.
The outcome while training the privilaged GAN with ANN is as:
![v1 training_ANN](https://github.com/basantbhandari/Privilaged-GAN/blob/main/Privilaged%20GAN/previlaged_GAN_v1/gans_training_ANN.gif)

The outcome while training the privilaged GAN with CNN is as:
![v1_training_CNN](https://github.com/basantbhandari/Privilaged-GAN/blob/main/Privilaged%20GAN/previlaged_GAN_v1/gans_training_CNN.gif)




## version 2:
The architecture used in version 2 is shown in figure below:
![version two architecture ](https://github.com/basantbhandari/Privilaged-GAN/blob/main/Privilaged%20GAN/previlaged_GAN_v2/nested_GAN_with_autoencoder_improved.png)


As we can see on the above diagram,there is parent GAN in which generator start from random noise and the child GAN, in which the generator consist of autoencoder that takes the generated outcomes of parent GAN that why it is privilaged GAN. The both GAN follows the the classical GAN training approach. In each epoch, first train parent GAN and then child GAN. The child learns from the parent success as well as parent failure.
The outcome while training the privilaged GAN with ANN is as:
![v2 training_ANN](https://github.com/basantbhandari/Privilaged-GAN/blob/main/Privilaged%20GAN/previlaged_GAN_v2/gans_training_ANN.gif)

The outcome while training the privilaged GAN with CNN is as:
![v2_training_CNN](https://github.com/basantbhandari/Privilaged-GAN/blob/main/Privilaged%20GAN/previlaged_GAN_v2/gans_training_CNN.gif)














