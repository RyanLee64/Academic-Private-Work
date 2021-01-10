# Academic-Private-Work

I have private repositories for all of my computer science coursework as well as for the templating based executable I created during my time with Social Standards. If you are a prospective employer and would like to access any of these private repositories or Github Gists please reach out to me at dbl2127@columbia.edu and I will respond promptly with links.

## Courses Taken 

### COMS 1004 -- Introduction To Computer Science/Programming in Java
**Professor: Adam Cannon**  
**Semester: Spring 2020**

COMS 1004 is Columbia's CS-1 course. The course objectives are to gain an understanging of:

*Fundamental Java programming skills  
*Knowledge of the fundamental concepts in computer science.  
*Algorithmic problem-solving capabilities.  

The course works its way up from translating trivial calculations into Java to building a few command line games (without GUIs) such as Nim and a modified version of video poker. By the end I walked away with a better understanding of how to integrate the Java API into my projects, organize and format my code, and solve problems iteratively.  

*Below is a high level-overview of the 1004 Programming Projects and my raw grades on each project. In additiona to the five Programming Projects their are five Problem Sets for which I also have repositories. Due to the fact that the problem sets have several very small pieces, I have not enumerated them below. To access any individual repositories that include the content and the class statistics please reach out to me at dbl2127@columbia.edu*  

1. 
  * Calculate the number of hours for a given period of time.
  * Calculate the date of Easter for a given year.
  * Binary leap year detector.
  * *Grade 58/60*
  
 2. Checksum functionality for an inputted credit number based off of a set of      specified criteria.
   * *Grade 44/50*
   
 3. The game of Nim: Nim has the player and computer each select marbles from a pile. The goal is to make your oponent take the final marble. 
  * For more on Nim check out [this](https://en.wikipedia.org/wiki/Nim) Wikipedia article
  * Two Way Postal Zip Code to Letter bar code translator. 
  *I have included an image from the Cay Horstman Big Java Early Objects 6e book to provide some context below.
  ![alt text](https://github.com/RyanLee64/Academic-Private-Work/blob/a33f59310d0e03d66478fd83a3019039d765f664/zip_to_bar.png)
  * *Grade 58/60*
  
4. Video Poker: The player starts with 5 tokens and is allowed to bet up to 5 tokens in order to multiply their winnings *n* times. The player is dealt five cards. They are allowed to reject up to all five of the cards. They are then dealt cards to replace their rejected cards and the hand is then scored. For more on video poker check out [this](https://en.wikipedia.org/wiki/Video_poker) Wikipedia article.
  * *Grade 56/60* 
  
5. Talk Scheduler: The scheduler takes a list of possible "talks" In Name: Start - End format and outputs the maximum number of talks possible to schedule as a subset of the original list.
  * *Grade 63/70* 
  
 
 ### COMS 3134 -- Introduction To Computer Science/Programming in Java
**Professor: Adam Cannon**  
**Semester: Spring 2020**

COMS 1004 is Columbia's CS-1 course. The course objectives are to gain an understanging of:

*Fundamental Java programming skills  
*Knowledge of the fundamental concepts in computer science.  
*Algorithmic problem-solving capabilities.  

The course works its way up from translating trivial calculations into Java to building a few command line games (without GUIs) such as Nim and a modified version of video poker. By the end I walked away with a better understanding of how to integrate the Java API into my projects, organize and format my code, and solve problems iteratively.  


### COMS 3134 -- Data Structures in Java
**Professor: The Legendary Paul Blaer**  
**Semester: Summer 2020**

COMS 3134 is Columbia's CS-2 course. The course objectives are to gain an understanging of:

Data types and structures: arrays, stacks singly and doubly linked lists, queues, trees, sets, and graphs. Programming techniques for processing such structures: sorting and searching, and hashing. Storage management. Design and analysis of algorithms. Taught in Java.

The course has more or less three chunks to it. The first unit had us analyze and learn about the analysis of iterative as well as recursive algorithms using Big-Oh notation and other forms of run-time analysis. We then dove into the data structures above and had programming projects which required the implementation of 1-2 of these data strucutres. Finally, we went thorugh different sorting and path algorithms such as: Selection sort, merge sort, Heap Sort, etc. and Prim's algorithm, Kruskal's algrithm, and reviewed Dijkstra's algorithm from 1004.  

I came out of this course with a far better understanding of the importance of writing succint code and how to analyze the computational expense of the code I develop. It also gave me an understanding of the role of inheretance and interfaces in OOP. I got way better at recursivley programming through the course, and I started to develop solid practices around handling and throwing exceptions that arise in my code. Finally, I learned about the Gypsy Kings -- BAMBOLEO.

*Below is a high level-overview of the 3134 Programming Projects and my raw grades on each project. In additiona to the five Programming Projects their are five Problem Sets for which I also have repositories (in this case if applicable some were completly on paper). Due to the fact that the problem sets have several very small pieces, I have not enumerated them below. To access any individual repositories that include the content and the class statistics please reach out to me at dbl2127@columbia.edu*  

1. 
  * Create a *generic* rectangle class 
  * Implement a *generic* form of linear and binary search
  * Create objects with a given O(n^x) run-time specified by the user. We used the nanoTime method to confirm that these run-times were of the correct magnitude.
  * *Grade 47.5/50*
2. 
  * Create a geneic implementation of a Stack
  * Use the stack to test for symbol imbalances in a file passed as a command line argument
  * Create a generic Queue out of two Stacks
  * Grade *56/60*
  
3.
  * Expression Tree Evaluator:
   The Expression Tree object takes an expression. There are accompanying prefix, infix, and postfix methods which recursively evaluate the expression in the specified order with the use of a stack.
   * Binary Search tree:
    The Better BST was an exercise in adding functionality to the BST class supplied by Proffesor Blaer -- so we added the funtionality to check the height, print the tree, etc. 
    * *Grade 36/65*
4. 
  * Spell Checker: 
   We created a spell checker program built on upon a hash table. The file (dictionary) passed to the constructor is parsed into a HashSet. Using the getIncorrectWords method each word is compared against the values of the HashSet dictionary. There is also a suggestions method which when supplied with a word helps the user out by generating an ArrayList of possible words they meant to say.
   * K-Best Values: This was a classic exercise in finding the k(largest) values of a dataset. What made the exercidse a challenge were the runtime constraints put on our methods as well as the implementation of a priority queue as the underlying data strucure used to handle the input set.
   * *Grade 65/65*
 5. Dijkstra's Algorithm: this was the final programming project and it was really neat becasue wrapping my head around Dijkstra's in 1004 took a while but by this point I not only really througholy understood the use case for Dijkstra but also several other shortest path algorithms. Feeling comfortable programming this was really neat. We interacted with Dijkstra's through a GUI supplied by one of Professor Blaer's TAs that mapped out all of the major metros in the US. I personally for some reason was really struck by this. Getting to look at the source code made me less-intimidated about coding a GUI and was one of the inspirations for making a GUI for the Report Builder Helper I created for Social Standards.
  * *Grade 60/60*

   
  





 
  



