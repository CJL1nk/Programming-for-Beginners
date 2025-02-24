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
- Basic understanding of documentation websites
- Basic problem breakdown and solving skills
- Read everything below, ESPECIALLY including ***How do I “Problem Solve?”***

---**What are these? (Also ordered)**---
* Basic programming functions are just the most commonly, easy to use coding functions. Things that let you add numbers, print stuff to the console, and let the user type things in.
* If/Else statements are used to make your program run different code based off given conditions. For example, if a number is less than 5, say "Hello" to console, else, if it's greater than 5, write "Goodbye" to console.
* Functions let you "save" a block of code and call it whenever desired, multiple times even.
* Variable data types are the type of data you're storing. For example, you couldn't have "B" in an integer variable because an integer only stores a number.
* Arrays allow you to store a collection of multiple values in a single variable.
* Loops continuously run the same block of code until a certain of code is meant. For example, increment a number by 3 until the number is greater than 20.
* Documentation websites are where you'll often find yourself when learning new programming languages or when using libraries. They tell you how the code works, how to use it, and any quirks it may have.
* Problem solving skills are explained below.

This will likely take a little while, don't just watch a video or two and have a basic understanding of their concepts. True understanding and knowledge comes through **experience**, which takes lots of **time**, **failure**, **mistakes**, and most importantly, **projects**. This lesson covers a LOT and should by far take the longest of any of the lessons, at the very **LEAST 2-3 weeks**.

This stage of your learning is hands down the most important part of your entire journey. Without a very strong understanding of the **fundamentals of programming itself**, you won't be able to get anywhere on your own. Keep in mind the fundamentals are significantly different and more important than the programming language itself. Things like real problem solving skills and the ability to break a problem down into individually solvable parts are incredibly useful, impossible to move on without. As tedious and boring as it might get, I can't reiterate enough that you need to **REALLY TRULY** understand these first few lessons, to the point of where any project or problem could be provided to you within your skill level and you should be able to pull it off within a **reasonable amount of time** with minimal problems.

One thing I will note, very early on, is that AI chatbots like ChatGPT, Grok, DeepSeek, or whatever else you might use have the ability to generate code for you. I **STRONGLY** advise against this as a beginner, as it **will** get you almost nowhere and you'll end up missing many of the basic **problem solving** skills that come along with programming. If you're truly stuck, I say it's okay to ask it where a bug might be happening in your code as it can be useful to identify things like that, however keep in mind that mistakes are very common from the AI and a good percentage of the time, code that's generated often won't work as expected, or won't work at all.

### ----- How do I "Problem Solve?" -----

Problem solving is a widely under-talked about aspect of programming, which is why I'm writing a mini lesson on it here. For the most part, this skill should develop naturally with time and experience but it's good to read a bit about it,

So what's even meant by problem solving? We can all solve problems can't we? Most of us probably wouldn't even be here if we didn't have SOME form of these skills right? Well, though those questions may be correct, they may not be as strong as you think they are, no offense intended.

For your first little exercise, imagine yourself as the developer of a little 2D mobile game. The game's nothing super serious, but the general idea for it is for you to be able to build your own terrarium and decorate it with your own plants, soils, bugs, animals, and whatever else might be included in a terrarium. You probably already have some more advanced ideas for this game, which is great, **creativity goes a LONG way** in programming. Now, I want you to think, what's the VERY FIRST, absolutely most basic thing you need to get done once you start coding your game. Some common answers to this are getting a terrarium on screen, making plant models, or making moving bugs. While these aren't exactly bad answers, they're not exactly as simple as they might seem. What do we need that's even more simple than that? If you guessed a window that we can even display stuff on, congratulations, you're already figuring it out better than 90% of most beginners. The VERY first thing we need is a little window we're able to even draw or display stuff on in the first place. From there, what's the next step? Well, the whole idea of having this window is to display stuff, so let's try drawing a line, or perhaps a square on the screen. From there, we can make the square move from left to right. Then we can draw a little box around our square, our first little "terrarium." As time goes on, we keep building up and up, making our little box slightly more and more complicated until we finally have something that resembles a terrarium, dirt, little bugs, and so on.

