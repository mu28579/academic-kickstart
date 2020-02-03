+++
title = "RIP Routing Simulator in Java"
date = 2017-01-01T00:00:00

+++

{{< figure library="1" src="openingWindow.png" title="Initial Window" >}}

# Project Overview
  * This project uses Java Swing create a GUI that simulates the RIP routing distance vector algorithm by reading in data from a text file.
  * Once run, the first window shows 3 options for the user. The open file button allows the user to enter the name of the input text file to be read. The step button runs the algorithm one step at a time and the run button runs the algorithm until the system of routers is stable.

{{< figure library="1" src="inputName.png" title="Input file name window" >}}

  * Once the open file button is clicked, the preceeding window appears which allows the user to enter the appropriate file name. If an incorrect file name is given, the user is shown the error message below.
  
{{< figure library="1" src="error.png" title="Error Message" >}}

  * Below is an example of an input file. The file contains 3 colums. The first two columns are the ID's of two routers and the third column is the distance between the two routers. 
  
{{< figure library="1" src="inputFile.png" title="Sample Input File" >}}
  
  
