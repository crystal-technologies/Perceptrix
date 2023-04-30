# Perceptrix

This is the revolutionary part of the entire CRYSTAL project. This is the part where Crystal processes your query, runs it through a neural network and then outputs an AI generated text, just like ChatGPT from OpenAI. But the goal is to make it even better. I am not sure whether this code even works because I do not have access to the computational resources required for such a computation intensive task. For me it will take approximately 254 years to train 0.001% of the minimum data required for optimum results. But as soon as the training is done, I will be able to improve this by adjusting the training factors on each training sequence. If you have access to this repository, then I assume you are one of my friend because I am not sure how many people are looking for an AI named Crystal. So if you want to understand how to run this for obtaining the results, just message me and I will provide you the steps.

`Wikipedia.py` is a file that webscrapes data from wikipedia and downloads all of it into a file named `wikipedia.txt`. It is a part of the vast dataset CRYSTAL will be trained on but a good starting point.

`train.py` will start the training process and create an AI model. It will most likely perform terrible if wikipedia.txt is the only data you trained it on. It will require way more data than that.

`train+chat.py` is basically the same as `train.py` but you can talk to CRYSTAL after the training has been completed.