If you haven't caught on already, the point to this lesson is to teach that in programming, it's far too easy to try and start out too big. If we tried to start out by making moving bugs and plants that would grow as time went on, we probably would have to end up changing a LOT of their code in the future, assuming we even got that far in the first place. If we had their textures, models, and even some code that could be usable, what would we use them on? We have no window to render these plants, no physics engine, and not even and object system in place. You can't start building a skyscraper from the top. Never forget how important it is to start small and simple, to break your idea down into its smallest most simple parts and start putting it together from there.

### ----- Project Ideas -----

So you've developed a pretty basic understanding of programming. You know how to write little functions that do simple things like add, or print a user's name based off some given input. Now your task is to make some mini projects to develop your skills. You'll quickly discover that it's pretty hard to come up with project ideas, which is something I'd say you can ask AI to give you some ideas on, so here's a list of some little project ideas for your skill level. The goal behind all of these is to utilize almost everything you've learned so far, as well as to help develop a deeper understanding of how they work and identify and weird quirks they may have.

- Command Line Calculator, which prompts the user for an operation (add, subtract, multiply, divide) and 2 numbers to perform the operation on. The program should then print the output to the console and continue asking for an operation until the user enters "Q" or some other option to exit.
- Fizzbuzz, a classic beginner programming challenge. Given a user entered integer **n**, for every positive integer **i <= n**, the task is to print "Fizz" if the number is divisible by 3, "Buzz" if it's divisible by 5, and "Fizzbuzz" if it's divisible by both 3 and 5.
- Find largest number, which repeatedly prompts the user for a number until they enter a negative integer. From there, it should print out the sum of every integer entered as well as the largest, and maybe even smallest numbers entered. There are multiple ways to solve this one, try to start doing so by using an array, then explore other options.
- Mad Libs generator, which asks the user for a series of nouns, verbs, adjectives, etc... and inserts them into a potentially funny story. [Mad Libs](https://en.wikipedia.org/wiki/Mad_Libs)
- Number guessing game, which asks the user to enter a number between 1-100. If the number is too low, it prints "Too low" and if it's too high, it prints "Too high." Once they guess the correct number, start again with a new one.

### ----- Resources -----

One of the hardest parts of learning how to program is **learning how to learn in the first place**. It's really easy to just search up some YouTube videos and say you've learned a lot when in reality, you don't know as much as you think. Below is a list of resources to help you get started. I recommend if there's anything you run across in here that you don't know how to read or aren't sure what it means/does, please take the time to look into it and figure it out.

- [Python For Beginners](https://www.python.org/about/gettingstarted/)
- [CodeAcademy](https://www.codecademy.com/learn/learn-how-to-code)
- [W3Schools](https://www.w3schools.com/) (My king <3)
- [GeeksForGeeks](https://www.geeksforgeeks.org/)
- [RealPython](https://realpython.com/)
- [LeetCode](https://leetcode.com/)
- [(Video) 12 Hour Python Course](https://www.youtube.com/watch?v=ix9cRaBkVe0) (Please don't just watch this and assume you know everything)
- [(Playlist) Another Good Python Course](https://www.youtube.com/watch?v=mRMmlo_Uqcs&list=PLIhvC56v63ILPDA2DQBv0IKzqsWTZxCkp)
- [Python Documentation](https://docs.python.org/3/)
- [StackOverflow](https://stackoverflow.com/questions) (Use this as a last resort for questions, sometimes people's solutions are a bit bogus)

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
* As explained before, documentation is how we keep track of our code in English, writing out what it does, how it works, how to use it, and what to expect from it.
* Git is a command line application that lets us track the version history of our code. GitHub is a place where we can upload Git repositories, which are the collections of our code bases. This allows us to track progress and past versions of our code, as well as acts as an online backup just in case we somehow lose it.

One thing I wanna go over right away is how important learning how to write clean, organized, and well documented code is in this phase. It's really easy to be mindlessly writing code without thinking about how readable it is or how well it might be optimized. Whether you believe it or not, you **will** eventually forget exactly how some parts of your programs work and if there's no comments explaining anything and the code is messy, written like a bowl of noodles, you'll have a hard time figuring out what exactly does what and how things are linked together. As a result, this makes maintaining, expanding, and updating your code significantly harder.

Another thing I think is important to learn somewhat early on is how to actually use the command line. At first sight it's a pretty scary thing, a lot of people view it as a dangerous section of your computer that you should never touch to avoid screwing something up. While this is kind of true to some degree, it's nearly impossible to do, especially on windows, without a good amount of knowledge and luck. In order to screw something up, it HAS to be intentional, so you probably won't need to worry too much. The reason I think it's such an important thing to learn now is mainly because of Git, as the commands you'll be running are all through the terminal unless you use something like GitHub desktop. On top of that, basic knowledge of it is necessary for more advanced programming languages like C++, which we'll learn a little later down the road. It's also very common for servers to run on Linux distributions that are terminal only, meaning there's no user interface or anything you can click on. This might seem a little silly at first, but you'll understand a little better later on once we learn how servers work and how resource intensive having a GUI could be. Bottom line, get comfortable with the command line, it's not as scary or hard as it might seem at first.

The final topic I wanna go over here is edge case handling. As mentioned before, edge cases are odd values that we might not exactly expect our program to receive which end up breaking things. It's easy to say something like "oh well whoever's using my program shouldn't be doing stupid inputs with it in the first place," and while you aren't exactly wrong, it's still not very good practice to just let these slip by. There are many, many instances where edge cases will arise from non user-entered values and our edge cases are completely normal values that we would expect to receive. That's why it's so important to handle, especially in large complex systems where a single error could shutdown an entire city.

### ----- Project Ideas -----

We've finally moved onto slightly more advanced projects yippee!! From here on out, each of these projects will likely take a bit longer and require more thinking and troubleshooting. Don't let that demotivate you though, as that's really, truly, the only way to get better. I also recommend practicing writing cleaner, more organized code as you work on these projects. Be sure to handle any errors or edge cases that may occur so your program doesn't crash or break.

- Clean up old code. Look through some of your past projects and see how you can clean, document, and potentially maybe even optimize some of the past programs you've written. This is a very common thing to need to do, so getting some practice in now never hurts.
- Use a library like matplotlib to display some type of statistics of your choice. [Matplotlib](https://matplotlib.org/)
- Write a note taking app, which allows you to save notes with a title, an actual note itself, and an automatically determined date. Upon opening, a menu should be displayed asking the user if they want to write a note or open a note. If they choose to write a note, they enter a title and the note itself, which then gets saved to a file along with the date. If they choose to open a note, the title and date of every note they have written will display on screen, bonus points if you have a preview of the note itself. They can then choose to display a note by typing in the title.

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

---**What are these? (Also ordered)**---
* Classes are a way to store what we call "Objects" in programming. A single object represents an entity with its own attributes and methods, meaning it can have multiple of its own variables and functions. An example of this would be creating a Person class, where it has a name, birth date, weight, height, and might have some functions like eat() that increase the person's weight. We can then create multiple instances of this person class, so we could have Person1, Person2, Person3, etc.. all with their own names, heights, weights and so on.
* Class methods are functions within a class designed to perform specific functions on its parent class. Usually they involve simply modifying or returning values, but can be used in other clever ways too.
* Object oriented programming (OOP) is the concept of designing our programs around objects.
* Dictionaries (or Hashmaps in other languages) are a way of associating 2 pieces of data together. For example, we could have a dictionary containing a class's grades. Each item in this dictionary has a key and a value, and in this case we'd see relationships like {"John": 85.3} or {"Martha": 92.0} where the key is the person's name and the value is their grade. We can then just access the dictionary by the persons name and immediately retrieve their grade. Unlike arrays, we can instantaneously access a key without having a search through the entire collection.
* JSON is a format that's commonly used to store various types of data. It's easy to understand and efficient, making it useful to store and retrieve somewhat large amounts of data.
* Bubble Sort, Insertion Sort, and Selection Sort are 3 of some of the most basic sorting algorithms. Sorting algorithms look at a collection of comparable objects, usually integers, and sort them from smallest to largest. These three are some very basic ones, however we'll look at some more complex, faster ones when we get into algorithms and data structures.

### ----- Project Ideas -----

With objects and classes finally out of the way, we've finally learned some of the most useful features of programming. Of course, these features aren't very useful to us unless we practice and make good use of em, so get to work and make some cool stuff. Be sure to handle any errors or edge cases that may occur so your program doesn't crash or break.

- Employee database, which contains a class Employee that holds the employees name, address, and phone number. Each employee is saved into a dictionary {EmployeeID: Employee} which is saved to a json file. Upon start, the program should load all the current employees from the json into the employees dictionary, and employees should be able to be added or removed.

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
* [(Video) How to Convert Decimal to Binary](https://www.youtube.com/watch?v=VLflTjd3lWA)
* [(Video) Binary Addition and Subtraction](https://www.youtube.com/watch?v=C5EkxfNEMjE)
* [Binary Multiplication](https://www.sciencedirect.com/topics/engineering/binary-multiplication)
* [What is Hexadecimal](https://www.techtarget.com/whatis/definition/hexadecimal)
* [(Video) How to Convert Hexadecimal to Decimal](https://www.youtube.com/watch?v=pg-HEGBpCQk)
* [Number in Different Bases](https://mathcenter.oxford.emory.edu/site/math125/bases/)

# L5 - C++ and Memory
Now that we have a basic understanding of binary and hexadecimal, we can finally move on to our next programming language. You may have heard scary things about C++ with how hard and different it is, but after a bit of practice and understanding of how the language and computers work, it becomes a breeze.

To start off with C++, we'll need a slightly more complex IDE. You can use VSCode, but I highly advise against it because that's like using Windows Notepad for Python. I recommend for beginners you use [CLion](https://www.jetbrains.com/clion/download/#section=windows), however you can also use [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) which is a bit more complex.

Next, we'll need a **compiler**, which is what translates our code into machine code, something our computer can actually execute. I'm not gonna explain too much now because it gets a bit complicated, but we'll use [GCC](https://sourceforge.net/projects/mingw/files/Installer/mingw-get-setup.exe/download).

I highly recommend watching step by step tutorials for learning how to install things correctly, which I will link below in resources.

This lesson should take 2-3 weeks.

### ----- What to learn (Ordered) -----
- Basics of C++, listed below
- Declaring variables, variable data types, performing basic operations like addition, subtraction, and so on
- If/Else statements
- Functions, return types, parameters and arguments
- Loops
- Basic arrays
- Printing to console with cout
- The C++ compiler
- Compilers vs Interpreters
- Memory, RAM, and how things are stored there
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
* The compiler looks at our code and translates it into machine code, or **Assembly**. This will produce an executable file for us to click and run. On the other hand, an interpreter, which is what Python uses, interprets and executes our code line by line.
* Our computers need some way of actually storing all the numbers and letters we're seeing on screen, as well as all the instructions written in our code. It stores most of this in the RAM (Random Access Memory), in the form of binary or hexadecimal. Different data types take up different amounts of space. For instance by default, an integer variable takes up 32 bits, or 4 bytes, in memory.
* Unsigned integers are integers that cannot be negative, and will roll back to 0 once they hit their size limit. Signed integers, on the other hand, can be negative, and will roll to it's lowest value when they hit their size limit.
* Two's complement is the method we use to store negative numbers in binary. Not a super deep understanding of this is required just yet, but it's a good thing to know.

This probably seems like a LOT to learn, and trust me, it is. We're entering almost a whole new world of computers here so don't expect it to be easy. It **WILL** be frustrating, we've all been there before. But please do remember, you have infinite resources on the internet and even me if you get stuck, so feel free to contact if you have any questions :)
