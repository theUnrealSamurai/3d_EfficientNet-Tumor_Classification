# 3d_EfficientNet-Tumor_Classification [PyTorch]
solution for the kaggle rsna-miccai-brain-tumor-radiogenomic-classification

The notebook uses a 3d EfficientNet-b1 model to train and classify the images for the glioma tumor. 

to the run the notebook upload the notebook to kaggle and add these 2 datasets to the notebook [data1](https://www.kaggle.com/datasets/jonathanbesomi/rsna-miccai-png) and [data2](https://www.kaggle.com/competitions/rsna-miccai-brain-tumor-radiogenomic-classification/data) turn on the GPU and run the notebook.

I used a unique way of merging the pictures by taking the average of images when there are more number of images in the sequence and duplicating the images when there are less in the squence to obtain a constant number of slices in each data sample. 
The dataset is very small in size. So training the model for more than 10 epochs will start overfitting the model. So avoid training it for more epochs




