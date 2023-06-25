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

Key Points 

	* Multiple returns can enhance a routine’s readability and maintainability, and they help prevent deeply nested logic. They should, nevertheless, be used carefully.
 	* Recursion provides elegant solutions to a small set of problems. Use it carefully, too.
  	* In a few cases, gotos are the best way to write code that’s readable and maintainable. Such cases are rare. Use gotos only as a last resort.

# Chapter 18 - Table-Driven Methods

Key Points

	* Tables provide an alternative to complicated logic and inheritance structures. If you find that you’re confused by a program’s logic or inheritance tree, ask yourself whether
 	you could simplify by using a lookup table.
  	* One key consideration in using a table is deciding how to access the table. You can access tables by using direct access, indexed access, or stair-step access.
   	* Another key consideration in using a table is deciding what exactly to put into the table.

# Chapter 19 - General Control Issues

Key Points

	* Making boolean expressions simple and readable contributes substantially to the quality of your code.
 	* Deep nesting makes a routine hard to understand. Fortunately, you can avoid it relatively easily.
  	* Structured programming is a simple idea that is still relevant: you can build any program out of a combination of sequences, selections, and iterations.
   	* Minimizing complexity is a key to writing high-quality code.

# Chapter 20 - The Software-Quality Landscape

 Key Points 

  	* Quality is free, in the end, but it requires a reallocation of resources so that defects are prevented cheaply instead of fixed expensively.
   	* Not all quality-assurance goals are simultaneously achievable. Explicitly decide which goals you want to achieve, and communicate the goals to other people on your team.
    	* No single defect-detection technique is completely effective by itself. Testing by itself is not optimally effective at removing errors. Successful quality-assurance
	programs use several different techniques to detect different kinds of errors.
 	* You can apply effective techniques during construction and many equally powerful techniques before construction. The earlier you find a defect, the less intertwined it will become 
  	with the rest of your code and the less damage it will cause.
   	* Quality assurance in the software arena is process-oriented. Software development doesn’t have a repetitive phase that affects the final product like manufacturing does, so the quality of the result
    	is controlled by the process used to develop the software.

# Chapter 21 - Collaborative Construction

Key Points

	* Collaborative development practices tend to find a higher percentage of defects than testing and to find them more efficiently.
 	* Collaborative development practices tend to find different kinds of errors than testing does, implying that you need to use both reviews and testing to ensure the quality of your software.
  	* Formal inspections use checklists, preparation, well-defined roles, and continual process improvement to maximize error-detection efficiency. They tend to find more defects than walk-throughs.
   	* Pair programming typically costs about the same as inspections and produces similar quality code. Pair programming is especially valuable when schedule reduction is desired. Some developers 
    	prefer working in pairs to working solo.
     	* Formal inspections can be used on work products such as requirements, designs, and test cases, as well as on code.
      	* Walk-throughs and code reading are alternatives to inspections. Code reading offers more flexibility in using each person’s time effectively.

# Chapter 22 - Developer Testing

Key Points 

 	* Testing by the developer is a key part of a full testing strategy. Independent testing is also important but is outside the scope of this book.
  	* Writing test cases before the code takes the same amount of time and effort as writing the test cases after the code, but it shortens defect-detection-debug-correction cycles.
   	* Even considering the numerous kinds of testing available, testing is only one part of a good software-quality program. High-quality development methods, including minimizing defects 
	 in requirements and design, are at least as important. Collaborative development practices are also at least as effective at detecting errors as testing, and these practices detect different kinds of errors.
  	* You can generate many test cases deterministically by using basis testing, data-flow analysis, boundary analysis, classes of bad data, and classes of good data. You can generate additional test cases with error guessing. 
   	* Errors tend to cluster in a few error-prone classes and routines. Find that error-prone code, redesign it, and rewrite it.
    	* Test data tends to have a higher error density than the code being tested. Because hunting for such errors wastes time without improving the code, test-data errors are more aggravating than programming errors. Avoid them by
	developing your tests as carefully as your code.
 	* Automated testing is useful in general and is essential for regression testing.
  	* In the long run, the best way to improve your testing process is to make it regular, measure it, and use what you learn to improve it.

# Chapter 23 - Debugging 

Key Points 

 	* Debugging is a make-or-break aspect of software development. The best approach is to use other techniques described in this book to avoid defects in the first place. It’s still worth your time to improve your debugging skills, how-
	ever, because the difference between good and poor debugging performance is at least 10 to 1.
 	* A systematic approach to finding and fixing errors is critical to success. Focus your debugging so that each test moves you a step forward. Use the Scientific Method of Debugging.
  	* Understand the root problem before you fix the program. Random guesses about the sources of errors and random corrections will leave the program in worse condition than when you started.
   	* Set your compiler warning to the pickiest level possible, and fix the errors it reports. It’s hard to fix subtle errors if you ignore the obvious ones.
    	* Debugging tools are powerful aids to software development. Find them and use them, and remember to use your brain at the same time.

