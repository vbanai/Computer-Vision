MULTILABEL CLASSIFICATION PROJECT (Part 1) <br/>
<br/>
As most of the machine learning clinics on classification tasks work with MNIST and Cifar10 dataset which are known to be easier to use for training, I was curious
what results can be achieved on dataset which contains relatively small number of images downloaded from the internet, and on the images you can detect more objects at the same time, not just one (multilabel classification). <br/>
<br/>
For this project I used 465 images for training dataset, 101 pictures for validation dataset, and a smaller amount for the test dataset. You can see a Horse or a Dolphin or both in one image. I tested several models using Pytorch or Tensorflow and experimented with various technics (data-augmentation, normalization, batch-normalization, weight decay, gradient cliping, learning rate scheduling etc.) to reach the best result. I was curious if 100% accuracy on the validation dataset can be reached and if Tensorflow or Pytorch performs better. <br/>
<br/>
With Pytorch resnet9 model (you can find the model in part 2 of the project) I could reach 100%. Regarding Tensorflow  I could reach 97% accuracy on the validation dataset using resnet50 model (you can find the model in part 3 of the project).<br/>
<br/>
In this first part I use models:
- Pytorh: CNN, Resnet9 models
- Tensorflow: DNN, CNN models<br/>
<br/>
Part 2 of this project:  https://github.com/vbanai/Multi-label-classification_DOLPHIN_HORSE_Part2_Pytroch_Dataaugmentation_TransferL <br/>
Part 3 of this project:  https://github.com/vbanai/Multi-label-classification_DOLPHIN_HORSE_Part3_TF_Resnet9_50_models
