# 4641Proj2
Download the github repository :https://github.com/jminowa3/4641Proj2

Download ANT to compile files
open the folder ABAGAIL-master with your favorite IDE

Part one

Open Assignment two, and run the program with command arguments
java -cp ABAGAIL.jar Assignment2.AssignmentTwo and fill in the arg parameters with
For RHC: hidden layers #, iteration #, 'RHC'
For GA: hidden layers #, iterations #, 'ga'
For SA: hidden layers #, iterations #, 'sa'
Then you can change the values of each hyperparameter in the code

Example:
java -cp ABAGAIL.jar Assignment2.AssignmentTwo 2 2000 sa
which runs a neural net with 2 hidden layers, 2000 iteration with hyperparameter values used in the code

It will output values of weights, number of correctly and incorrectly classified, and training and testing time

Part two
can be run using 
ex:
java -cp ABAGAIL.jar opt.test.knapsacktest

open either knapsacktest.java, flipfloptest.java or travelingsalesmantest.java, and run them as is, it will store in a csv file with each of the algorithm's fitnesses as well as their hyperparameters, and in command line it will print best runtime and fitness evaluation with each hyperparameter
