# Brain-Tumor-Detection
I will document the entire process of building a brain tumor detection model, including the steps, challenges, and improvements made along the way.

**Attempt One :** Title : End to End Brain Tumor Detection

This is my first attempt at building a multi-class brain tumor classification model using TensorFlow's ResNet. Since a validation set was not provided, I split the training data into training and validation sets. Initially, I tested the model on a small subset of 200 images. Afterward, I trained the full model on the complete dataset and evaluated it using the test data. While the training accuracy reached 94%, the overall accuracy was very low only 9%. I plan to analyze the pipeline, identify mistakes, and make improvements in the next iteration.
I will upload next iteration within 1 0r 2 days thank you.

**Attempt Two:**  - Title : complete end to end brain tumor detection

In my second attempt, I decided to tackle the data mismatch issue by creating a manually valid dataset. Since my original dataset lacked proper validation data, I carefully selected and extracted 200 images from the training set, ensuring that all types of brain tumors were included. This manually created dataset was then used for validation.

I trained my model using the complete dataset, I trained my model using the full dataset, combining the original training images with the newly created valid data.For this project iam using  ResNet CNN model, and this time, the results were much more promising. The model's accuracy on the test dataset surged to 80%, a huge improvement over the 9% accuracy in my first attempt.






