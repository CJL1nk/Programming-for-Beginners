# CJ_Link Coputer Learn Guide

learn to use the 'puter

# L1

So you know next to nothing other than computer has a screen and does some cool stuff
You made it here so I'm just gonna assume you at least know how to use that jawnson

Our very first step here is to learn the basics of programming, preferably in an easy language like [Python](https://www.python.org/downloads/)
There's several other languages good for beginners but this is the best in my opinion
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

# L2

So you've made it this far, farther than most people really. By now, you should  have spent at least a couple weeks learning and writing mini programs and maybe even gone beyond. Ideally you should already know some of the stuff in here.

This lesson should take approximately 1-2 weeks.

### ----- What to learn (Ordered) -----
- File importing and multi-file programs
- File reading and writing
- Using files to store data
- JSON
- Basic command line commands
- Package installation with pip
- Documentation reading and writing
- Git and GitHub

---**What are these? (Also ordered)**---
* File importing lets you use functions written in other files. This is very helpful for organizing your code.
* File reading allows us to read data from a file for our program to use, and file writing allows us to write data. This is incredibly useful for things like game save files or storing other data we might want to save across sessions.
* JSON is a format that's commonly used to store various types of data. It's easy to understand and efficient, making it useful to store and retrieve somewhat large amounts of data.
* The command line is your little terminal where you type in commands. This is arguably one of the most important things to learn early because you don't wanna be stuck as what I like to call a "clicker."
* PIP is the default python package installer. It allows you to download packages or libraries, which are often large organized collections of code (or "modules") written by other people made to perform a variety of specific, related functions.
* As explained before, documentation is how we keep track of our code in English, writing out what it does, how it works, how to use it, and what to expect from it.
* Git is a command line application that lets us track the version history of our code. GitHub is a place where we can upload Git repositories, which are the collections of our code bases. This allows us to track progress and past versions of our code, as well as acts as an online backup just in case we somehow lose it.

One thing I wanna go over right away is how important learning how to write clean, organized, and well documented code is in this phase. It's really easy to be mindlessly writing code without thinking about how readable it is or how well it might be optimized. Whether you believe it or not, you **will** eventually forget exactly how some parts of your programs work and if there's no comments explaining anything and the code is messy, written like a bowl of noodles, you'll have a hard time figuring out what exactly does what and how things are linked together. As a result, this makes maintaining, expanding, and updating your code significantly harder.

### ----- Project Ideas -----

We've finally moved onto slightly more advanced projects yippee!! From here on out, each of these projects will likely take a bit longer and require more thinking and troubleshooting. Don't let that demotivate you though, as that's really, truly, the only way to get better. I also recommend practicing writing cleaner, more organized code as you work on these projects.

- Clean up old code. Look through some of your past projects and see how you can clean, document, and potentially maybe even optimize some of the past programs you've written. This is a very common thing to need to do, so getting some practice in now never hurts.
- 

### ----- Resources -----

* [Teclado importing tutorial](https://teclado.com/30-days-of-python/python-30-day-18-imports/)
* [(Video) Tips to organize Python code](https://www.youtube.com/watch?v=e9yMYdnSlUA)
* [(Video) How to structure your code](https://www.youtube.com/watch?v=6OSpm4uXqDw)
* [JSON Tutorial](https://www.w3schools.com/js/js_json_intro.asp)
* [Windows Terminal Documentation](https://learn.microsoft.com/en-us/windows/terminal/)
* [Linux Terminal Documentation](https://linuxcommand.org/lc3_man_page_index.php)
* [PIP Documentation](https://packaging.python.org/en/latest/tutorials/installing-packages/)
* [(Video) How to document your code](https://www.youtube.com/watch?v=L7Ry-Fiij-M)
* [How to write good code documentation](https://guides.lib.berkeley.edu/how-to-write-good-documentation)
* [W3Schools Git tutorial](https://www.w3schools.com/GIT/) (Again please learn how to use this site it's AMAZING)
* [(Video) Git and GitHub tutorial](https://www.youtube.com/watch?v=RGOj5yH7evk)
* [GitHub Docs](https://docs.github.com/en/get-started/start-your-journey/hello-world)


