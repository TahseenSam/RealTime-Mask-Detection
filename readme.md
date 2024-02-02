# Realtime Mask Detection

## Overview
This repository contains code for Realtime Mask Detection using a model trained on the Kaggle dataset [Face Mask Detection](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection). The model utilizes transfer learning with the VGG16 architecture, achieving promising results as shown below:

```
Epoch 5/5
35/35 [==============================] - 7s 207ms/step - loss: 0.1045 - accuracy: 0.9730 - val_loss: 0.0956 - val_accuracy: 0.9820.
```

## Results
### With Mask
![With Mask]("Results/With%20Mask.jpg")

### Without Mask
![Without Mask](Results/Without%20Mask.jpg)

## Usage
1. Clone this repository.
2. Install the required dependencies using `requirements.txt`.
3. Run the inference notebook to observe real-time mask detection using the trained model.

Feel free to explore and modify the code for your specific use case. If you have any questions or suggestions, please don't hesitate to reach out. Happy coding!
