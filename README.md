MULTILABEL CLASSIFICATION PROJECT (Part 1) <br/>
<br/>
As most of the machine learning clinics on classification tasks work with MNIST and Cifar10 dataset, which are known to be easier to use for training, I was curious
which results can be achieved on dataset which contains relatively small number of images downloaded from the internet, and on the images you can detect more object, 
not just one (multilabel classification). <br/>
<br/>
I use 465 images for training dataset, 101 pictures for validation dataset, and a smaller amount for the test dataset. You can find Horse, Dolphin or both on the images. I tested several models using Pytorch or Tensorflow with various technics (data-augmentation, normalization, batch-normalization, weight decay, gradient cliping, learning rate scheduling etc.), and I was curious if 100% accuracy on the validation dataset can be reached and Tensorflow or Pytorch performs better.<br/>
<br/>
In this first part I use simpler models:
- Pytorh: CNN, Resnet9 models
- Tensorflow: DNN, CNN models
