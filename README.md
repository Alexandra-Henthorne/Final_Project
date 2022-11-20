# Final_Project

For this segment I have used pandas , matplot, and beautifulsoup, KD Tree and other applications as shown in step one to sort and analyze my data.

I first cleaned the data to make sure there were no errors, missing data or columns that did not benefit the data.

Since the white wine data had far more data than the red I needed to match the data set number and  I neeeded to perform a randomization to make sure that I was not being biased . So I matched the white nd red wine to 1599 .

AFter this one done, data cleaned and the  same amount of infmration for both sets of wine I could begin coding. 

I first made a correlation table to see if any ingredients correlated to the quality of wine. This was not helpful as the data  for the quality of wine was not all the same . Which is what I was hoping but it couldnt be that easy. :) 

I then wanted to make sure since I was just looking at numbers and colums so I created a scatter plot for each ingredient in correltion with quality to see if something stood out .

Nothing was really standing out to me from this correlation.

So then I went on to create a training set  at 80 percent of the total data and 20 percent of the testing.

After this I wanted to see what the training set looked like by not specifying a red or white wine.

It gave me high qaulity wines but the issues was that the qualities all differed. 

Now to the Kd Tree

The reason that I choose to use this is was because I was hoping that it would better show or determine my hypothesis/question. A K-Dimensional tree is a tree data structure for organizing sample points in a k dimensional space. The tree will store the rows of wine based off of their features .

After determining the K values and their error output it was then time to choose a k value that I thought would best demonstrate our data. 

I choose K=4 because there was a zero error percentage and no chance of a tie .

After placing the k value into the training ang testing data set I then looked at the top ten outputs. When looking at the data I could see that it was giving me multiple different quality points they were all not the same . So since it was not giving me a precise conclusion and giving me all tens or eights I decicided to plot the data and then see if finding the mean would help.

By looking at the mean and plot of the data set after finding the rms I can see that the error output was still small which was hopeful meaning that the data was not horrible to work with but was still not giving out the ouput I desired to answer my question.