# Chapter 24 - Refactoring

Key Points

 	* Program changes are a fact of life both during initial development and after initial release.
  	* Software can either improve or degrade as it’s changed. The Cardinal Rule of Software Evolution is that internal quality should improve with code evolution.
   	* One key to success in refactoring is learning to pay attention to the numerous warning signs or smells that indicate a need to refactor.
    	* Another key to refactoring success is learning numerous specific refactorings.
     	* A final key to success is having a strategy for refactoring safely. Some refactoring approaches are better than others.
      	* Refactoring during development is the best chance you’ll get to improve your program, to make all the changes you’ll wish you’d made the first time. Take advantage of these opportunities during development!

# Chapter 25 - Code-Tuning Strategies

Key Points 

 	* Performance is only one aspect of overall software quality, and it’s usually not the most important. Finely tuned code is only one aspect of overall performance, and it’s usually not the
  	most significant. Program architecture, detailed design, and data-structure and algorithm selection usually have more influence on a program’s execution speed and size than the efficiency of its code does.
   	* Quantitative measurement is a key to maximizing performance. It’s needed to find the areas in which performance improvements will really count, and it’s needed again to verify that optimizations improve 	rather than degrade the software.
    	* Most programs spend most of their time in a small fraction of their code. You won’t know which code that is until you measure it.
     	* Multiple iterations are usually needed to achieve desired performance improvements through code tuning.
      	* The best way to prepare for performance work during initial coding is to write clean code that’s easy to understand and modify.

# Chapter 26 - Code-Tuning Techniques

Key Points 

	* Results of optimizations vary widely with different languages, compilers, and environments. Without measuring each specific optimization, you’ll have no idea whether it will help or hurt your program.
 	* The first optimization is often not the best. Even after you find a good one, keep looking for one that’s better.
  	* Code tuning is a little like nuclear energy. It’s a controversial, emotional topic. Some people think it’s so detrimental to reliability and maintainability that they won’t do it at all. Others think 
   	that with proper safeguards, it’s beneficial. If you decide to use the techniques in this chapter, apply them with care.
    	
# Chapter 27 - How Program Size Affects Construction

Key Points 

	* As project size increases, communication needs to be supported. The point of most methodologies is to reduce communications problems, and a methodology should live or die on its merits as a communication 
 facilitator.
 	* All other things being equal, productivity will be lower on a large project than on a small one.
   	* All other things being equal, a large project will have more errors per thousand lines of code than a small one.
    	* Activities that are taken for granted on small projects must be carefully planned on larger ones. Construction becomes less predominant as project size increases.
     	* Scaling up a lightweight methodology tends to work better than scaling down a heavyweight methodology. The most effective approach of all is using a “right-weight” methodology.

# Chapter 28 - Managing Construction

 Key Points

 	* Good coding practices can be achieved either through enforced standards or through more light-handed approaches.
  	* Configuration management, when properly applied, makes programmers’ jobs easier. This especially includes change control.
   	* Good software estimation is a significant challenge. Keys to success are using multiple approaches, tightening down your estimates as you work your way into 
    	the project, and making use of data to create the estimates.
     	* Measurement is a key to successful construction management. You can find ways to measure any aspect of a project that are better than not measuring it at
	all. Accurate measurement is a key to accurate scheduling, to quality control, and to improving your development process.
 	* Programmers and managers are people, and they work best when treated as such.

# Chapter 29 - Integration

Key Points

	* The construction sequence and integration approach affect the order in which classes are designed, coded, and tested.
 	* A well-thought-out integration order reduces testing effort and eases debugging.
  	* Incremental integration comes in several varieties, and, unless the project is trivial, any one of them is better than phased integration.
   	* The best integration approach for any specific project is usually a combination of top-down, bottom-up, risk-oriented, and other integration approaches. T-shaped integration and vertical-slice
   	 integration are two approaches that often work well.
     	* Daily builds can reduce integration problems, improve developer morale, and provide useful project management information.
	
# Chapter 30 - Programming Tools

Key Points 

 	* Programmers sometimes overlook some of the most powerful tools for years before discovering them.
  	* Good tools can make your life a lot easier.
   	* Tools are readily available for editing, analyzing code quality, refactoring, version control, debugging, testing, and code tuning.
    	* You can make many of the special-purpose tools you need.
     	* Good tools can reduce the more tedious aspects of software development, but they can’t eliminate the need for programming, although they will continue to
	reshape what we mean by “programming.”

