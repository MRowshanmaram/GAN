# GAN
a GAN model for generating flowers
this is a model based on a Mathlab training moddel. that you can fined it by searching "Train Generative Adversarial Network (GAN)" in the search box of Mathlab.
more over you can find the data set on this link "https://www.tensorflow.org/datasets/catalog/tf_flowers"
after loading the dataset it have been preprocessed and reshaped. for the sake of having a bigger dataset we augment the data to include random horizontal flipping and resize the images to have size 64-by-64.

We normalize each image to [-1,1] by  using hjkhk
"image = ( image - 127.5 ) / 127.5" and augument by using "tf.image.random_flip_left_right(image)" method of tensorflow.
