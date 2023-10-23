# Image-Processing-3
 Training CNN with cifar10 dataset
**kaggle version mynet:** https://www.kaggle.com/dataminingee/cifar10-with-mycnn
**kaggle version vgg19 transfer learning:** https://www.kaggle.com/dataminingee/cifar10-trained-with-vgg19-transferlearning

## Environment
|Environment|Version|
|-----------|----------|
|python |3.8|
|jupyter notebook|6.5.2|
|cuda|12.0|

## Packages
|Package|Version|
|-----------|----------|
|torch           |                  2.1.0+cu118|
|torchaudio       |                 2.1.0+cu118|
|torchsummary     |                 1.5.1|
|torchvision      |                 0.16.0+cu118|
|numpy|1.23.4|
|matplotlib|3.3.1|

## Execute Code
python CIFAR10_UI.py

![image](https://github.com/Study-boy-dot/Image-Processing-3/assets/80616480/e17fd7dc-34b7-45cc-884f-c279eaf7b998)
1. Show 9 cifar10 images
2. Print out model structure
3. Show Image augmentation result
4. Show training and validation process history
5. Use trained model doing prediction
```diff
- Remember to train your own model with my provided code or yourself and modify filepath of model
```

`CIFAR10_Trained_with_MyNet.ipynb`: classify cifar10 with my CNN and output model file  
`CIFAR10_Trained_with_VGG19_TransferLearning.ipynb`: classify cifar10 with pretrained vgg19 and output model file

## Code Review
hackmd: https://hackmd.io/@1Xh3vNpPQ1ebdS9gVi7gXg/B11k4LWz6
