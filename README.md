# Anime-Face-Generation
In this various models will be used to generate Anime Faces starting with GANs.<br>
As of now DCGAN is done, will upload W-GAN soon.
## Dataset
The Dataset for this was taken from [Anime Face Dataset](https://www.kaggle.com/datasets/splcher/animefacedataset)
## DCGANs (In progess: A run with more Epochs is required)
The notebook was run on Kaggle <br>
Exact Architecure has been used in the model as mentioned in the paper [1.] , adding an layer to discriminator did improve the quality (visually) but any other hyperparameter tuning worsened the quality.
### Architecure
![architecure](DCGAN/images/dcgan_archi.png)
### Results
![dcgan_img](DCGAN/images/result.png)
#### Interpolation between two Random Instances
![dcgan_inter](DCGAN/images/interpolation.png)
#### Loss Curve during Training
![dcgan_loss](DCGAN/images/loss.png)
### References
1. [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434)
2. [DCGAN for classroom images](https://neuro.cs.ut.ee/wp-content/uploads/2018/02/DCGAN.pdf)
