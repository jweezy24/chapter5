# Tasks
1. Create a assembly program that branches based off the value of three different variables.

## Details

Task 1:
    I highly suggest reading the book and doing the practice before doing this.
    Name your file cp5.s.
    You need to initally start with the three variables.
        * the variables should be called max, t1, t2.
        * Set the values to whatever you would like.
        * max tells us the cut off for a value
        * if t1 or t2 greater than max we branch to a function that adds 2 to the register r0.
        * if t1 or t2 less than the max we branch to a function that adds 1 to the register r0.
    Your main should,
        1. load the addresses of the variables into a register.
        2. Load the values within the variables.
        3. Compare the variables and branch to the functions that do something to r0.
        4. Finally your program should return 2,3, or 4 depending on the values of t1 and t2.
    You will also need to create a makefile to build your assembly code as well.


## Gradding
    Task 1:
        I will first run your makefile.
        Your makfile should create files specified in the chapter. (1 point)
        I will run your code useing this command `./cp5 ; echo $?`.
        The output should be 2,3, or 4. (2 points)
        When I run `make clean` the files created by your make should be deleted. (1 point)
        Loading memory from variables will be worth 2 points.
        Do a comparison that branches to a new funtion depending on the comparison. (2 points)
        Return a correct value based on the values of the variables.

