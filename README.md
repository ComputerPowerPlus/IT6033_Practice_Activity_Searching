# IT6033 Practice Activity: Searching
This practice repository contains starter files for a searching algorithms learning activity  
### THIS IS NOT AN ASSESSMENT!

## Part 1: Implement a sequential search on an array of ints

* Implement the searching in _SequentialSearch.indexOf()_

* Test your implementation using JUnit test _SequentialSearchTest.java_
  - select _SequentialSearchTest.java_
  - right click
  - select __Run File__
  - look at results in test results panel
  - (you may add other tests of your choice in that class)
    
* Implement the file input reading and measurements in SequentialSearch.main()
    - reading from an input file containing a list of ints separated by spaces
    - you can use _utils.In.java_ to help
    - input files are provided in folder _data_
    - implement a timer, optionally using _utils.Stopwatch.java_
    - test with small file first
    - NetBeans > Project > Properties > Run > create new configuration __Sequential Search__  with 
      - main class: _SequentialSearch.java_
      - arguments: _40 8ints.txt_
      - directory: _..\data_
     - Manu __Run__ > select __Run Project__ - this will run whichever configuration is selected in the dropdown box visible on the toolbar
    
* Perform time measurements with files of different sizes
    - run with provided files from _8ints.txt_ to _1Mints.txt_ (or create your own)
    - record measurements in a document
    
* Perform step counting
    - implement step counter in your algorithm (comment it out when doing time measurements as this may affect the time)
    - run with provided files from _8int.txt_ to _1Mint.txt_ (or create your own)
    - record measurements in a document


## Part 2: Implement a binary search on an array of ints

Similar to above, with classes
- _BinarySearch.java_
- _BinarySearchTest.java_

Run with a new configuration __Binary Search__

Note: input files must be __sorted__ lists for a binary search.


