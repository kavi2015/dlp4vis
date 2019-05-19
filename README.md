# dlp4vis

Deep Learning Project for Vision Science - Toward Enabling Interpretable Automated Eye Disease Detection from OCT Data

Files of Relevance for Project Milestone:

(1) newDataSet3BlockCNN.ipynb (CNN A)

(2) newDatasetKerasVGG_googleDrive.ipynb (CNN B)

(3) VisualizationOfBasic3LayersCNN.ipynb (Attention-based Visualization)


Files of Relevance for Final Report:

Note: All code files can be run by downloading .ipynb of interest and opening in jupyter or directly loading from GitHub into Google Colab; each cell be be run sequentially once corresponding data is loaded into local Google Drive.

(1) Test CNN B on Early Glaucoma Dataset using 10-fold cross validation: EGD_CrossVal_Final_KerasVGG.ipynb (in 'Result' Folder)

(2) Pre-trained ResNet-18 with Random Forest: probmap_resnet18_rf.ipynb

(3) ROC Curve Code: kaggle_vgg16_rf.ipynb; Figure: kaggle_vgg16_rf_ROC.png

(4) Kaggle-8K VGG + Conv + Dense Layers: kaggle8k_VGG16pretrain.ipynb

(5) Example Data from Kaggle OCT Dataset: https://www.kaggle.com/paultimothymooney/kermany2018#OCT2017.zip

(6) Code for extracting features for tSNE visualization: KaviMod4_tSNE_VGG16pretrain.ipynb


Future Directions: Multi-modal image input, UNET for enhancing accuracy, alternate accuracy metrics


Note: Keras ImageDataGenerator code based on code from "Deep Learning with Python" by Francois Chollet, Chapters 5 and 7

Note: Non-pretrained CNNs based on https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html

Note: Visualization technique (GRAD-CAM) code based on: https://github.com/raghakot/keras-vis


Acknowledgements: We would like to thank all members of the Hood Visual Science Lab at Columbia University as well as all members of the Laboratory for Intelligent Imaging and Neural Computing at Columbia University. In particular, thanks go to Xinhui Li for help on the tSNE visualization technique, Dr. Emmanouil (Manos) Tsamis, Nikhil Bommakanti, and Rashmi Rajshekhar for useful discussions and for enabling acquisition of image data (EGD and NGD, respectively). We are also grateful to Isht Dwivedi, Prof. Iddo Drori, Dr. C. Gustavo De Moraes, Prof. Paul Sajda, and Prof. Donald C. Hood for their guidance and valuable insights throughout the development and implementation of this project.
