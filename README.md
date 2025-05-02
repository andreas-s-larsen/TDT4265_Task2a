# TDT4265_Task2a

Presentation of project on Blackboard.

Cybele is used in the notebooks to retrieve data, and MONAI is used throughout all notebooks.

EAD.ipynb is simple Exploratory Data Analysis of the data.

<h3>Early Models</h3>
model_v1.ipynb is the first working model I got from the project. It uses U-Net, DiceLoss, Novograd, DiceMetric. It has simple data preprocessing.

model_v5.ipynb is a later model that incorporates sliding windows, data augmentation, AdamW, DiceFocalLoss, and other enhancements.

model_v9.ipynb is a working multiclass model with hard data augmentation. It uses Attention-Unet with early stopping, a learning rate scheduler, early stopping, and other enhancements.

<h3>Final Model</h3>
model_v12.ipynb is the final model. It uses SegResNet from the MONAI library. 

A lot of data augmentation is done to enhance the training process as the data is quite limited.

Results of the final model:
Test Loss: 0.3065
Test Dice: 0.6083


By: Andreas Seierstad Larsen
