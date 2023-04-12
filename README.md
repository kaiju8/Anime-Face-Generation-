# Anime-Face-Generation
In this various models will be used to generate Anime Faces starting with GANs
As of now DCGAN is done, will upload W-GAN soon.
## Dataset
## DCGANs
The notebook was run on Kaggle
Exact Architecure has been used in the model as mentioned in the paper [og] , adding an layer to discriminator did improve the quality (visually) but any other hyperparameter tuning worsened the quality.
### Architecure
![architecure](DCGAN/images/dcgan_archi.png)
### Results
The main result is in the notebook
#### Interpolation between two Random Instances
![interpolation](DCGAN/images/interpolation.png)
#### Loss Curve during Training
![loss_curve](DCGAN/images/loss.png)
### References
[og]: [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434)
2. [DCGAN for classroom images](https://neuro.cs.ut.ee/wp-content/uploads/2018/02/DCGAN.pdf)
