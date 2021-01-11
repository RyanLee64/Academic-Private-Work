# Academic Work

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

1. Programming Project 1:
  * Calculate the number of hours for a given period of time.
  * Calculate the date of Easter for a given year.
  * Binary leap year detector.
  * *Grade 58/60*
  
 2. Programming Project 2: Checksum functionality for an inputted credit number based off of a set of      specified criteria.
   * *Grade 44/50*
   
 3. Programming Project 3: The game of Nim -- Nim has the player and computer each select marbles from a pile. The goal is to make your oponent take the final marble. 
  * For more on Nim check out [this](https://en.wikipedia.org/wiki/Nim) Wikipedia article
  * Two Way Postal Zip Code to Letter bar code translator. 
  *I have included an image from the Cay Horstman Big Java Early Objects 6e book to provide some context below.
  ![alt text](https://github.com/RyanLee64/Academic-Private-Work/blob/a33f59310d0e03d66478fd83a3019039d765f664/zip_to_bar.png)
  * *Grade 58/60*
  
4. Programming Project 4: Video Poker -- The player starts with 5 tokens and is allowed to bet up to 5 tokens in order to multiply their winnings *n* times. The player is dealt five cards. They are allowed to reject up to all five of the cards. They are then dealt cards to replace their rejected cards and the hand is then scored. For more on video poker check out [this](https://en.wikipedia.org/wiki/Video_poker) Wikipedia article.
  * *Grade 56/60* 
  
5. Programming Project 5: Talk Scheduler -- The scheduler takes a list of possible "talks" In Name: Start - End format and outputs the maximum number of talks possible to schedule as a subset of the original list.
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

1. Programming Project 1:
  * Create a *generic* rectangle class 
  * Implement a *generic* form of linear and binary search
  * Create objects with a given O(n^x) run-time specified by the user. We used the nanoTime method to confirm that these run-times were of the correct magnitude.
  * *Grade 47.5/50*
2. Programming Project 2:
  * Create a geneic implementation of a Stack
  * Use the stack to test for symbol imbalances in a file passed as a command line argument
  * Create a generic Queue out of two Stacks
  * Grade *56/60*
  
3. Programming Project 3:
  * Expression Tree Evaluator:
   The Expression Tree object takes an expression. There are accompanying prefix, infix, and postfix methods which recursively evaluate the expression in the specified order with the use of a stack.
   * Binary Search tree:
    The Better BST was an exercise in adding functionality to the BST class supplied by Proffesor Blaer -- so we added the funtionality to check the height, print the tree, etc. 
    * *Grade 36/65*
4. Programming Project 4:
  * Spell Checker: 
   We created a spell checker program built on upon a hash table. The file (dictionary) passed to the constructor is parsed into a HashSet. Using the getIncorrectWords method each word is compared against the values of the HashSet dictionary. There is also a suggestions method which when supplied with a word helps the user out by generating an ArrayList of possible words they meant to say.
   * K-Best Values: This was a classic exercise in finding the k(largest) values of a dataset. What made the exercidse a challenge were the runtime constraints put on our methods as well as the implementation of a priority queue as the underlying data strucure used to handle the input set.
   * *Grade 65/65*
 5. Programming Project 5: Dijkstra's Algorithm: this was the final programming project and it was really neat becasue wrapping my head around Dijkstra's in 1004 took a while but by this point I not only really througholy understood the use case for Dijkstra but also several other shortest path algorithms. Feeling comfortable programming this was really neat. We interacted with Dijkstra's through a GUI supplied by one of Professor Blaer's TAs that mapped out all of the major metros in the US. I personally for some reason was really struck by this. Getting to look at the source code made me less-intimidated about coding a GUI and was one of the inspirations for making a GUI for the Report Builder Helper I created for Social Standards.
  * *Grade 60/60*

### COMS 3137 -- Advanced Programming 
**Professor: Jae Woo Lee**  
**Semester: Fall 2020**

COMS 3137 is Columbia's systems course taught in C. This has been my favorite CS course so far. It lives rent-free in no Columbia CS student's mind. If you ever hop on r/Columbia, there is usually at least one student experiencing an AP [crisis](https://www.reddit.com/r/columbia/comments/jr7erc/surviving_advanced_programming_w_jae/).  AP is definetly the weeder course of the CS program. It is driven by a (pretty compelling) narrative described in Professor Lee's paper [**Follow the River and You Will Find the C**](http://www.cs.columbia.edu/~jae/papers/3157-paper-v2.2-camera-final.pdf). Each "lab" built on the prior and the final project had us create an HTTP server from scratch which both served static web pages as well as dynamically searched through a backend database of (name, message) pairs created by my 3137 section over the course of the semester. 

The course enviornment for this course was pretty neat as well. All of the students were assigned an account on a Linux server running Ubuntu Linux, 64-bit version. 

I learned a ton in this course. First off the enviornemtn forces you to get familiar with navigating a computer via a shell. It also forces you to get learn an editor like Vim. 

I think learning a low-level language was super beneficial to me. I am all about seeing the trees first (i.e. learning OOP) and then going deep on a subject. The syllabus is super succing and does a great job at succincely and comprehensively describing the topics covered, so I will put it below:

Unit 1: C programming basics

    UNIX CLI basics
    Compiling & linking
    Makefile
    Git
    Binary number
    Data types
    Expressions & statements
    Storage class
    Process address space

Unit 2: Pointers and arrays

    Pointers
    Arrays
    Pointers vs. arrays

Unit 3: Function pointers and structs

    Function pointers
    Struct
    Linked list

Unit 4: File I/O

    Standard I/O
    Redirection
    File I/O

Unit 5: UNIX processes, shell, TCP/IP
    
    Shell Scripting
    UNIX overview
    Creating processes using fork & exec
    Introduction to TCP/IP networking

Unit 6: Sockets API and HTTP

    Endianness
    Sockets API
    HTTP 1.0

Unit 7: Web-based software architecture

    HTTP 1.0 vs. HTTP 1.1
    3-tier architecture

*Below is a high level-overview of the 3137 Programming Projects and my raw grades on each project. In additiona to the five Programming Projects their are five Problem Sets for which I also have repositories (in this case if applicable some were completly on paper). Due to the fact that the problem sets have several very small pieces, I have not enumerated them below. To access any individual repositories that include the content and the class statistics please reach out to me at dbl2127@columbia.edu*  


1. Lab 1: Getting familiar with C and the Linux course enviornemnt. Simple average, prime, and decimal to binary convertor. The challenge was learning Vim, how to structure projects in the Linux enviornment, and learning the C syntax requisite to knock out what we needed to do.

* *Grade 100/100*

2. Lab 2: Sorting an integer array and writing the echo program to also capitalize each command line arg and write it next to the original arg in a descending list. The challenge of this lab was starting to wrap my head around memory managent as well as making a Makefile for a project with a little more robustness than Lab 1. We used valgrind to check for any and all memory leaks throughout the course.

* *Grade 100/100*

3. Lab 3: Implementation of a singly linked list and using our linked list to create an echo program which reverses the command line args passed to it. Essientally, we were provided with a pretty comprehensive list of functions we needed to build out in order to create our Linked List API. The linked list is the underlying data strucure for our message database and was this lab was the first super concrete building block in the creation of our HTTP server.

* *Grade 100/100*

4. Lab 4: There is a bit of background neccesary to understand what is going on with Lab 4. I have mentioned this message database of (name, message) pairs. This database is a binary, centralized database accesible to all 3137 students with each pair composed of a 40 character struct. Our task was to read the binary datatbase into a singly linked list and then returns the pairs which contain the substring specified by the user in either the name or message. This was a great exerciese in learning all about pointers, stucts, binary files, and more general File I/O. 

* *Grade 98/100*

5. Lab 5: Creating a hacky netcat server uisng a shell script to perform mdb-lookup and then using another shell script to create a less hacky netcat mdb-lookup server. Part 1 of Lab 5 was an exercise in using shell scripts, chaining programs together, and forking processes to create a desired result. The first part of the lab had us more or less create a shell scipt to wrap the command line arg we studied in class to run a mdb-lookup server using netcat. The second one has us wait for the forked process to return and continues running repeatedly instead of just once as in part 1. This was a great way to learn about the magic of pipes in [UNIX](https://www.youtube.com/watch?v=tc4ROCJYbm0) and learn about how to be a good steward of the fork/execl family of functions in orer to avoid fork bombing into oblivion. 

* *Grade 93/100*

6. Lab 6: Here we use the Sockets API in order to create an MDB-lookup server which listens on the specified port for input. Using netcat we were able to feed input which then needed to be sanitized and read from the file descriptor associated with the port. Part 2 of the lab had us created a limited version of the wget program. We created a program which connected to the public port of a web server (80 in nearly every instance in my testing) and read line by line from the socket the result of the resouce we were served by the web server on the other end. This data was then written out to a binary file whose name matched the resource specified at the end of the pathname. This was a great exercise in learning the underpinnings of the internet through the C sockets API. Part 2 was certainly limited in functionality comapred to fgets as it could only access pages conforming to HTTP not HTTPS. It also taught us about endianess and the importance of comforming to the HTTP protocol on our end. 

* *Grade 120/120*

7. Lab 7: This is the crème de la crème of AP assignments. The assignemnt is straightfoward but was crazy spooky at the start of the semester -- writing an HTTP server from scratch. This project was twofold. First we wrote a program which served static content. The program would accept connections serve the specified resource and then close the socket. The status was printed out to stdout. In order for a webpage to be fully served this process happened several times per page. We had to create a page. I made mine about my dog naturally. ![alt text](https://github.com/RyanLee64/Academic-Private-Work/blob/main/lab7_webpage.png)

The second part of the lab was in my opinion the coolest. We spooled up the backend lab 6 mdb-lookup server and then connected to it with our front end server. We then serve up a pretty simple table which allows for the user to input a lookup string. Upon entering the string the query is passed to the backend which then presses it to the frontend server which then dynamically serves it to the clinet -- chenqui. 

Lab 7 really brought the whole course all together. 

* *Grade 137/150*








 
  



