# Use a Pre-trained Image Classifier to Identify Dog Breeds

## Project Goal

The primary goal of this project is to enhance your Python programming skills by using a pre-trained image classifier to identify dog breeds. The focus is on applying Python tools, rather than building the classifier from scratch.

## Project Description

Your city is hosting a citywide dog show, and you've volunteered to help with contestant registration. Participants are required to submit an image of their dog along with biographical information. The registration system tags these images based on the provided information. However, some participants may attempt to register non-dog pets.

To ensure that only dogs are registered, you will use an already developed Python classifier. **Note:** You do **not** need to create the classifier; it will be provided to you. Your task is to apply your Python skills to use the classifier effectively.

## Tasks

1. **Determine the Best Image Classification Algorithm:** 
   - Using your Python skills, evaluate different image classification algorithms to identify which one performs best in classifying images as "dogs" or "not dogs."

2. **Assess the Accuracy of Dog Breed Identification:**
   - Determine how accurately the best classification algorithm identifies specific dog breeds.

3. **Measure Algorithm Runtime:**
   - Measure the time each algorithm takes to solve the classification problem. Keep in mind that there is often a trade-off between accuracy and runtime. More accurate algorithms may take longer to run and require more computational resources.

## Important Notes

For this task, you will use a deep learning model known as a Convolutional Neural Network (CNN). CNNs are particularly effective at detecting features in images, such as colors, textures, and edges, and then using those features to identify objects.

You will work with a CNN that has been pre-trained on a large dataset called ImageNet, which contains 1.2 million images. Different CNN architectures (such as AlexNet, VGG, and ResNet) perform differently depending on the criteria you are optimizing for. In this project, you will explore these three architectures and determine which is best suited for your application.

The `classifier.py` file provided includes a classifier function that allows you to use these CNNs for image classification. The `test_classifier.py` file contains an example program demonstrating how to use the classifier function. Your task is to use your Python skills to complete the classification tasks using the provided classifier function.

### Similar Dog Breeds

Some dog breeds look very similar, making it challenging for algorithms to distinguish between them. The more images the algorithm has learned from, the better it will perform. Some examples of similar-looking breeds include:

- Great Pyrenees and Kuvasz
- German Shepherd and Malinois
- Beagle and Walker Hound

## Reviewer Notes

Congratulations on passing this project! 🎉 You've done an excellent job. To further optimize your project, consider exploring the following Python concepts:

1. **Building a Regular Expression:** Learn to build regular expressions using the `re` module.
2. **Using f-strings:** Explore the new and improved f-string formatting functionalities in Python.

Feel free to revisit the project anytime and keep up the great work! :udacious:

confirm.udacity.com/e/85afd4d0-6c23-11ee-a521-735df0b7fb4d
