# Yoga Pose Detection and Correction


This project aims to develop a real-time yoga pose detection system that provides feedback on the accuracy of the user's pose. The system uses a deep learning model trained on images of yoga poses.

## Data Preprocessing
- The images are resized to 224x224 pixels to match the input requirements of the pre-trained ResNet-18 model.
- Data augmentation techniques such as random horizontal flipping, rotation, and color jittering were applied to improve generalization.

## Model Architecture
We used a pre-trained ResNet-18 model, which was fine-tuned for the binary classification task (correct or incorrect pose). The model’s fully connected layer was modified to output a single value, which is then passed through a sigmoid activation function to produce the final prediction.

## Training
The model was trained for 10 epochs with a batch size of 8. The loss function used is BCEWithLogitsLoss, which is suitable for binary classification tasks. The Adam optimizer was used to update the model’s weights.

## Results
- The model achieved a validation accuracy of 100%.
- The final test accuracy was 100%.

## Challenges
- Collecting enough labeled data for training posed a challenge. The dataset was limited in variety, which may have impacted the model’s generalization.

## Future Work
- Improve the dataset by including more diverse yoga poses and capturing different angles.
- Explore more complex architectures for better accuracy.


