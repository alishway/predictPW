<h1>This is a shiny application for developing data product's course project</h1>

<h2>What does it do?</h2>

Predicts the Iris flower pedal width, using sepal width and length, plus the pedal length.

<h2>What is iris flower data about?</h2>

It is collected by Edgar Anderson to quantify the morphologic variation of Iris flowers of three related species, i.e. Setosa,Versicolor and Virginica. Four attributes of each species are measured from each sample, i.e. sepal and petal length and width, in centimetres. 


<h2>Instructions on how to use the application</h2>

To predict petal width, this shiny application requires the user to select 3 attributes using “slider input” features. When the user make the selections:

-	First, the selections appear on the top right
-	Then the prediction value of Petal width appears right below it (in centimetres)
-	Lastly, the plot of petal length versus petal width appears right below everything. On the plot you can see the colored grouping of all the species. Also, the predicted value of petal width appears in a reddish circle, on the plot. The predicted value of petal width dynamically changes, as the users change their inputs.


<h2>How to install and run?</h2>

You can download both server.R and ui.R files and then place them all in the same folder. Name the folder, i.e. PredictPW. Then open an R session, change your working directory to the home directory of "predictPW" folder" and then type runApp(‘PredictPW’). 

You can view the application by clicking <a href="https://alishway.shinyapps.io/predictPW/">predictPW</> or go to the following link:
https://alishway.shinyapps.io/predictPW/

