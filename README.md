# 👕 Fashion MNIST Image Classification

### **1. What is the Fashion MNIST dataset?**
It's a collection of 70,000 pictures of clothes like shirts, pants, and shoes. Each picture is small (28x28 pixels) and shows one type of clothing item. We use it to train our model to recognize different clothes.

### **2. Why do we normalize image pixel values before training?**
We divide the pixel values by 255 to make them smaller (between 0 and 1). This makes it easier for the model to learn and train faster. Big numbers can slow down the training process.

### **3. List the layers used in the neural network and their functions.**
- **Flatten layer** - turns the 2D image into a single line of numbers
- **Dense layer with 128 neurons** - finds patterns in the data
- **Dense layer with 10 neurons** - gives us the final predictions for each clothing type

### **4. What does an epoch mean in model training?**
One epoch means the model looks at all the training images once. If we use 10 epochs, it goes through all the images 10 times to learn better.

### **5. Compare the predicted label and actual label for the first test image.**
We can check if the model guessed correctly by comparing what it predicted to the real answer. The code shows both values so we can see if they match or not.

### **6. What could be done to improve the model's accuracy?**
We can add more layers, use more neurons, or train for more epochs. We could also try different settings or add more variety to the training data to help it learn better.


**🔗GOOGLE COLAB: https://colab.research.google.com/drive/1mtMoeeN9ebsz-0Mb069-PfuwBjWXNI9S?usp=sharing**
