# AI Capstone Project 

## Dataset used:-

https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DL0321EN/data/concrete_data_week4.zip

## Course:-
https://www.coursera.org/learn/ai-deep-learning-capstone

## About the repository:-

1 . This Repository contains the 4 week AI Capstone project assignment using keras as a part of IBM-AI Engineering in which we need to classify a image containing a stone cracked or not by processing 40000 images in which nearly 30000 for training and 10000 for validation.
2 . 4th week is final assignment in which we need to campare performance in between pretrained models like Resnet50 and VGG16 using keras.

## Performance of Models:-

I ran both models to 2 epochs. Performance is as shown in below table.
| Model     | Training Accuracy | Validation Accuracy | Test Accuracy | Validation Loss | Training Loss  |
|-----------|-------------------|---------------------|---------------|-----------------|--------------- |
| Resnet 50 | 95.20%            | 94.45%              | 92.19%        | 0.0016          | 0.00741        |
| VGG16     | 99.60%            | 99.54%              | 99.34%        | 1.2517e-05      | 0.11661        |

## Conclusion:- 
### Accuracy:
- VGG16 still exhibits higher training accuracy (99.60%) compared to Resnet 50 (95.20%), indicating that it fits the training data better.

### Validation Accuracy:
- Both models have similar validation accuracies, with VGG16 at 99.54% and Resnet 50 at 94.45%. This suggests that both models perform well on the validation data, but VGG16 still maintains a slight advantage.

### Test Accuracy:
- VGG16 continues to perform better on the test dataset with an accuracy of 99.34% compared to Resnet 50's 92.19%. VGG16 is more robust and capable of making accurate predictions on unseen data.

### Losses:
- VGG16 still has a significantly lower validation loss (1.2517e-05) compared to Resnet 50 (0.0016). While both models have low training losses, the validation loss for VGG16 remains exceptionally low, indicating its strong performance.

In conclusion, even with the updated metrics, VGG16 remains the superior model for this task. It demonstrates higher accuracy and lower loss values during training, validation, and testing, making it a more suitable choice for this particular problem. However, as mentioned previously, it's essential to consider other practical factors when choosing a model for real-world applications.

In closing, the results presented here serve as a testament to the diligent research and development efforts put into this capstone project, highlighting the promising performance of the selected models and paving the way for further advancements in our research journey.

![accuracy and loss pic](https://github.com/dreamboat26/geniuscroc/assets/125608791/9e599d8a-bc69-40dd-86e5-035467e5465d)
![changing the output layer](https://github.com/dreamboat26/geniuscroc/assets/125608791/1145a117-c660-4624-809d-96d4a427f833)
![last layer changed](https://github.com/dreamboat26/geniuscroc/assets/125608791/244a6445-5f94-463a-a678-2e38aa3cc85c)
![Train the model](https://github.com/dreamboat26/geniuscroc/assets/125608791/260a788e-32ae-41a0-bbf6-d7e8abaf459a)
![Capture](https://github.com/dreamboat26/geniuscroc/assets/125608791/2c70ad1a-a90c-40c1-bd2c-7c24e7a43f74)
![Capture1](https://github.com/dreamboat26/geniuscroc/assets/125608791/e46f0353-472b-4326-86aa-d97147dc7e0d)
![Capture3](https://github.com/dreamboat26/geniuscroc/assets/125608791/61a79626-9bfd-4024-8e96-135aba45fe68)

Happy Learning!
