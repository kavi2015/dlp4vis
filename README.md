# dlp4vis
Deep Learning Project for Vision Science

Files of Relevance for Project Milestone:

(1) newDataSet3BlockCNN.ipynb (CNN A)

(2) newDatasetKerasVGG_googleDrive.ipynb (CNN B)

(3) VisualizationOfBasic3LayersCNN.ipynb (Attention-based Visualization)


Tasks for final report (early December):

(1) Optimize attention based classification using UNET or Class Activation Maps or Grad CAMs (or Keras), and create activation maps for CNN B (pre-trained VGG + Random Forest Classifier); try out t-SNE especically for visualizing high-dimensional data

(2) Test CNN B on Early Glaucoma Dataset using 10-fold cross validation

(3) Try out pre-trained ResNet-18 with last few layers trained on RNFL image data

(4) Compute AUC of ROC curves, try out PPV/other accuracy metrics

(5) All of above for Kaggle OCT Dataset: https://www.kaggle.com/paultimothymooney/kermany2018#OCT2017.zip

(6) If time: try simpler models to achieve higher accuracy; try more datasets; try multi-modal image input

Note: Keras ImageDataGenerator code based on code from "Deep Learning with Python" by Francois Chollet, Chapters 5 and 7

Note: Simple CNN A based on https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html

Note: Visualization technique (GRAD-CAM) code based on: https://github.com/raghakot/keras-vis
