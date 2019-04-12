This is a project based on https://www.datacamp.com/community/tutorials/reconstructing-brain-images-deep-learning

The key idea is we are training an autoencoder to reconstruct an image. After the network learns how to reconstruct an image, we compute the difference between the reconstructed images and the original. this should give us a feeling for areas of anomaly in the input