# Ants and Bees Classification using Transfer learning
![Cover photo](https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.oneindia.com%2Fimg%2F2016%2F01%2F28-1453966107-ants-honey-bee.jpg&tbnid=AoLI8o_g1muS-M&vet=12ahUKEwj5ssOckr-EAxUNUaQEHYP1AMYQMygNegUIARCOAQ..i&imgrefurl=https%3A%2F%2Fwww.oneindia.com%2Finternational%2Fhoneybees-ants-may-provide-clues-to-suicide-in-humans-1995974.html&docid=d--5T6fE0Xy5GM&w=600&h=450&q=ants%20and%20bees&ved=2ahUKEwj5ssOckr-EAxUNUaQEHYP1AMYQMygNegUIARCOAQ)

A deep learning model is a network of weights whose values are optimized using a loss function during the training progress.
The weights of the network are typically initialized randomly before the start of the training process.
# In transfer learning:
we use a pre-trained model that has been trained on a related task(ResNet). This gives us a set of initial weights that are likely to perform better than the randomly initialized weights.
We optimize the pre-trained weights further for our specific task.


## :star: Dataset Description
Data set is splitted into Training part and testing part, each part contain two labels (Ants, Bees)
I apply data Augmantation techniques and normaliztion techniques before Training and testing 

## :star: Libraries 
- pytorch
- numpy
- torchvision
- datasets
- models
- transforms


## :star: Steps
- Exploring Data
- Data Augmantation
- Data Normalization
- Training :(Applying Forward propagation and Back propgation)
- Testing : :(Applying Forward propagation)
- Predections
- Visualize the prediction

