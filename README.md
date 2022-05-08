# Visual Sign to Text Conversion Tool

This is a final year project based on Visual Sign to Text Conversion Tool to help the dumb and deaf people communicate easily without the help of translator.

## Abstract

Sign language is one of the oldest and most natural forms of language for communication, but since most people do not know sign language and interpreters are very difficult to come by, we have come up with a real time method using neural networks for fingerspelling based on American sign language.
In our method, the image is first preprocessed and then it is passed through a classifier which predicts the class of the hand gestures. Our method provides 98.9 % accuracy for the 26 letters of the alphabet.

## Project Description

American sign language is a predominant sign language Since the only disability D&M people have is communication related and they cannot use spoken languages hence the only way for them to communicate is through sign language. 

Communication is the process of exchange of thoughts and messages in various ways such as speech, signals, behavior and visuals. 

Deaf and Mute(Dumb)(D&M) people make use of their hands to express different gestures to express their ideas with other people. 

Gestures are the nonverbally exchanged messages and these gestures are understood with vision. This nonverbal communication of deaf and dumb people is called sign language. 

Sign language is a visual language and consists of 3 major components 

![components](images/components.jpg)

In this project I basically focus on producing a model which can recognize Fingerspelling based hand gestures in order to form a complete word by combining each gesture. 

The gestures I  trained are as given in the image below.

![Signs](images/signs.jpg)

## Steps to run this project

1) Install Anaconda in your machine from https://www.anaconda.com
2) Run Jupyter Notebook.
3) Install all the requirements and dependencies.
4) Open Project.ipynb in Jupyter Notebook.
5) Run all the cells to see the results.
6) Also you can run the file runFromModel.ipnyb to see the results from previously saved models.

## Conclusion

While adding 3 dense layers of model heuristics Using VGG 19 At 10 Epochs we get 97.6% accuracy and on adding 2 dense layers we get 98.9% accuracy. Hence using 3 layers results in overfitting. Whereas we are getting 98.1% accuracy on using 2 dense layers for ResNet 50 when training for 10 epochs. Hence we are using VGG 19 for the tool.
Mute people will easily be able to take an active part in a video conference/meeting/class as this tool will help them to communicate better with other people. This tool will add immense value to the life of people and make their life easier.

## Future Scope:

● Improving Accuracy of the model.  
● Adding more words and phrases to model.  
● Final touch ups in the backend.  
● Designing a UI.  
● Integrating with meet apps/Making API for convenience.
