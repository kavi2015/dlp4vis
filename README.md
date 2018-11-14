# dlp4vis
Deep Learning Project for Vision Science

Files of Relevance for Project Milestone:

(1) newDataSet3BlockCNN.ipynb (CNN A)

(2) newDatasetKerasVGG_googleDrive.ipynb (CNN B)

(2) VisualizationOfBasic3LayersCNN.ipynb (Attention-based Visualization)


Tasks for final report (early December):

(1) Optimize attention based classification using UNET or Class Activation Maps or Grad CAMs (or Keras), and create activation maps for CNN B (pre-trained VGG + Random Forest Classifier)

(2) Test CNN B on Early Glaucoma Dataset; possibly obtain fine-grained labels to re-train both models

(3) Try simpler models to achieve higher accuracy; try more datasets; try multi-modal images

(4) Compute AUC of ROC curves, try out PPV/other accuracy metrics

Note: Keras ImageDataGenerator code based on code from "Deep Learning with Python" by Francois Chollet, Chapters 5 and 7

Note: Simple CNN A based on https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html

Note: Visualization technique (GRAD-CAM) code based on: https://github.com/raghakot/keras-vis
