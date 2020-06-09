# Pneumonia-Train-Models-
This repo  contains different Python Notebook script that I have used for training various CNN models for prediction of Pnuemonia from ChestXRAY.
Details of Models are following 
1) ResNet Arch (ResNet 18, 34,50,101,152)
2) VGGNet Arch (VGG16 and 19)
3) GoogleNet Arch (Inception and GoogleNet)
5) DenseNet Arch (DenNet 121)
6) ShuffleNet Arch 
7) Mobile Net Arch
8) Sequeeze Net Arc

The mentioned arch are state of art pretrained model on ImageNet Dataset. All models are trained using FastAI , a pytorch based library.
Beyound this I proposed and trained the following arch which perform better than Pretrained CNN models. Details of the arch is following:

1) ResNet used as feature extractor with Random Forest Classifier
2) ResNet used as feature extractor with LightGBM Classifier

Please feel free to use these models.
