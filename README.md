# IT6033 Practice Activity: Searching
This practice repository contains starter files for a searching algorithms learning activity (THIS IS NOT AN ASSIGNMENT)

## Part 1: Implement a sequential search on an array of ints

Implement the searhing in SequentialSearch.indexOf()

Test your implementation using JUnit test SequentialSearchTest.java
    * select SequentialSearchTest.java
    * right click
    - select Run File
    - look at results in test results panel
    (you may add other tests of your choice in that class)
    
Implement the file input reading and measurements in SequentialSearch.main()
    - reading from an input file containing a list of ints separated by spaces
    - you can use utils.In.java to help
    - input files are provided in folder data
    - implement a timer, optionally using utils.Stopwatch.java
    - test with small file first
    - NetBeans > Project > Properties > Run > new configuration with 
                main class: SequentialSearch.java
                arguments: 34 8int.txt
                directory: ..\data
    
Perform time measurements with files of different sizes
    - run with provided files from 8int.txt to 1Mint.txt (or create your own)
    - record measurements in a document
    
Perform step counting
    - implement step counter in your algorithm (comment it out when doing time measurements as this may affect the time)
    - run with provided files from 8int.txt to 1Mint.txt (or create your own)
    - record measurements in a document


## Part 2: Implment a binary search on an array of ints

Similar to above, with classes
- BinarySearch.java
- BinarysearchTest.java

Note: input files must be sorted lists.


