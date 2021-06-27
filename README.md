# CovidDetector

# Data Collection
The Covid X-Ray Images were collected from the given github repository-https://github.com/ieee8023/covid-chestxray-dataset,

The chest xray images for the healthy patients were collected from the following kaggle dataset -https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

# Data Preprocessing
Here I have only selected the images which have the posterior anterior view,for the training purpose.


# Model and Accuracy
As there are only 149 xray images of infected lungs,which is much less training dataset to apply any kind of transfer learning so I decided to apply CNN model.
The model gave a accuracy of 90% on the training dataset and 81% on the validation set
