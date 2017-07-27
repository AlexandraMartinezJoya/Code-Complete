# Code-Complete
-- In Progress -- 
# Textbook Examples mined from Code Complete.

# Chapter 1: Welcome to Software Construction

Key Points:

	* Software construction is the central activity in software development; construction is the only activity that's guaranteed to happen on every project.
	* The main activities in construction are detailed design, coding, debugging integration, and developer testing (unit testing and integration testing).
	* Other common terms for construction are "coding" and programming" . 
	* The quality of the construction substantially affects the quality of the software 
	* In the final analysis, your understanding of how to do construction determines how good a programmer you are, and that's the subject of the rest of the book.

# Chapter 2  - Metaphors for a Richer Understanding of Software Development

Key Points

	* Metaphors are heuristics, not algorithms. As such, they tend to be a little sloppy.
	* Metaphors help you understand the software-development process by relating it to other activities you already know about. 
	* Some metaphors are better than others
	* Treating software construction as similar to building construction suggests that careful preparation is needed and illuminates the difference between large and small projects
	* Thinking of software-development practices as tools in an intellectual toolbox suggests further that every programmer has many tools and that no single tool is right for every job. Choosing the right tool for each problem is one key to being an effective programmer. 
	* Metaphors are not mutually exclusive. Use the combination of metaphors that works best for you. 

# Chapter 3 - Measure Twice, Cut Once

Key Points

	* The overarching goal of preparing for construction is risk reduction. Be sure your preparation activities are reducing risks, not increasing them.
	* If you want to develop high-quality software, attention to quality must be part of the software-development process from the beginning to the end. Attention to quality at the beginning has a greater influence on product quality than attention at the end.
	* Part of a programmer's job is to educate bosses and coworkers about the software-development process, including the importance of adequate preparation before programming begins. 
	* The kind of project you're working on significantly affects construction prerequisites - many projects should be highly iterative, and some should be more sequential. 
	* If a good problem definition hasn't been specified, you might be solving the wrong problem during construction. 
	* If good requirements work hasn't been done, you might have missed important details of the problem. Requirements changes cost 20 to 100 times as much in the stages following construction as they do earlier, so be sure the requirements are right before you start programming. 
	* If a good architectural design hasn't been done, you might be solving the right problem the wrong way during construction. The cost of architectural changes increase as more code is written for the wrong architecture, so be sure the architecture is right, too. 
	* Understand what approach has been taken to the construction prerequisites on your project, and choose your construction approach accordingly.

# Chapter 4 - Key Constructor Decisions

Key Points

	* Every programming language has strenghts and weaknesses. Be aware of the specific strengths and weaknesses of the language you're using.
	* Establishing programming conventions before you begin programming. It's nearly impossible to change code to match them later.
	* More construction practices exist than you can use on any single project. Consciously choose the practices that are best suited to your project.
	* Ask yourself whether the programming practices you're using are a response to the programming language you're using or controlled by it. Remember to program into the language, rather than programing in it.
	* Your position on the technology wave determines what approaches will be effective - or even possible. Identify where you are on the technology wave, and adjust your plans and expectations accordingly. 

# Chapter 5. Design in Construction

Key Points

	* Software's Primary Technical Imperative is managing complexity. This is greatly aided by a design focus on simplicity.
	* Simplicity is achieved into two general ways: minimizing the amount of essential complexity that anyone's brain has to deal with at any one time, and keeping accidental complexity from proliferating needlessly. 
	* Design is heuristic. Dogmatic adherence to any single methodology hurts creativity and hurts your programs
	* Good design is iterative, the more design possibilities you try, the better your final design will be.
	* Information hiding is a particularly valuable concept. Asking "What should I hide?" settles many difficult design issues.
	* Lots of useful, interesting information on design is available outside this book. The perspectives presented here are just the tip of the iceberg

# Chapter 6 - Working Classes

In Chapter 6 The Topic Abstract Data Types and Interfaces are explained and we have the first code samples. The chapter is basically used as an introduction as abstract data type and should be treated as such, the examples which they are. 

Key Points

	* Class interfaces should provide a consistent abstraction. Many problems arise from violating this single principle
	* A class interface should hide something- a system interface, a design decision, or an implementation detail
	* Containment is usually preferable to inheritance unless you're modeling an "is a " relationship
	* Inheritance is a useful tool, but it adds complexity, which is counter to Software's Primary Technical Imperative of managing complexity.
	* Classes are your primary tool for managing complexity. Give their design as much attention as needed to acc

# Chapter 7 - High-Quality Routines

In Chapter 7, Routines are Explained in great detail, and as the cherry on the top, we have the first Ada example.  

Key Points

	* The most important reason for creating a routine is to improve the intellectual manageability of a program, and you can create a routine for many other good reasons. Saving space is a minor reason; improved readability, realiability, and modifiability are better reasons.
	* Sometimes the opperation that most benefits from being put into a routine of its own is a simple one
	* You can classify routines into various kinds of cohesion, but you can make most routines functionally cohesive, which is best
	* The name of a routine is an indication of its quality. If the name is bad and it's accurate, the routine might be poorly designed. If the name is bad and it's innaccurate, it's not telling you what the program does. Either way, a bad name means that the program needs to be changed.
	* Functions should be used only when the primary purpose of the function is to return the specific value described by the function's name.
	* Careful programmers use macro routines with care and only as a last resort. 

# Chapter 8 - Defensive Programming
In Chapter 8, The concept of Defensive Programming is explained in great detail. Some code samples are given for each subchapter, and we have the first Visual Basic example.

