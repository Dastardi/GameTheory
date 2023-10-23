An easy-to-use resource created by Luke Currier and Rory Smead for modeling replicator dynamics using Python!

## Guide to Running Simulations<br>
### How to run in Google Colab: <br>
1. Go to https://colab.google/.
2. In the upper right corner, click New Notebook.
3. Once in your notebook, click File -> Upload Notebook -> Github.
4. Search for "rorysmead/gametheory".
5. Select "Current Version". It should load automatically.
6. Once in the notebook, you need to run the first two cells before you can run the third cell containing run(). You can do that using Shift->Return or by pressing the play button in the top left corner of the cell.
7. Once you've done that, you're off to the races! You can create new matrices by using the same format as the others in the second code cell (make sure you type your brackets and commas carefully, we'll try to figure out a better way of doing this soon!).
8. Additionally, you can edit mutation and correlation levels as well as change how the output appears using the variables listed below and in the notebook. 

### Variables: <br>
<b>Mutation: mu</b><br>
Default value: 0.00<br>
The chance of mutation, from 0 to 1. <br>

<b>Correlation: r</b><br>
Default value: 0.00<br>
The chance of correlation, from 0 to 1. <br>

<b>Number of Runs: runs</b><br>
Default value: 10<br>
The number of times the program runs a randomized simulation according to the provided matrix.<br>
The program will average results from all runs to arrive at a percentage spread of strategies. <br>

<b>Maximum Number of Generations: maxgen</b><br>
Default value: 1000<br>
The maximum number of replications in a given simulation.<br>
This number will not be reached by most traditional games.<br>

<b>Print Runs: printruns</b><br>
Default value: True<br>
A boolean (True or False) that determines if the simulation shows results for each individual run in addition to the averaged results.<br>

<b>Print Generations: printgen</b><br>
Default value: True<br>
A boolean (True or False) that determines if the simulation shows how many generations it took for the simulation to stabilize.<br>

<b>Random Matrix: randfill</b><br>
Default value: True<br>
A boolean (True or False) that determines whether the matrix has random or uniform distribution.<br>
