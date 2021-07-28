MULTILABEL CLASSIFICATION PROJECT <br/>
<br/>
As most of the machine learning clinics on classification tasks work with MNIST and Cifar10 dataset which are known to be easier to use for training, I was curious
what results can be achieved on dataset which contains relatively small number of images downloaded from the internet, and on the images you can detect more objects at the same time, not just one (multilabel classification). <br/>
<br/>
For this project I used 465 images for training dataset, 101 pictures for validation dataset, and a smaller amount for the test dataset. You can see a Horse or a Dolphin or both in one image. I tested several models using Pytorch or Tensorflow and experimented with various technics (data-augmentation, normalization, batch-normalization, weight decay, gradient cliping, learning rate scheduling etc.) to reach the best result. I was curious if 100% accuracy on the validation dataset can be reached and if Tensorflow or Pytorch performs better. <br/>
<br/>
With Pytorch resnet9 model (you can find the model in part 2 of the project) I could reach 100%. Regarding Tensorflow  I could reach 97% accuracy on the validation dataset using resnet50 model.<br/>
<br/>
<br/>
Part 1<br/>
<br/>
I am experimenting with standard models:<br/>
- Pytorh: CNN, Resnet9 models<br/>
- Tensorflow: DNN, CNN models<br/>
<br/>
<br/>
Part 2<br/>
I am testing RESNET-9 and RESNET-50 model created by Tensorflow. Both model reaches pretty good results, TF-RESNET-9 reached 95% and TF-RESNET-50 carried out 97% accuracy.
<br/>
<br/>
Part 3<br/>
<br/>
In this part I am focusing on PYTORCH-RESNET-9 model presented in part 1, extending it and trying out various technics such as data-augmentation, normalization, batch-normalization, weight decay, gradient cliping, learning rate scheduling, Adam optimizer instead SDG. This model performs the best, I reached 100% accuracy on the validity dataset and 99% on the test dataset. In the end I am doing experiment with transfer learning but not with good result.(With tensorflow, VGG16 pretrained model I reached better result earlier, but it is not included in this project)

