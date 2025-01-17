# Cynaptics-Induction-Task 1
To begin the task, I first focused on learning the basics of Python, just enough to meet the requirements. After that, I completed a few basic courses on Kaggle to understand the fundamentals of machine learning.

Given the limited time available, I decided to focus only on that was directly relevant to the task. So, I concentrated on learning about neural networks  , convolutional neural networks (CNNs) , GAN through YouTube videos.

## Sub Task-1
To tackle this subtask, I started by understanding exactly what the task required me to do. My first step was to go through the script to figure out the terminologies, functions, how it works, and the overall training process. Once I had a decent understanding, I made some changes to the script, added the dataset, and ran it.

Of course, there were a lot of errors at first. I kept fixing them one by one, running the script again after every fix. This process repeated several times until I finally got the script working and could train the model. However, the accuracy I got was very low initially.

To improve the accuracy, I tried every technique I could think of. Some worked, but many didn’t, which was frustrating at times. I experimented with changing the batch size and the number of epochs, applying data augmentation, trying pretrained models, using learning rate schedulers, adding batch normalization, tweaking hyperparameters like kernel size, pooling size, and regularization, and testing different optimizers. Most of these attempts failed to improve the accuracy, but a few did make a difference.

Throughout this process, I spent a lot of time researching. I watched YouTube tutorials, asked seniors and friends for help, and Googled a lot of things. It was a long and sometimes discouraging process, but I kept at it and learned a lot along the way.

Score of Gradient Hunt 1.0 -:
![Screenshot 2025-01-17 123320](https://github.com/user-attachments/assets/6f8f0d4a-6ef4-4d6d-a6be-0db61afc7880)

Score of Gradient Hunt 2.0 -:
![Screenshot 2025-01-17 123343](https://github.com/user-attachments/assets/ba9f564b-11bf-46fa-ae78-4f72d953144a)



## Sub Task-2
To complete this task, I started by learning how GANs work, focusing on understanding the roles of the discriminator and generator. I decided to use the MNIST dataset, which has images of handwritten digits.

For the coding part, I began by importing the required libraries. Then, I created separate classes for the discriminator and generator. After setting the hyperparameters, I trained both the discriminator and generator. To check the results, I used TensorBoard to view the generated images.

At first, I coded the GAN without using CNN layers. It worked, but the images it generated were blurry and not very clear. To improve this, I reworked the code and added CNN layers to the architecture. This made a big difference, and I was able to generate much clearer images of handwritten numbers.


![Screenshot 2025-01-15 181239](https://github.com/user-attachments/assets/a3f3ad1d-1115-49e2-99f5-ae1c58269d44)



