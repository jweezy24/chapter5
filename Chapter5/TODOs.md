# Tasks
1. Create a assembly program that retrurns the max of two different variables.

## Details

Task 1:
    I highly suggest reading the book and doing the practice before doing this.
    Name your file cp5.s.
    You need to initally start with the three variables.
        * the variables should be called t1 and t2.
        * Set the values to whatever you would like.
        * return the max of t1 or t1
    Your main should,
        1. load the addresses of the variables into a register.
        2. Load the values within the variables.
        3. compare vairables and return the max from main.
    You will also need to create a makefile to build your assembly code as well.


## Gradding
    Task 1:
        I will first run your makefile.
        Your makfile should create files specified in the chapter. (1 point)
        I will run your code useing this command `./cp5 ; echo $?`.
        The output should be the max of the two variables. (2 points)
        When I run `make clean` the files created by your make should be deleted. (1 point)
        Loading memory from variables will be worth 2 points.
        Do a comparison that branches to a new funtion depending on the comparison. (2 points)
        Return a correct value based on the values of the variables.

