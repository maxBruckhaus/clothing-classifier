# clothing-classifier
Clothing classifier implemented using convolutional neural networks in PyTorch. Achieved accuracy of 91% with 4 categories (topcs, bottoms, shoes, hats) which decreased to 69% when more categories were instroduced (dress, longsleeve, polo, etc).

Exprimented with image resizing and grayscaling in Feature Extraction from Images notebook.
Exported images_3.csv & images_4.csv using the Add_Additional_Data notebook.
FinalModel notebook contains the results of our model agains dataset 01.
FinalModel2 notebook contains the results of our model against dataset 02.

images.csv - original kaggle csv file (not using)
images_2.csv - simplified categories (not using)
images_3.csv - simplified categories with additional data (dataset 01)
images_4.csv - original kaggle file with additional data but without ambiguous data (dataset 02)

Kaggle dataset: https://www.kaggle.com/agrigorev/clothing-dataset-full
Additional data: https://www.kaggle.com/stephenyu36/other-clothes
