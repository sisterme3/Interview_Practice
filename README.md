# Coding Interview Practice

### Steps for Problem Solving

***Listen:*** Pay close attention to any information in the problem description. You need it for an optimal algorithm. Pull out or write down any unique information. ****DON'T LEAVE OUT KEY DETAILS WHILE CODING: MAKE A CHECKLIST**

***Example:*** Draw an example of the problem for better understanding. Draw it on a whiteboard/paper. Make sure that the example is large enough, specific enough, and not a special case. 

***Brute Force:*** **STATE** the brute force algorithm and explain the space/ time complexity, let your interviewer know that you understand the easiest solution. Don't worry about developing an efficient algorithm yet. State a naive algorithm and its runtime, then optimize from there. Don't code yet!

***Optimize:*** Walk through the brute force with BUD optimization or try some of these ideas:
* Look for any unused info. You usually need all the info in a problem. How can you use the new information?

* Solve it manually on an example, then reverse engineer thought process. How did you solve it? Use a new example to see a new pattern in the problem

* Solve it "incorrectly" and then think about why the algorithm fails/ Can you fix those issues? Find an inefficient solution to move to an efficient solution

* Make a time vs. space tradeoff. Figure out the Big O and see if you can reduce it to O(N) or O(Log N)

* Figure out if you do something before the main function to have better results (sort, reorganizing,etc.)

* Use a Hash table. They are used alot within interview questions. 

* Think about the best run time

***BUD Optimization***

***B: Check for Bottlenecks (large wait times, large array accesses, one-time work, a chunk of work done repeatedly)***

***U: Unnecessary Work (Are you doing things are unnecessary for the sake of the problem)***

***D: Duplicated Work (Do you have multiple things doing the same thing)***

***Walk Through:*** Now that you have an optimal solution, **walk through your approach in detail.** Make sure you understand each detail before you start coding. (Keep talking to your interviewer) Get as close to perfect before coding as possible. Know your variables and when they change. 

*Write pseudocode carefully. Use it for var declarations and general if statements; however, for a loop. Just write the loop out in the language. Don't write sloppy code at any moment.*

***Implement:*** Write beautiful code. Modularize your code from the beginning and refactor to clean up anything that isn't beautiful. Start coding in the far top left corner of the whiteboard, avoid line creeping (write in a straight line), it makes your code look sloppy.

### **Beautiful Code looks like this**

* **Modularized Code: Use methods to break down your algorithm. if there is an odd initialization(like creating a matrix or array initialization) pretend you already have a function for that and keep it moving.**

* **Error Checks: Just make a TODO on the side of error checking that you could do later if you had more time**

* **Use other classes/structs where appropriate: If there is alot of data being loaded in a certain way(pair), you could pretend that there is a class that handles it and fill in the details later.**

* **Write good variable names. Not too long, not too short. Make it clear for what they are used for**

***If you see something that you can refactor later on, then explain this to the interviewer and make a decision if it is worht fixing***

***Remember that you have a short amount of code to show that you are a great developer. Everything counts.***

***Good Code Properties***
* **Correct:** The code should work on all expected and unexpected inputs
* **Efficent:** The code should operate the in the best time and space complexity, including the asympotoic (Big O) efficiency and the practical real life efficiency
* **Simple:** The code should be as concise as possible. It should be quick to write.
* **Readable:** A different developer should be able to read your code, should have comments and implements things in an easy way.
* **Maintainable:** Code should be reasonably adaptable to changes during the life curcle of a product and should be maintainable by another dev

* **Use Data Structures:** You can create your own class(data structure) within a problem to make it easier to handle a messy set of data
* **Appropriate Code Reuse** You can create reusable methods to clean up your solution to a problem
* **Modular** Separate large chunks of code into their own methods to make the code more maintainable, readable, and testable
* **Flexible and Robust** You can write for a more general case than a specific case
* **Error Checking** Make sure you validate what the input is

***Test:*** 
* **Conceptual Test.** Walk through your code like you would for a detailed code review. Does it do what its supposed to do
* **Unusual or non-standard code** Make sure you check weird looking things, they are usually where the little errors lie
* **Hot Spots** Like arithmetic and null nodes, Investigate things known to cause problems (Recursion base cases, Integer division, null nodes in binary trees, The start and end of iteration throught a linked list)
* **Small test cases** It's much faster than a big test case and just as effective, use tiny array or tiny strings to test things.
* **Special cases and Edge Cases** Test it against null or single element values and the extreme cases.
**Correct bugs carefully!**


### Tips for Optimizing and Solving Problems

* ***Look for BUD [B: Bottlenecks U: Unneccesary Work D: Duplicated Work]***

* ***Do It Yourself [Run through the problem in your own way, using a real example. Most of the time the way you do it is an optimal solution!! Be aware of any optimal solutions you added without realizing it]***

* ***Simplify and Generalize [Tweak data types with the problem and figure out a new solution]***

* ***Base Case and Build [Solve the Base Case and build to more complex cases using the solutions to the easier ones]***

* ***Data Structure BrainStorm [Run through a list of data structure and decide which approach is easiest]***

* ***Check BCR (Best Conceivable Runtime: Not necessarily achieveable, you just can't do better than that): It might give you a hint on how to solve a problem. Also, doing work equal to or less than the BCR is a freebie, it won't add to your runtime complexity.***


* ***Remember interviews are supposed to be challenging. Don't be afraid of a hard problem, just breathe and get to work!***


# Common Types of Problems



### Palindromes



### Greatest Pair(Adjacent)




### Greatest Pair(Sum/Product)




### Lowest Pair



### Finding Something in an Array (Locating a set of numbers etc.)




### String Manipulation 





# Theory based Knowledge



## Bit Manipulation




## Memory(Stack vs. Heap)



## Recursion




## Big O Time and Space

***Always derive, don't guess. Big O is not a multiple choice question***




## Big O Notation for particular problems 

* Iterating through a String: **O(NlogN)**

* A loop(int i=0; i<n(or any number); i++) with NO division within the header:  **O(N)**

* A nested loop with NO division within the header: **O(N^n) n = How many loops there are**

* A loop that contains division (int i=0; i<n/2; i++): **O(logN)**

* A nested loop that contains multiple division: **O(logN* O(of the other loops))**

* A get, size, length, add, subtract, divide, multiply method (a method with an immediate answer): **O(1) or constant**

### *Remember to take the most dominate term. If the loops are nested, multiply. If the loops are separate, add.*

## Basic Data Structures Descriptions and Typical Big O Analysis for their methods

### Arraylists/ Vectors <>
### Primitive Array []
### Binary Trees
### Heaps
### Stacks
### Linked List
### Doubly Linked Lists
### Circular Linked Lists
### Hash Tables
### Tries
### Graphs
### Hash Maps
### Hash Set
### Heaps


## Sorting Algorithms and Big O for each

### Insertion Sort

### Selection Sort

### Bubble Sort

### Quick Sort

### Merge Sort


## Searching Algorithms and Big O for each

### Breadth-First Search

### Depth- First Search

### Binary Search

### Linear Search















