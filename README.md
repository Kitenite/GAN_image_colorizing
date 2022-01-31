# GAN_image_colorizing
Using Generative Adversarial Network to color images trained on the pets dataset

Steps:
1. Create black and white version of training data (Pets dataset)
2. Train a generative neural network using the loss between the colored and black and white images as a loss function. Use a baseline Resnet for ease.
3. Train a critic to discern between the generated images and the original colored images.
4. They battle.
5. Test on unseen data.

Results:
Performs ok, there's a low ceiling for this type of work and the genrative model performs well enough without a critic. Needs to apply a more challenging dataset (Done in a different repo).
