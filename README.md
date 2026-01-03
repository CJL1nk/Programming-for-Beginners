# CJ_Link Coputer Learn Guide

learn to use the 'puter

# L1 - Programming Basics

So you know next to nothing other than computer has a screen and does some cool stuff <br />
You made it here so I'm just gonna assume you at least know how to use that jawnson

Our very first step here is to learn the basics of programming, preferably in an easy language like [Python](https://www.python.org/downloads/) <br />
There's several other languages good for beginners but this is the best in my opinion <br />
**AS YOU INSTALL** There should be a box labeled "Add Python 3.x.x to PATH", I highly recommend checking this box as it'll probably help you out later down the road.

Next, we'll need an IDE, which is a little code area that'll help us edit, make, manage, and run our code and files. If you want something Python specific, you can use [PyCharm](https://www.jetbrains.com/pycharm/download/), however I recommend [Visual Studio Code](https://code.visualstudio.com/) as it's universal, fast, and really easy to use

Before we get started, keep in mind that this is more of a learning guide than a tutorial itself. There'll still be a good amount of mini lessons I'll teach and whatnot, especially in the first few lessons, however this is mostly meant to be self-paced and taught. Multiple resources for learning given topics are given at the bottom of each lesson. Don't let that turn you away though, as the resources and information you find here is more valuable than you'll likely find anywhere else.

This lesson should take ideally 3-4 weeks, at the very least 2-3.

### ----- What to learn (Ordered) -----
- Basic programming functions like printing, performing operations on numbers, user input
- If/Else statements
- Functions, parameters, arguments
- Variable data types like int, string, float/double
- Arrays
- Loops and the different ways they're utilized
- Variable scope
- Basic boolean algebra
- Basic understanding of documentation websites
- Basic problem breakdown and solving skills
- Read everything below, ESPECIALLY including ***How do I “Problem Solve?”***

---**What are these? (Also ordered)**---
* Basic programming functions are just the most commonly, easy to use coding functions. Things that let you add numbers, print stuff to the console, and let the user type things in.
* If/Else statements are used to make your program run different code based off given conditions. For example, if a number is less than 5, write "Hello" to console, else, if it's greater than 5, write "Goodbye" to console.
* Functions let you "save" a block of code and call it whenever desired, multiple times even. This is useful when you need to repeatedly do some specific instructions over and over again, and don't want to type the same thing out a few times.
* Variable data types are the type of data you're storing. For example, you couldn't have "B" in an integer variable because an integer only stores a number.
* Arrays allow you to store a collection of multiple values in a single variable. These values can then be accessed by asking the array for the value at some index.
* Loops continuously run the same block of code until a certain condition is met. For example, ask a user for a number until the number they enter is less than 10.
* The scope of a variable is the "region" of code a variable can be accessed by. Inside a function, we might have some variable named *color* which will not be accessible anywhere except that function it's defined in.
* Boolean algebra is a special type of math that deals with only True/False. It's more important later on, but is one of the foundations of computer science and engineering itself.
* Documentation websites are where you'll often find yourself when learning new programming languages or when using libraries. They tell you how the code works, how to use it, and any quirks it may have.
* Problem solving skills are explained below.

This will likely take a little while, don't just watch a video or two and have a basic understanding of their concepts. True understanding and knowledge comes through **experience**, which takes lots of **time**, **failure**, and **mistakes**, which we gain by doing **projects**. This lesson covers a LOT and should take a hefty amount of work and time, at the very **LEAST 2-3 weeks**.

This stage of your learning is hands down the most important part of your entire journey. Without a very strong understanding of the **fundamentals of programming itself**, you won't be able to get anywhere on your own. Keep in mind the fundamentals are significantly different and more important than the programming language itself. Things like real problem solving skills and the ability to break a problem down into individually solvable parts are incredibly useful, impossible to move on without. As tedious and boring as it might get, I can't reiterate enough that you need to **REALLY TRULY** understand these first few lessons, to the point of where any project or problem could be provided to you within your skill level and you should be able to pull it off within a **reasonable amount of time** with minimal problems.

One thing I will note, very early on, is that AI chatbots like ChatGPT, Grok, Claude, or whatever else you might use have the ability to generate code for you. I **STRONGLY** advise against this as a beginner, as it **will** get you almost nowhere and you'll end up missing many of the basic **problem solving** skills that come along with programming. If you're truly stuck, I say it's okay to ask it where a bug might be happening in your code as it can be useful to identify things like that, however keep in mind that mistakes are very common from the AI and a good percentage of the time, code that's generated often won't work as expected, or won't work at all. AI is a useful tool, but should never be fully relied upon to do a task for us. It will **only** work early on, as once we start getting to the super cool low-level stuff, it often miserably fails. We **MUST** understand how, and why the code it gives us works (or doesn't!!).an't explain the difference between the Stack and Heap in memory. Computer Science extends far beyond just programming, it's the study of computation itself. Knowledge beyond just how to write a program goes a LONG way, as computers are highly complex systems and understanding quite literally everything about them down to a microscopic level is necessary to really make your skills useful. It won't be easy at all, I won't deny that, but the willpower to actually pull through despite all that is necessary. Long story short, Computer Science is far more complex than it may seem and studying this type of thing is ONLY worth it if you have the true desire to learn and have **real passion** for this kind of stuff. If you're going the college route, I'd say make SURE you pick a college with a good program because there are a LOT of colleges out there with some terrible CS programs where nothing you learn will really be that useful and that won't take you very far unfortunately.

### ----- How do I "Problem Solve?" -----

Problem solving is a widely undiscussed aspect of programming, which is why I'm writing a mini lesson on it here. For the most part, this skill should develop naturally with time and experience but it's good to read a bit about it,

So what's even meant by problem solving? We can all solve problems can't we? Most of us probably wouldn't even be here if we didn't have SOME form of these skills right? Well, though those questions may be correct, they may not be as strong as you think they are, no offense intended.

For your first little exercise, imagine yourself as the developer of a little 2D mobile game. The game's nothing super serious, but the general idea for it is for you to be able to build your own terrarium and decorate it with your own plants, soils, bugs, animals, and whatever else might be included in a terrarium. You probably already have some more advanced ideas for this game, which is great, **creativity goes a LONG way** in programming. Now, I want you to think, what's the VERY FIRST, absolutely most basic thing you need to get done once you start coding your game. Some common answers to this are getting a terrarium on screen, making plant models, or making moving bugs. While these aren't exactly bad answers, they're not exactly as simple as they might seem. What do we need that's even more simple than that? If you guessed a window that we can even display stuff on, congratulations, you're already figuring it out better than 90% of most beginners. The VERY first thing we need is a little window we're able to even draw or display stuff on in the first place. From there, what's the next step? Well, the whole idea of having this window is to display stuff, so let's try drawing a line, or perhaps a square on the screen. From there, we can make the square move from left to right. Then we can draw a little box around our square, our first little "terrarium." As time goes on, we keep building up and up, making our little box slightly more and more complicated until we finally have something that resembles a terrarium, dirt, little bugs, and so on.

If you haven't caught on already, the point to this lesson is to teach that in programming, it's far too easy to try and start out too big. If we tried to start out by making moving bugs and plants that would grow as time went on, we probably would have to end up changing a LOT of their code in the future, assuming we even got that far in the first place. If we had their textures, models, and even some code that could be usable, what would we use them on? We have no window to render these plants, no physics engine, and not even and object system in place. You can't start building a skyscraper from the top. Never forget how important it is to start small and simple, to break your idea down into its smallest most simple parts and start putting it together and solving each sub-problem first.

### ----- Project Ideas -----

So you've developed a pretty basic understanding of programming. You know how to write little functions that do simple things like add, or print a user's name based off some given input. Now your task is to make some mini projects to develop your skills. You'll quickly discover that it's pretty hard to come up with project ideas, which is something I'd say you can ask AI to give you some ideas on, so here's a list of some little project ideas for your skill level. The goal behind all of these is to utilize almost everything you've learned so far, as well as to help develop a deeper understanding of how they work and identify any weird quirks they may have. We, as humans, learn by repetition so personal projects are **VERY** important in your learning.

- Command Line Calculator, which prompts the user for an operation (add, subtract, multiply, divide) and 2 numbers to perform the operation on. The program should then print the output to the console and continue asking for an operation until the user enters "Q" or some other option to exit.
- Fizzbuzz, a classic beginner programming challenge. Given a user entered integer **n**, for every positive integer **i <= n**, the task is to print "Fizz" if the number is divisible by 3, "Buzz" if it's divisible by 5, and "Fizzbuzz" if it's divisible by both 3 and 5.
- Find largest number, which repeatedly prompts the user for a number until they enter a negative integer. From there, it should print out the sum of every integer entered as well as the largest, and maybe even smallest numbers entered. There are multiple ways to solve this one, try to start doing so by using an array, then explore other options.
- Mad Libs generator, which asks the user for a series of nouns, verbs, adjectives, etc... and inserts them into a potentially funny story. [Mad Libs](https://en.wikipedia.org/wiki/Mad_Libs)
- Number guessing game, which asks the user to enter a number between 1-100. If the number is too low, it prints "Too low" and if it's too high, it prints "Too high." Once they guess the correct number, start again with a new one.

Early on, especially in these first few lessons, the projects we make won't really have any real-world use. I know, it's boring, but it's still **essential** to do and understand them. Given you have the motivation to do that, quicker than you can even realize, you'll have real, useful, cool projects which can range from things like websites to even complex simulations.

### ----- Resources -----

One of the hardest parts of learning how to program is **learning how to learn in the first place**. It's really easy to just search up some YouTube videos and say you've learned a lot when in reality, you don't know as much as you think. It's far too easy to understand something conceptually, but completely have no idea what you're doing once a task is actually given to you. Below is a list of resources to help you get started. I recommend if there's anything you run across in here that you don't know how to read or aren't sure what it means/does, please take the time to look into it and figure it out.

- [Python For Beginners](https://www.python.org/about/gettingstarted/)
- [CodeAcademy](https://www.codecademy.com/learn/learn-how-to-code)
- [W3Schools](https://www.w3schools.com/) (My king <3)
- [GeeksForGeeks](https://www.geeksforgeeks.org/)
- [RealPython](https://realpython.com/)
- [LeetCode](https://leetcode.com/)
- [(Video) 12 Hour Python Course](https://www.youtube.com/watch?v=ix9cRaBkVe0) (Please don't just watch this and assume you know everything)
- [(Playlist) Another Good Python Course](https://www.youtube.com/watch?v=mRMmlo_Uqcs&list=PLIhvC56v63ILPDA2DQBv0IKzqsWTZxCkp)
- [Boolean Algebra Basics](https://www.allaboutcircuits.com/technical-articles/boolean-basics/)
- [(Video) Boolean Algebra in 13 Minutes](https://www.youtube.com/watch?v=cTjFy18SjRc)
- [Python Documentation](https://docs.python.org/3/)
- [(Playlist) Hardvard CS50 courses](https://www.youtube.com/watch?v=h6lqxDwUmJQ&list=PLhQjrBD2T383q7Vn8QnTsVgSvyLpsqL_R) (Hard for beginners, good material though)
- [StackOverflow](https://stackoverflow.com/questions) (Use this as a last resort for questions, sometimes people's solutions are a bit bogus and rude)

# L2 - Improving our skills

Wow, we've made it this far, farther than most people really. By now, you should  have spent at least a couple weeks learning and writing mini programs and maybe even gone beyond. Ideally you should already know some of the stuff in here. This lesson is mainly focused on extending your Python skills and learning how to utilize some of the more useful features of the language, as well as getting comfortable with new workflow environments.

This lesson should take approximately 1-2 weeks.

### ----- What to learn (Ordered) -----
- File importing and multi-file programs
- File reading and writing
- Using files to store data
- String manipulation methods
- Error handling
- Edge cases
- Basic command line commands
- Package installation with pip
- Using packages and modules
- Documentation reading and writing
- Git and GitHub

---**What are these? (Also ordered)**---
* File importing lets you use functions written in other files. This is very helpful for organizing your code.
* File reading allows us to read data from a file for our program to use, and file writing allows us to write data. This is incredibly useful for things like game save files or storing other data we might want to save across sessions.
* Python provides us with lots of different functions to manipulate, cut, concatenate, edit, and reads strings. These are incredibly useful to learn earlier on.
* Error handling is how we deal with errors that might happen in our code. An example of this is someone typing in some bogus into our menu like "rgtsrgsdf" when the options are numbers from 1-5. We need to be able to handle this and tell them it's an invalid option, or deal with it and move on with some default value instead of our program just crashing.
* Edge cases are odd, out of the ordinary values our program might receive from the user or anywhere else that might be returning some value. For example, we have a program that asks us to enter 2 numbers to determine which one is greater. What happens if they're the same number? What happens if one of them is extremely huge, or extremely small? What happens if somehow the user enters a null value?
* The command line is your little terminal where you type in commands. This is arguably one of the most important things to learn early because you don't wanna be stuck as what I like to call a "clicker."
* PIP is the default python package installer. It allows you to download packages or libraries, which are often large organized collections of code (or "modules") written by other people made to perform a variety of specific, related functions.
* Packages, modules, and libraries all mean basically the same thing in this context. It's very common to need to use other people's libraries to assist in writing your own code.
* As explained before, documentation is how we keep track of our code in English, writing out what it does, how it works, how to use it, and what to expect from it.
* Git is a command line application that lets us track the version history of our code. GitHub is a place where we can upload Git repositories, which are the collections of our code bases. This allows us to track progress and past versions of our code, as well as acts as an online backup just in case we somehow lose it. There are other Git hosting services such as GitLab, SourceForge, Amazon AWS CodeCommit, and others, however GitHub and GitLab are the two mainstream ones.

One thing I wanna go over right away is how important learning how to write clean, organized, and well documented code is in this phase. It's really easy to be mindlessly writing code without thinking about how readable it is or how well it might be optimized. Whether you believe it or not, you **will** eventually forget exactly how some parts of your programs work and if there's no comments explaining anything and the code is messy, written like a bowl of noodles, you'll have a hard time figuring out what exactly does what and how things are linked together. As a result, this makes maintaining, expanding, and updating your code significantly harder.

Another thing I think is important to learn somewhat early on is how to actually use the command line. At first sight it's a pretty scary thing, a lot of people view it as a dangerous section of your computer that you should never touch to avoid screwing something up. While this is kind of true to some degree, it's nearly impossible to do, especially on windows, without a good amount of knowledge and luck. In order to screw something up, it HAS to be intentional, so you probably won't need to worry too much. The reason I think it's such an important thing to learn now is mainly because of Git, as the commands you'll be running are all through the terminal unless you use something like GitHub desktop. On top of that, basic knowledge of it is necessary for more advanced programming languages like C++, which we'll learn a little later down the road. It's also very common for servers to run on Linux distributions that are terminal only, meaning there's no user interface or anything you can click on. This might seem a little silly at first, but you'll understand a little better later on once we learn how servers work and how resource intensive having a GUI could be. Bottom line, get comfortable with the command line, it's not as scary or hard as it might seem at first.

The final topic I wanna go over here is edge case handling. As mentioned before, edge cases are odd values that we might not exactly expect our program to receive which end up breaking things. It's easy to say something like "oh well whoever's using my program shouldn't be doing stupid inputs with it in the first place," and while you aren't exactly wrong, it's still not very good practice to just let these slip by. There are many, many instances where edge cases will arise from non user-entered values and our edge cases are completely normal values that we would expect to receive. That's why it's so important to handle, especially in large complex systems where a single error could shutdown an entire city. (Thanks Cloudflare)

### ----- Project Ideas -----

We've finally moved onto slightly more advanced projects yippee!! From here on out, each of these projects will likely take a bit longer and require more thinking and troubleshooting. Don't let that demotivate you though, as that's really, truly, the only way to get better. I also recommend practicing writing cleaner, more organized code as you work on these projects. Be sure to handle any errors or edge cases that may occur so your program doesn't crash or break.

- Clean up old code. Look through some of your past projects and see how you can clean, document, and potentially maybe even optimize some of the past programs you've written. This is a very common thing to need to do, so getting some practice in now never hurts.
- Use a library like [Matplotlib](https://matplotlib.org/) to display some type of statistics of your choice.
- Write a note taking app, which allows you to save notes with a title, an actual note itself, and an automatically determined date. Upon opening, a menu should be displayed asking the user if they want to write a note or open a note. If they choose to write a note, they enter a title and the note itself, which then gets saved to a file along with the date. If they choose to open a note, the title and date of every note they have written will display on screen, bonus points if you have a preview of the note itself. They can then choose to display a note by typing in the title.
- Use a package like [pytube](https://github.com/pytube/pytube) or similar to allow users to easily download files from YouTube, given some video link.

### ----- Resources -----

* [Teclado importing tutorial](https://teclado.com/30-days-of-python/python-30-day-18-imports/)
* [(Video) Tips to organize Python code](https://www.youtube.com/watch?v=e9yMYdnSlUA)
* [(Video) How to structure your code](https://www.youtube.com/watch?v=6OSpm4uXqDw)
* [JSON Tutorial](https://www.w3schools.com/js/js_json_intro.asp)
* [W3Schools String Methods](https://www.w3schools.com/python/python_ref_string.asp)
* [(Video) Error handling](https://www.youtube.com/watch?v=Xe-oxpOWeE0)
* [(Video) Edge cases](https://www.youtube.com/watch?v=ZDfP3ZCaZMc)
* [Windows Terminal Documentation](https://learn.microsoft.com/en-us/windows/terminal/)
* [(Video) How to use the Windows terminal](https://www.youtube.com/watch?v=qnB044mHixc)
* [Linux Terminal Documentation](https://linuxcommand.org/lc3_man_page_index.php)
* [PIP Documentation](https://packaging.python.org/en/latest/tutorials/installing-packages/)
* [(Video) External libraries](https://www.youtube.com/watch?v=gzsgtLMK1O0)
* [(Video) How to document your code](https://www.youtube.com/watch?v=L7Ry-Fiij-M)
* [How to write good code documentation](https://guides.lib.berkeley.edu/how-to-write-good-documentation)
* [W3Schools Git tutorial](https://www.w3schools.com/GIT/) (Again please learn how to use this site it's AMAZING)
* [(Video) Git and GitHub tutorial](https://www.youtube.com/watch?v=RGOj5yH7evk)
* [GitHub Docs](https://docs.github.com/en/get-started/start-your-journey/hello-world)

# L3 - Objects and Basic Algorithms

So we know the basics of programming and hopefully how to not write ugly messy code. We've written some basic programs, probably not SUPER useful but by now we're starting to see some ways we might actually be able to use our skills. In this lesson, we're learning about Objects, which you may have already naturally learned some things about. Objects are one of the most useful things you'll ever use, and some form of creating them is included in almost every single programming language out there. On top of that, we'll start to look at some basic algorithms that will be the building blocks of some more advanced topics later down the road.

This lesson should take approximately 2-3 weeks.

### ----- What to learn (Ordered) -----
- Classes (or Objects)
- Class methods
- Object Oriented Programming
- Dictionaries (Hashmaps)
- JSON
- Bubble Sort, Insertion Sort, and Selection Sort
- Recursive functions

---**What are these? (Also ordered)**---
* Classes are a way to store what we call "Objects" in programming. A single object represents an entity with its own attributes and methods, meaning it can have multiple of its own variables and functions. An example of this would be creating a Person class, where it has a name, birth date, weight, height, and might have some functions like eat() that increase the person's weight. We can then create multiple instances of this person class, so we could have Person1, Person2, Person3, etc.. all with their own names, heights, weights and so on.
* Class methods are functions within a class designed to perform specific functions on its parent class. Usually they involve simply modifying or returning values, but can be used in other clever ways too.
* Object oriented programming (OOP) is the concept of designing our programs around objects.
* Dictionaries (or Hashmaps in other languages) are a way of associating 2 pieces of data together. For example, we could have a dictionary containing a class's grades. Each item in this dictionary has a key and a value, and in this case we'd see relationships like {"John": 85.3} or {"Martha": 92.0} where the key is the person's name and the value is their grade. We can then just access the dictionary by the persons name and immediately retrieve their grade. Unlike arrays, we can instantaneously access a key without having a search through the entire collection.
* JSON is a format that's commonly used to store various types of data. It's easy to understand and efficient, making it useful to store and retrieve somewhat large amounts of data.
* Bubble Sort, Insertion Sort, and Selection Sort are 3 of some of the most basic sorting algorithms. Sorting algorithms look at a collection of comparable objects, usually integers, and sort them from smallest to largest. These three are some very basic ones, however we'll look at some more complex, faster ones when we get into algorithms and data structures.
* Recursive functions are functions that call themselves one or more times.

### ----- Project Ideas -----

With objects and classes finally out of the way, we've finally learned some of the most useful features of programming. Of course, these features aren't very useful to us unless we practice and make good use of em, so get to work and make some cool stuff. Be sure to handle any errors or edge cases that may occur so your program doesn't crash or break.

- Employee database, which contains a class Employee that holds the employees name, address, and phone number. Each employee is saved into a dictionary {EmployeeID: Employee} which is saved to a json file. Upon start, the program should load all the current employees from the json into the employees dictionary, and employees should be able to be added or removed.
- Fibonacci sequence generator, which generates and prints the first n bits of the Fibonacci sequence using a recursive function.
- Receipt generator, which lets a user pick out multiple items from a store all with their own unique names, prices, and item IDs and generates a formatted receipt with the total + tax. The receipt should then save to a file and the user should be able to view old receipts they had checked out in the past.
- Write a sorting algorithm, one of the three basic ones we learned about here. If possible, try and discover any small optimizations you could add to the algorithm for best running time.
- Leetcode!!! They're not always the most fun, but see if you can solve Leetcode problems. They're incredibly useful for learning how to use, and optimize, our algorithms.

### ----- Resources -----

* [W3School Python Classes Tutorial](https://www.w3schools.com/python/python_classes.asp)
* [Python Classes Documentation](https://docs.python.org/3/tutorial/classes.html)
* [(Video) Python OOP Tutorial](https://www.youtube.com/watch?v=ZDa-Z5JzLYM)
* [(Video) Object Oriented Programming](https://www.youtube.com/watch?v=pTB0EiLXUC8)
* [W3Schools Dictionaries Tutorial](https://www.w3schools.com/python/python_dictionaries.asp)
* [(Video) Working with dictionaries](https://www.youtube.com/watch?v=_5BQaRuucTY)
* [(Video) Sorting with Selection, Bubble, and Insertion Sort](https://www.youtube.com/watch?v=HGk_ypEuS24)
* [(Video) Selection and Bubble Sort](https://www.youtube.com/watch?v=ev8mz3p90g8)
* [Sorting Algorithms](https://www.geeksforgeeks.org/sorting-algorithms/)
* [W3Schools Recursion](https://www.w3schools.com/python/gloss_python_function_recursion.asp)
* [(Video) Recursion](https://www.youtube.com/watch?v=m1Fjdnj_Mds)

<br>

## !! STOP !! : Breakpoint

From here, there's a few different routes you can go. I would **always** recommend you just read this document from the top down, as it teaches things in what I believe to be the correct priority however if you'd like to skip ahead, you can. Starting in the next lesson, we'll be diving into the low-level aspects of computers and writing some code "more close to the cpu." This is definitely where things can start getting pretty hard, however, **real-world useful knowledge** will start to come to fruition. If you're less interested in this side of computers, that's okay, it isn't *completely* necessary knowledge to dive into some other Computer Science aspects, however it's quite useful and will **often lead to much better-written and optimized software**. Along with this, there are things we call "black boxes" in programming. If you haven't heard of that term already, it's a general term for some function, library, or any interface where we feed it input, and it gives us output without us knowing what's going on behind the scenes. Often times, it's **very** important to know *exactly* what the interfaces we use are doing, whether it's some simple function or an entire piece of software. Without knowing low level computing, there will be a LOT of stuff remaining as black boxes to you which could **very well** lead to your detriment. Nevertheless, here's a list of topics you're free to skip to if you feel interested:

- [Websites](#l100---html-and-css)
- [Databases](#l200---databases) (Generally used WITH websites)
- [Networking Basics](#l300---networking-basics)
- [Linux](#l400---linux)
- [Server Systems](#l500---server-systems) (Tends to heavily rely on knowledge from previous 4 links)
- [Programming Languages](#l600---programming-languages) (Not all will really make sense unless you learn low-level)



# L4 - Binary and Hexadecimal

After what seems like absolutely FOREVER (hopefully) we've finally gotten to the point of where we can do most "simple" tasks that are given to us. You understand the basics of programming and can likely start to understand how larger scale apps, websites, and games might work. As awesome as this is, we still have a LOT more to learn, and this is where we start learning the actual really cool, fun stuff. At least in my opinion anyway. If you haven't researched it already, you're likely wondering how parts of our programs actually work, and what's going on behind the scenes. All we see is some English text and numbers on a screen, but how does a computer actually make sense of all that? In this lesson, we'll be looking at binary and hexadecimal and the math behind them, which are 2 of the key number systems to learn to understand the workings of computers.

This lesson should take no more than a couple days probably.

### ----- What to learn (Ordered) -----
- Binary and Decimal
- Converting Binary to Decimal
- Counting with any base
- Hexadecimal
- Binary addition, subtraction, and multiplication

---**What are these? (Also ordered)**---
* Binary are those silly 1s and 0s you see when people are talking about computers. Binary is essentially just counting in base 2, which is perfect for our computers because the electronics operate in 2 states, on or off. With binary, we can represent any type of data we want and use it in incredibly clever ways to make our computers do whatever we want.
* Binary can be converted to Decimal, our number system, pretty easily. It's simply converting base 2 to base 10.
* Number systems can be in any base, where the base is the number of different values each place in the number can be. Binary is base 2, so each place can either be 1 or 0. Decimal is base 10, so each place can be from 0-9, 10 total digits. Hexadecimal is base 16, so each place can be 0-F, where we count 1, 2, 3, ... , 8 , 9, A , B, C, D, E, F, a total of 16 values.
* Just like the decimal system, we can do simple math functions in binary, almost even easier than in decimal.

### ----- Project Ideas -----
There aren't really many projects you could really do with this information, but I'll assign some practice stuff. You can use online converters to check your work.
* Convert 16 and 55 to binary, then add them together.
* Convert 78 to binary, then to hexadecimal.
* Convert E6 from hexadecimal, to binary and decimal.
* Convert 1064 to binary and multiply it by 2 (There's a special little secret to this one !! Find it somewhere in [here](https://www.sciencedirect.com/topics/engineering/binary-multiplication))
* Convert 5F and 19 to binary and subtract them

### ----- Resources -----
* [Introduction to Binary](https://www.cmu.edu/gelfand/lgc-educational-media/digital-education-modules/dem-documents/new-the-world-of-the-internet-handouts.pdf)
* [(Video) How to Convert Decimal to Binary](https://www.youtub.com/watch?v=C5EkxfNEMjE)
* [Binary Multiplication](https://www.sciencedirect.com/topics/engineering/binary-multiplication)
* [What is Hexadecimal](https://www.techtarget.com/whatis/definition/hexadecimal)
* [(Video) How to Convert Hexadecimal to Decimal](https://www.youtube.com/watch?v=pg-HEGBpCQk)
* [Number in Different Bases](https://mathcenter.oxford.emory.edu/site/math125/bases/)

# L5 - Basic C++ and Memory
Now that we have a basic understanding of binary and hexadecimal, we can finally move on to our next programming language. You may have heard scary things about C++ with how hard and different it is, but after a bit of practice and understanding of how the language and computers work, it becomes a breeze.

To start off with C++, we'll need a slightly more complex IDE. You can use VSCode, but I highly advise against it because that's like using Windows Notepad for Python. I recommend for beginners you use [CLion](https://www.jetbrains.com/clion/download/#section=windows), however you can also use [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) which is a bit more complex.

Next, we'll need a **compiler**, which is what translates our code into machine code, something our computer can actually execute. I'm not gonna explain too much now because it gets a bit complicated, but we'll use [GCC](https://sourceforge.net/projects/mingw/files/Installer/mingw-get-setup.exe/download).

I highly recommend watching step by step tutorials for learning how to install things correctly, which I will link below in resources.

A lot more command line knowledge is gonna be needed from here on out, so I recommend if you're a bit rusty or didn't learn it very well in  the first place, you backtrack a bit and clean up your knowledge.

This lesson should take 3-4 weeks.

### ----- What to learn (Ordered) -----
- Basics of C++, listed below
- Declaring variables, variable data types, constants, performing basic operations like addition, subtraction, and so on
- If/Else statements
- Functions, return types, parameters and arguments
- Loops
- Basic arrays and their limitations
- Printing to console with cout
- Inputting with cin
- Structs
- Header files
- The C++ compiler
- Compilers vs Interpreters
- RAM and how it's used
- Unsigned vs signed integers
- Two's complement binary, (Signed integers)

---**What are these? (Also ordered)**---
* C++ is a **low level language**, meaning it works much "closer" to the computers hardware. It gets translated, or in this case, "compiled," directly into machine code that our computers can execute. You'll see this in the form of an exe, which is simply just an executable file.
* We already know what variables are, however in C++ they're a little bit different. We **need to declare a data type** for each variable like int, double, bool, string, and so on. As expected, integer variables cannot hold strings, and double, or "float" variables can't hold a boolean. **Each variable can only hold the data type it was originally declared to have**.
* If/Else statements work basically just like they do in Python, and let our code make decisions based off given conditions.
* Functions are also very similar to Python, however in C++ they have a **return type**. If they return an integer, the return type must be int, and if they return nothing, they have what's called a **void** return type.
* Loops are also very similar to how they work in Python, however for loops have slightly different syntax.
* Default arrays in C++ must have a declared size. The total number of items in the array cannot exceed this size, and our program will crash if it does. This problem is fixed with **vectors**, which are arrays with practically infinite size but we'll take a look at those once we move into more advanced C++.
* Instead of using print() like in Python, we use cout, the C++ standard output stream which lets us easily concatenate and output things to the console.
* Instead of using input() like Python, we use cin instead.
* Structs are a very basic implementation of objects, derived from C. They allow you to create a piece of data containing multiple variables to describe that data.
* Header files, in C++, are files that we use to declare the functions and global variables so they can be used across other files. We might have some file called math.cpp, whose functions are built to be used by other files, so we'd create an associated header file called math.h and put our function definitions in there. This allows us to import math.h and use those functions in other files like main.cpp by giving the compiler necessary information to link function calls back to that header file.
* The compiler looks at our code and translates it into machine code, which is read by us humans in the form of **Assembly**. This will produce an executable file for us to click and run. On the other hand, an interpreter, which is what Python uses, interprets and executes our code line by line.
* Our computers need some way of actually storing all the numbers and letters we're seeing on screen, as well as all the instructions written in our code. It stores most of this in the RAM (Random Access Memory), in the form of binary or hexadecimal. Different data types take up different amounts of space. For instance by default, an integer variable takes up 32 bits, or 4 bytes, in memory.
* Unsigned integers are integers that cannot be negative, and will roll back to 0 once they hit their size limit. Signed integers, on the other hand, can be negative, and will roll to it's lowest value when they hit their size limit.
* Two's complement is the method we use to store negative numbers in binary. Not a super deep understanding of this is required just yet, but it's a good thing to know.

This probably seems like a LOT to learn, and trust me, it is. We're entering almost a whole new world of computers here so don't expect it to be easy. It **WILL** be frustrating, we've all been there before. There will be multiple times where you feel absolutely stuck or like nothing is making any sense and that's completely normal. Don't be afraid to step back backtrack a little if there's a concept you aren't quite understanding or seem to be too advanced. But please do remember, you have infinite resources on the internet and even me if you get stuck, so feel free to contact if you have any questions :)

### ----- Project Ideas -----

With basic knowledge of objects finally out of the way, we've finally learned some of the most useful features of programming. Of course, these features aren't very useful to us unless we practice and make good use of em, so get to work and make some cool stuff. In the projects below, we won't need to use very advanced classes or niche C++ features however you're free to if you feel comfortable. Be sure to handle any errors or edge cases that may occur so your program doesn't crash or break.

- Password strength checker, that takes some string input and determines on a scale from 1-10 how strong your password is.
- Tic Tac Toe game against the computer, where the board is represented by some 3x3 array that gets **neatly** printed to console. The player should be able to pick which cell to play in through a row, A-C, and a column, 1-3. The computer's moves should be randomized, unless you would like to come up with an algorithm to always make the best move, which will involve checking to see if the user is ever 1 move away from winning.

### ----- Resources -----

# L6 - Advanced C++ and Data Structures

Hopefully we've developed a basic understanding of C++ by now. We've learned it's much more rigid and strict than Python, and early on it might even feel kind of janky. Nevertheless, we still need to move on and now learn some of the main features that makes C++ genuinely useful.

"Bad programmers worry about the code. Good programmers worry about data structures and their relationships." - Linus Torvalds

This lesson should take 3-4 weeks

### ----- What to learn (Ordered) -----
- File Inclusion
- File input/output
- Pointers and references
- Vectors
- Classes and class methods
- Templates / Generic Types
- Linked Lists
- Stacks and Queues
- Binary Trees
- Hash tables / Hashmaps
- Library use

---**What are these? (Also ordered)**---

- Just like in Python, we can import functions from another file. The way we do this in C++ is slightly different though, where we define all of our functions in our header (.h) file. From there, we can then import the header file of any file we'd like, given the functions in the header file are implemented in some .cpp file. For example, we could have some main.cpp file needing to use some functions in math.cpp, so we'd import math.cpp's header file (probably named math.h) inside either main.cpp or main.h to use those functions.
- The standard C++ library contains lots of functions useful for reading and writing to files. This allows us to store data and retrieve it later on, making it incredibly useful if you want data from your program to persist. Different modes can be specified to allow writing plain text, or raw binary to a file. Writing raw binary can be signifcantly more efficient when simply saving data that isn't supposed to be read by anyone except the computer, as writing the number 34,263,652 to a file in binary mode only takes 4 bytes, where as in plain text mode it would take twice that amount, 8 bytes. (1 32 bit integer, vs 8 ascii characters)
- If you haven't learned about them already, pointers and references are incredibly useful in managing memory and keeping things efficient. They allow us to have a variable that "points" to some other variable somewhere else in memory, instead of having to **create copies which takes processing power and even more memory**. They're incredibly useful in data structure implementation, as data structures often have "nodes" which can be thought of as the indices or "slots" in an array. Most nodes know some type of information about other nodes in the structure such as knowing where its neighboring nodes are, through pointers. **Pointers often don't get explained well by people who teach them**, I will link a video soon showing them and their use cases.
- Vectors are a much more advanced version of arrays. Vectors are essentially an "infinite size" array which when necessary, continuously grow themselves to be bigger and bigger behind the scenes to be able to fit more and more items in. Vectors can be created with any data type or user-defined types, meaning we can populate them with even our own structs and classes.
- Classes are the C++ implementation of objects, very useful for object oriented programming. Classes allow you to create your own objects with their own associated attributes and methods. They work quite similar to how they do in python, however a lot less janky as C++ was developed with OOP in mind.
- Templates are the C++ version of generic typing. Generic types are what allow us to create some data structure that holds whatever type of data type or user-defined type we want. Things like vectors use generic types, allowing a vector of integers, doubles, some user-defined Person class, or even a vector of vectors of strings.
- Linked Lists are a data structure similar to arrays, where we can sequentially insert pieces of data into a list. Each element in a linked list is called a **node**, where each node knows whether it's the **head** or **tail** node (first or last node), the previous node, and next node in line, if they exist. Generally, this is done through pointers, where a node has a pointer to its neighbors around it, and can be traversed by simply repeatedly accessing a pointer to the next or previous node. These are beneficial because they allow us to insert elements without the need to shift every other element in the list down one, leading to much faster insertions. The downside, however, is that we cannot access a specific element by index in constant time, to reach the n'th element, we must start at the first node and continuously retrieve the next node n times.
- Stacks and Queues are data structures that "stack" data. In a stack, whatever element was most recently added is the next to come out, similar to a stack of plates. In a queue, whichever element was least recently added is the next to come out. Both are very useful for scheduling and even advanced algorithms.
- A Binary Tree is a set of nodes that contain at most 2 children, and a parent node. The uppermost node is the root node, and generally acts as the starting point for things like search trees. As more nodes are added, the tree tends to grow downwards. Depending on how they're implemented, they can be used to efficiently store, and search for data in O(logn) time through repeatedly diving the number of nodes in half for each step down.
- Hashmaps are a form of key value data storage, assigning some piece of key data, to another piece of data. When an element added to the map, the key is hashed into an address to be placed into memory, along with its value. When a value is needed, the key can be given, which will then be hashed and the value at the given address will be returned as the value. This leads to constant access time without the need to search through the entire list to find some piece of data. A simple example of this would be an entire hashmap filled with every US state and their population, with the state name being the key and the value being it's population. Then, you could ask the map for the value at key "Oregon" and it would return 4,200,000.
- C++ quite obviously has a HUGE ecosystem of libraries, more commonly referred to as packages in Python. Using them can be quite a bit more challenging in C++, especially with the number of ways to do it, so getting the hang of it is quite necessary once you start writing larger scale projects.

### ----- Project Ideas -----

Now, we can finally actually start writing some cool, cool stuff. We're writing in a language that can do things incredibly quickly, allowing us to write advanced algorithms, simulations, and even games.

- CLI password management system that allows you to add, remove, view, and store passwords in a file. Remember, it is **EXTREMELY important to never store plaintext passwords**, so you're gonna want to find some library that uses an encryption algorithm like AES-256 or similar to store your passwords in. **Take care to research exactly how we actually store passwords in files.**
- Build a Linked List along with functions to traverse the list and find elements in your node. Be careful as to handle all edge cases and any errors that may occur so nothing breaks.
- Build both a Stack and a Queue data structure, along with functions to add elements and get the top/bottom element. These data structures can actually be **very useful** in some later algorithms we will explore. Again, be careful to handle edge cases so no weird, unexpected errors occur.
- Build a Binary Tree data structure of some type, along with functions to add to, remove from, and traverse around the tree. I recommend implementing a [Binary Search Tree](https://en.wikipedia.org/wiki/Binary_search_tree), which keeps data sorted for very quick searching. Google uses binary search trees to quickly decide what sites match your query. Once again, be careful to handle edge cases so no weird, unexpected errors occur.
- Use a library like [SFML](https://www.sfml-dev.org/) to build a simple game or particle/gravity simulation. This one is up to your interpretation, but there's a LOT of things you can do with this library, especially with its really good [documentation](https://www.sfml-dev.org/documentation/3.0.2/). There's lots of good videos around this type of stuff like this [Sand Simulation Video](https://www.youtube.com/watch?v=HrrJxkRlRfk)  or extremely advanced [Gravity Simulation](https://www.youtube.com/watch?v=GjbcvqEOIuE&t=572s). The data structures and algorithms you use to do this are **very** important, as things like simulations can be very, very performance intensive.






# L100 - HTML and CSS

Behold, the backing of basically every single website you've ever laid your eyes on. HTML and CSS are perhaps the single most useful thing to know when devloping a website.

# L200 - Databases

# L300 - Networking Basics

# L400 - Linux

# L500 - Server Systems

# L600 - Programming Languages

As you have hopefully learned by now, there's tons of different programming languages out there which generally tend to have their own specialized use cases. The four we have learned up to this point are Python, C++, Assembly, and Javascript (or hopefully even more !!).  As you've probably noticed, each of these 4 languages all have their own way of being written, studied, and their own use cases. These are what we call the programming language **semantics** and **syntax**, which are terms for the mathematical meaning behind what we write. These 4 languages, conceptually, will more or less cover most topics, use cases, and issue's we'll run in to when writing in any language. As you begin to learn more languages, you'll start to realize that each new language is just some different flavor of another language you've already learned, with different syntax but similar semantics. This can heavily speed up the learning process of new languages, as once you know some of the main, core languages, everything else is similar enough. While this is true, it's also important **not to fall into the trap of just learning the language's syntax**, but not necessarily its semantics. Take, for example, C/C++ and **Rust**. Rust is a "memory safe" version of C which is intended to have very similar functions and use cases to C, but with better memory safety, package management, and in some cases, even things like execution speed. If you already know C/C++ and start to learn the language's syntax, it'll be a breeze. You already understand everything like data types, memory allocation, compilers, and everything else that comes along with low level languages. The trap here is, if you try and write Rust code with similar semantics and flow as you would in C, it's very likely your Rust code will seem awkward and in many cases, even **unsafe** to experienced Rust devs. Rust has an entirely different flow, a different way of being written and doing things, which is very important and takes time, effort, and failure to learn, which probably sounds very similar to your early Computer Science experience. As you'd expect, this issue will arise again and again with each new language you learn, however as long as you understand the core concepts of the language you're learning, you should be able to master it in no time.

### --- **But how do I choose a programming language?** ---

With all that in mind, we dive into our next topic, how do I even choose which programming language to write my next piece of software in? The answer to that question won't always be a simple, single language best answer, as many languages *can* serve the same purpose, but it's important to learn to **use good judgement**. **Though there may not always be one, single correct answer**, it's generally a good idea to go with what will combine simplicity, functionality, and personal comfort. Below will be a list of a ton of various programming languages, along with their use cases, pros, and cons to potentially help you make your decision. Still, keep in mind it's always a good idea to research more before you make your choice.

<br>

### --- **C** ---
C is generally used for low level systems programming or writing any code where execution speed really, really matters. We see it everywhere in places like operating systems, device drivers, embedded systems like our little thermostat or BIOS components, system libraries that deal with things like graphics, audio, and device I/O, and almost anywhere else you could even imagine. Even if you're not writing in C, there's a good chance that C is *always* running in the background.

C is a great choice if you're planning on writing any smaller scale low-level system code that's supposed to operate very close to the hardware, or if you're writing something where execution speed is absolutely critical. If memory safety is important and you don't trust yourself enough, some better options might be C++, Rust, or Go.

#### **Pros:**
- Extremely fast, gets compiled directly into machine code.
- Modern compilers optimize the code very, very well.
- Very lightweight, providing minimal abstraction so you're getting basically *exactly* what you type.
- Manual memory allocation and freeing, leading to much more control and efficiency if done well.
- No garbage collector constantly running, which takes up copious amounts of extra memory and processing power.
- HUGE ecosystem, a library for almost anything you could ever need probably exists.
- Compiles for anything, everywhere.

#### **Cons:**
- No memory safety features at all, meaning manual memory allocaiton and freeing can also lead to severe safety issues, crashing, and memory leaks if not handled correctly.
- Can be difficult to debug.
- Much slower development at a large scale.

<br>

### --- **C++** ---
C++ is like if C had a child and got really lucky with the gene pool. C++ code can be used everywhere where C is used, it's just like C but significantly more functional, providing Object-Oriented semantics with zero-cost abstractions among many other quality-of-life features. C++ is generally used in large scale applications where low-level performance and features matter. These are usually things like web browsers, game engines and devleopment, libraries and frameworks, databases, and simulations.

C++ is a great choice if you're building a larger scale application while still requiring performance and control. It's among one of the most versatile languages and *can* be used for almost everything (doesn't mean it *should* though). Though it provides all features of C (and more !!) but with added safety, memory safety issues still arise.

#### **Pros:**
- All pros of C.
- **Modern compilers** are very advanced and can often optimize abstractions away.
- Provides classes, templates, and generic types, which are very useful for library and data structure building.
- Much better memory safety than C.
- Interoperable with all C code.
- Significantly easier to develop at large scales than C.

#### **Cons:**
- Memory safety issues can still arise, even in the standard library functions if not handled correctly.
- Standard library implementations differ across platforms.
- High complexity which can lead to spaghetti code and difficulty in learning.