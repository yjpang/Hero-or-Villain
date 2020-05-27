# Hero-or-Villain
Convolutional Neural Network identifying pictures as being hero or villain image based on over 4000 images.

## Table of Contents
* [General Info](#general-info)
* [Data and Technologies](#data-and-technologies)
* [Methodology](#methodology)
* [Final thoughts and conclusion](#final-thoughts-and-conclusion)

## General Info
The presentation can be found [here](https://youtu.be/9xt1g0aqgU0). 

The main goal of this project is to develop a Machine learning model that can take an image and correctly identify it as a hero or villain.

## Data And Technologies

My data set is made up of 4000 images from google images. I went through all the images individually to make sure the images had the traditional traits for heroes and villain.  I wanted the model to detect nuances in facial features and ignore skin tones, so I added additional minority heroes to the data to reflect a more current image of heroes and villains.  I basically added "The Rock" and the cast of the "Fast and the Furious".  

And here are the technologies I used:
  1) Convolutional Neural Networks and Tensorflow
  2) Matplotlib and Seaborn: Tools for visualization.
  3) Numpy 
  4) Added a pre-trained convnet model
  5) Ran model on Google Colab(GPU) - GPU was needed to process the images.
  
## Methodology

I used a convolutional neural network to break down images to be trained and validated.  Then I added a pre-trained convnet model to further increase accuracy in its catagorizing of heroes and villains.

## Final thoughts and conclusion

This was a fun project, but it took me a long time to come up with the concept.  Initially, I wanted my final project with the Metis program to be Disney related, dealing with casting or animation development.  While trying to find an idea, I noticed that Disney was famous for having iconic heroes and villains.  

There was my concept developing a Machine learning model using Convolutional Neural Networks to help Disney determine, which actors to cast for hero or villain.  Is the costume appropriate for a villain?  How about animated characters?  Can they look more evil or good depending on angles in their faces or the color of their shoes?  There are certain characteristics and colors that humans find good or bad, heroic or evil.  Maybe its a big pleasant smile or sinister scowl.  Humans may not know how they know whats good or evil, but with enough data images a machine learning model will.

At the end this model was able to validate the level of heroism or villainism in an image then catagorized images accordingly with a 72.5% accuracy.




