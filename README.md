# Brain Tumor Localization

Details:
  Number of Brain MRI scan: 3929
  Data Source: https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation
  
Steps Involved:
  Input: MRI scan.
  First Phase: Detect Tumor using Resnet Classifier Model.
  Second Phase: If tumor is present, using ResUnet model to localize the tumor on pixel level.
  Third Phase: Send the output image in JSON format.


Weight File has exceeded the upload file size. Here are the link to obtain the weight file.
Weight file for Image Classification:
https://drive.google.com/file/d/1PhtHnR_lJnyIhrqVDnxAE3HXPacW1jdB/view?usp=sharing

Weight file for Image Segmentation:
https://drive.google.com/file/d/1tPFr3rwpNeyYA6YuYA-caB2Cryh2UggX/view?usp=sharing


In this project, the Explainable AI part is on hold. 
