# Waste vs Recyclable
Suppose there was a need to automatically classify items as organic waste or recyclable, how could could this be done? One way is to capture an image of the items and classify them for downstream sorting. The notebook within this repo demonstrates how to fine-tune an existing image classifying model using transfer learning. Here, the pre-trained VGG16 Convolution Neural Network (CNN) model from the Keras library is fine-tuned as an example of how to quickly develop such a model.

Within the notebook is a full walkthrough showing how data was loaded, the model building process, training, and performance validation. Additionally, there are visualizations included to assess the dataset, overall model performance, and prediction accuracies.<br />
Below is an example of the images used for training and validation (500 for each class, 1,000 total), and final testing (100 for each class, 200 total).<br />
![d7f394dd-a6f1-41d4-8fdc-e79d1d18be4c](https://github.com/user-attachments/assets/35d19475-5d30-45ad-9387-1172a49e0ad2)<br />
![d615b537-4eb4-4afe-b4b1-25477d40e781](https://github.com/user-attachments/assets/0bcb13e6-c482-41fb-8b58-599196c41f61)<br />



## Results Overview
The model was able to achieve 80% accuracy on the test set, with similarly high and training/validation accuracies and loss, respectively.<br />
![TrainVal_acc](https://github.com/user-attachments/assets/f01b411a-c37b-4ed6-96eb-f59afc17668b)![TrainVal_loss](https://github.com/user-attachments/assets/f573a273-cce0-4053-aa8e-b564d7a0875e)<br />

Below is an example of the test set predicitons.<br />
![WasteRecyc_predictions](https://github.com/user-attachments/assets/3ce698df-26f8-4a9d-9d41-be49165d060b)
