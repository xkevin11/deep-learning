# Deep-Learning


## Useful Resources

Keras Tutorial : The Ultimate Beginner’s Guide to Deep Learning in Python
https://elitedatascience.com/keras-tutorial-deep-learning-in-python




5 Genius Python Deep Learning Libraries
https://elitedatascience.com/python-deep-learning-libraries#keras

<ol>
  <li>Theano is a low-level library that specializes in efficient computation. You’ll only use this directly if you need fine-grain customization and flexibility.</li>
  <li>TensorFlow is another low-level library that is less mature than Theano. However, it’s supported by Google and offers out-of-the-box distributed computing.</li>
  <li>Lasagne is a lightweight wrapper for Theano. Use this if need the flexibility of Theano but don’t want to always write neural network layers from scratch.</li>
  <li>Keras is a heavyweight wrapper for both Theano and Tensorflow. It’s minimalistic, modular, and awesome for rapid experimentation. This is our favorite Python library for deep learning and the best place to start for beginners.</li>
  <li>MXNet is another high-level library similar to Keras. It offers bindings for multiple languages and support for distributed computing.</li>
</ol>


KDnuggest - 7 Steps to Mastering Deep Learning with Keras
https://www.kdnuggets.com/2017/10/seven-steps-deep-learning-keras.html


## GPU
[2018-09-02]
So I managed to get a CNN model working on my MacBook Pro (see keras_deep_learning.py) to learn MNIST dataset. The forecast accuracy on test set was over 99%!! However, using CPU it took > 40 min to train, which is too slow. TensorFlow no longer provides GPU support on macOS either as of version 1.2.

Question - which of the below?
1) e-GPU
2) [AWS EC2](https://docs.aws.amazon.com/dlami/latest/devguide/gpu.html)
3) [Google Colaboratory](https://colab.research.google.com/drive/16zuAQZHrThsi9ztnFYJVg7BC28v11D_I): training completes in 212 seconds!! Improvement by X11.3

[Tensorflow : GPU vs CPU](https://www.youtube.com/watch?v=BspsNJHO2Uw)
CPU - 176 s, GPU (GTX1080) - 8 s



### e-GPU
[StackOverflow](https://apple.stackexchange.com/questions/277356/machine-learning-on-external-gpu-with-cuda-and-late-mbp-2016)

[Kaggle thread](https://www.kaggle.com/questions-and-answers/32619)

[NVIDIA Titan Xp](https://becominghuman.ai/deep-learning-gaming-build-with-nvidia-titan-xp-and-macbook-pro-with-thunderbolt2-5ceee7167f8b)

[Picking a GPU for Deep Learning](https://blog.slavv.com/picking-a-gpu-for-deep-learning-3d4795c273b9)

[Siraj](https://www.youtube.com/watch?v=Bgwujw-yom8)

<ul>
	<li>High budget: Titan XP</li>
	<li>Moderate Budget: GTX 1060</li>
	<li>TIght Budget: GTX 1050 TI</li>
</ul>

