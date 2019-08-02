# Hand-Gesture-Detection
There are multiple way to detect hand gesture without using Machine Learning algorithm such as using color histograms and HOG classifiers, edge detection or background substraction. However, these methods tend to not very robust as it can be affected by the unusual background or changes in lighting conditions.

With a large datasets with different hand gestrues, we can train the model using neural networks. This will somewhat better than the methods mentioned above, even though it will take sometimes for us to train the model.

I found a dataset of hand gestures on [Kaggle](https://www.kaggle.com/gti-upm/leapgestrecog). This dataset contains 10 different gestures from 10 different people. For each gestures of each person, there will be 200 images of them.

This project will apply Convolutional Neural Networks to classify the image. Even though I got a high accuracy result, I cannot use the model on real life webcam image since the datasets are made with a dark background. In addition, I do not use all datasets due to my computer performance

This project serves as a stepping stone for my upcoming project on classifying hand motion. It is likely that I need to use 3D CNNs and RNN to train the model, and AWS services such as S3, EC2, and SageMaker to do that project.
