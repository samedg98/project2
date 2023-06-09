# Project 2

# Samed Ganibegovic

# Concurrent UNIX Processes and shared memory


--------------------------------------------------------------------------------------------------------

Brief Description: 

The goal of this project is to become familiar with concurrent processing in Linux using shared memory.  

--------------------------------------------------------------------------------------------------------

Invoking the solution:

master should take in several command line options as follows:

master -h master [-h] [-s i] [-t time] datafile

-h          Describe how the project should be run and then, terminate.
-s x        Indicate the number of children allowed to exist in the system at the same time.  (Default 20)
-t time     The time in seconds after which the process will terminate, even if it has not finished.  (Default 100)
datafile    Input file containing one integer on each line.


--------------------------------------------------------------------------------------------------------

How to run the project: 

First, you will need to type "make" into the command prompt.
This will create the necessary .o files as well as the executable files.
Then, you type ./master followed by any of the above options. *if no datafile is given, an error message will be prompted*
Now, the program will run as expected.
To clean the project, type "make clean".

--------------------------------------------------------------------------------------------------------

Issues and problems with the program:

I had trouble completing bin_adder to have the bakery algorithm.
This led to bigger issues with the code as a whole.
I had the project running using a different algorithm, however, since the requirements were for bakery algorithm or no grade for the algorithm at all, 
I decided to just leave the working code out and turn it in as is.


*Edit*

I am resubmitting this project for the final time, as I tried to figure out the bakery algorithm.
I was able to compile something with the concept included.
When I had something running before, using a different algorithm, the output was much more advanced.
However, I decided to go with this as it is something and I tried to incorporate the bakery algorithm. 
One element I struggled with and could not figure out for whatever reason was the two log files.

*****

--------------------------------------------------------------------------------------------------------

Link to version control:

https://github.com/samedg98/project2 
