# Survey-data-exploration
I just wanted to upload this for my own sake, I was just exploring some large survey data.

My goals for this small work are:
 - take a look at the data
 - check and see if any out of the box machine learning can accurately predict the correct classes
 - see why the out of the box machine learning models cannot
 - see if I can modify some things and correctly predict the classes

From first look: 
 - the classes are very imbalanced, far fewer people have diabetes than there are without
 - many of the models have a high accuracy and low precision/recall/f1 making it seem "good" but in reality isn't
 - some models don't predict a person to have diabetes at all so how can I focus on the minority class