Key Points

	* Production code should handle errors in a more sophisticated way then "garbage in, garbage out" 
	* Defensive-programming techniques make errors easier to find, easier to fix, and less damaging to production code
	* Assertions can help detect errors early, especially in large systems, high-realibility systems, and fast-changing code bases
	* The decision about how to handle bad inputs in a key error-handling decision and a key high-level design decision
	* Exceptions provide a means of handling errors that operates in a different dimension from the normal flow of the code. They are a valuable addition to the programmer's intellectual toolbox when used with care, and they should be weighed against other error-processing techniques
	* Constraints that apply to the production system do not necessarily apply to the development version. You can use that to your advantage, adding code to the development version that helps to flush out errors quickly

# Chapter 9 - The Pseudocode Programming Process (PPP)
Chapter 9 explains in detail how to use Pseudocode practices

Key Points

	* Constructing classes and constructing routines tends to be an iterative process. Insights gained while constructing specific routines tend to ripple back though the class's design.
	* Writing good pseudocode calls for using understandable English, avoiding features specific to a single programming language, and writing at the level of intent (describing what the design does rather than how it will do it).
	* The Pseudocode Programming Process is a useful tool for detailed design and makes coding easy. Pseudocode translates directly into comments, ensuring that the comments are accruate and useful.
	* Don't settlefor the first design you think of. Iterate through multiple approaches in pseduocode and pick the best approach before you begin writing code.
	* Check your work at each step, and encourage others to check it too. That way, you'll catch mistakes at the least expensive level, when you've invested the least amount of effort.

# Chapter 10 - General Issues in Using Variables
Chapter 10 basically starts a new topics, and explains in depth the details of variables, from best practices of naming variables to general lifetime of a variable within a program

The Data Literacy Test

Put a I next to each term that looks familiar. If you think you know what a term means but aren't sure, give yourself a 0.5. Add the points when you're don, and interpret your score according to the scoring table below.

___abstract data type
___array
___bitmap
___boolean variable
___B-tree
___character variable
___container class
___double precision
___elongated stream
___enumerated type
___floating point
___heap
___index
___integer
___linked list
___named constant
___literal
___local variable
___lookup table
___member data
___pointer
___private
___retroactive synapse
___referential integrity
___stack
___string
___structured variable
___tree
___typedef
___union
___value chain
___variant

___Total Score

Key Points

	* Data initialization is prone to errors, so use initialization techniques described in this chapter to avoid the problems caused by unexpected initial values.
	* Minimize the scope of each variable. Keep references to a variable close together. Keep it local to a routine or class. Avoid global data
	* Keep statements that work with the same variables as close together as possible.
	* Early binding tends to limit flexibility but minimize complexity. Late binding tends to increase flexibility but at the price of increased complexity.
	* Use each variable for one and only one purpose 

# Chapter 11 - The power of Variable Names
Chapter 11 Goes into detail on naming variables, and explains general naming conventions. Examples are to be found

Key Points

	* Good variable names are a key element of program readability. Specific kinds of variables such as loop indexes and status variables require specific considerations.
	* Names should be as specific as possible. Names that are vague enough or general enough to be used for more than one purpose are usually bad names.
	* Naming conventions distinguish among local, class, and global data. They distinguish among type names, named constants, enumerated types, and variables.
	* Regardless of the kind of project you're working on, you should adopt a variable naming convention. The kind of convention you adopt depends on the size of your program and the number of people working on it.
	* Abbreviations are rarely needed with modern programming languages. If you do use abbreviations, keep track of abbreviations in a project dictionary or use the standardized prefixes approach
	* Code is read far more times than it is written. Be sure that the names you choose favor read-time convenience over write-time convenience. 

# Chapter 12 - Fundamental Data Types
Chapter 12 Explains Fundamental data types and shows tips and tricks on how to efficiently use them, as well as how not to.

Key Points

	* Working with a specific data type means remembering many individual rules for each type. Use this chapter's checklist to make sure that you've considered the common problems.
	* Creating your own types makes your program easier to modify and more self-documenting, if your language supports that capability
	* When you create a simple type using typedef or its equivalent, consider whether you should be creating a new class instead

# Chapter 13- Unusual data types
Chapter 13 Explains the unusual data types, and has a lenghtly disussion on structs, pointers and global data.


Key Points

	* Structures can help make programs less complicated, easier to understand, and easier to maintain
	* Whenever you consider using a structure, consider whether a class would work better
	* Pointers are error-prone. Protect yourself by using access routines or classes and defensive-programming practices 
	* Avoid global variables, not just because they're dangerous, but because you can replace them with something better
	* If you can't avoid global variables, work with them through access routines. Access routines give you everything that global variables give you, and more



# Chapter 14- Organizing Straight Line Code
Chapter 14 

Key Points

	* The strongest principle for organizing straight-line code is ordering dependencies.
	* Dependencies should be made obvious through the use of good routine names, parameter lists, comments, and - if the code is critical enough - housekeeping variables
	* If code doesn't have order dependencies, keep related statements as close together as possible



# Chapter 15- Using Conditionals

Key Points 

	* For simple if-else statements, pay attention to the order of the if and else clauses, especially if they process a lot of errors. Make sure the nominal case is clear
	* For if-then-else chains and case statements, choose an order that maximizes readability
	* To trap errors, use the default clause in a case statement or the last else in a chain of if-then-else statement
	* All control constructs are not created equal. Choose the control construct that's most appropriate for each section of code.



# Chapter 16- Controlling Loops

Key Points

	* Loops are complicated. Keeping them simple helps readers of your code
	* Technique for keeping loops simple include avoiding exotic kinds of loops, minimizing nesting, making entries and exits clear, and keeping housekeeping code in one place
	* Loop indexes are subjected to a great deal of abuse. Name them clearly, and use them for only one purpose.
	* Think through the loop carefully to verify that it operates normally under each case and terminates under all possible conditions.



# Chapter 17 - Unusual Control Structures