# Chapter 31 - Layout and Style

Key Points 

 	* The first priority of visual layout is to illuminate the logical organization of the code. Criteria used to assess whether that priority is achieved include accuracy,
	consistency, readability, and maintainability.
 	* Looking good is secondary to the other criteria—a distant second. If the other criteria are met and the underlying code is good, however, the layout will look fine.
  	* Visual Basic has pure blocks and the conventional practice in Java is to use pure- block style, so you can use a pure-block layout if you program in those languages. 
   	In C++, either pure-block emulation or begin-end block boundaries work well.
    	* Structuring code is important for its own sake. The specific convention you follow is less important than the fact that you follow some convention consistently.
	A layout convention that’s followed inconsistently can actually hurt readability.
	* Many aspects of layout are religious issues. Try to separate objective preferencesfrom subjective ones. Use explicit criteria to help ground your discussions about
style preferences.

 # Chapter 32 - Self-Documenting Code

 Key Points

 	* The question of whether to comment is a legitimate one. Done poorly, commenting is a waste of time and sometimes harmful. Done well, commenting is worthwhile.
  	* The source code should contain most of the critical information about the program. As long as the program is running, the source code is more likely than any
	other resource to be kept current, and it’s useful to have important information bundled with the code.
 	* Good code is its own best documentation. If the code is bad enough to require extensive comments, try first to improve the code so that it doesn’t need extensive comments.
  	* Comments should say things about the code that the code can’t say about itself—at the summary level or the intent level.
   	* Some commenting styles require a lot of tedious clerical work. Develop a style that’s easy to maintain.

# Chapter 33 - Personal Character

Key Points 

	* Your personal character directly affects your ability to write computer programs.
 	* The characteristics that matter most are humility, curiosity, intellectual honesty, creativity and discipline, and enlightened laziness.
  	* The characteristics of a superior programmer have almost nothing to do with talent and everything to do with a commitment to personal development.
   	* Surprisingly, raw intelligence, experience, persistence, and guts hurt as much as they help.
    	* Many programmers don’t actively seek new information and techniques and instead rely on accidental, on-the-job exposure to new information. If you devote a small percentage of your time to 
     	reading and learning about programming, after a few months or years you’ll dramatically distinguish yourself from the programming mainstream.
      	* Good character is mainly a matter of having the right habits. To be a great programmer, develop the right habits and the rest will come naturally.

# Chapter 34 - Themes in Software Craftsmanship

Key Points 

 	* One primary goal of programming is managing complexity.
  	* The programming process significantly affects the final product.
   	* Team programming is more an exercise in communicating with people than in communicating with a computer. Individual programming is more an exercise in communicating 
    	with yourself than with a computer.
     	* Team programming is more an exercise in communicating with people than in communicating with a computer. Individual programming is more an exercise in communicating with
      	yourself than with a computer.
       * Programming in terms of the problem rather than the solution helps to manage complexity.
       * Paying attention to intellectual warning signs like the “irritation of doubt” is especially important in programming because programming is almost purely a mental activity.
       * The more you iterate in each development activity, the better the product of that activity will be.
       * Dogmatic methodologies and high-quality software development don’t mix. Fill your intellectual toolbox with programming alternatives, and improve your skill at choosing the
       right tool for the job.

# Chapter 35 - Where to Find More Information

Key Points 
	More reading materials: 

 	Bass, Len, Paul Clements, and Rick Kazman. Software Architecture in Practice, 2d ed.
	Boston, MA: Addison-Wesley, 2003.

	Fowler, Martin. Refactoring: Improving the Design of Existing Code. Reading, MA: Addison-Wesley, 1999.

	Gamma, Erich, et al. Design Patterns. Reading, MA: Addison-Wesley, 1995.

 	Gilb, Tom. Principles of Software Engineering Management. Wokingham, England: Addison-Wesley, 1988.

  	Maguire, Steve. Writing Solid Code. Redmond, WA: Microsoft Press, 1993.

   	Meyer, Bertrand. Object-Oriented Software Construction, 2d ed. New York, NY: Prentice Hall PTR, 1997.

    	“Software Measurement Guidebook,” NASA Goddard Space Flight Center. Available from sel.gsfc.nasa.gov/website/documents/online-doc.htm

     	For more details on this professional development program, as well as for up-to-date reading lists, see our professional development website at 
      www.construx.com/professionaldev/.
	
       
       
