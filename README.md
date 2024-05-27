# deeplearning

Inside here are some of my deep learning projects

### Project 1

### Project 2 description
This project was split into two parts. We used a perturbed versions of the MNIST dataset. In the first task we object localization, and testet out three cnn architectures to predict the output tensor [pred, cx, cy, w, h, label]. In the second task we did object detection where we had multiple objects. Here we made a grid of the input image and predicted the same tensors for each grid cell, basically imitating a simple version of the yolo algorithm. Here we tested out three new architectures, but we had to make the output tensor match the grid cell (2x3).  For all the tasks we created a custom training, performance, and loss function.

### Project 3
This was a three part project. Here we first trained our own word embeddings. Then we created our own simple transformer model to predict the conjugation of be/have, given a context of the n words before and after. Lastly, we created a text generation model where we implemented a beam search algorithm. 
