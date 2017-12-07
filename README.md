# Lab 12 - Getting Graphical with Processing

## What this lab gets you

* You'll get to do something a bit more visual by kicking the tires on Processing, a "flexible software sketchbook and a language for learning how to code within the context of the visual arts". (Quote taken from the [Processing website](https://processing.org/).) Processing is based on the Java language, so you should feel right at home. 
* Lest you think Processing is just some kind of lame toy language, take some time to look at some of the very cool stuff that was created with (or whose creation was aided by) Processing at the [curated exhibition page](https://processing.org/exhibition/) - some of the older links may be dead and some pages are not in English...because Processing is used throughout the world!

## Getting Ready

We have Processing installed in our labs (including B107 and B103); if you want to install it on your own machine, it is freely available on the Processing website. 

1. Start Processing on your machine.
    You can skip the Welcome screen.![Image](screen.PNG?raw=true) 

        What you should see is a Processing sketch window. This is your code editor.

        You should also see a "play" arrow button.
1. Using processing is meant to be pretty simple - type your code into the editor and press play!

        Let's give you something to do!

## Processing Practice - Coordinate System and Shapes

1. Got to https://processing.org/tutorials/
1. Start the _Coordinate System and Shapes_ tutorial
1. Draw yourself some points, lines, rectangles, and ellipses - for the rectangles and ellipses, make sure you try the different modes (CENTER, CORNER, and CORNERS)
1. You can save your sketchbook if you wish through the File menu - make sure you choose a reasonable save location, as the default location is NOT reasonable!

---

## Processing Practice - Color

1. Got to https://processing.org/tutorials/
1. Start the _Color_ tutorial
1. Draw yourself some **colored** points, lines, rectangles, and ellipses - for the rectangles and ellipses, make sure you create shapes with different fills and strokes.
1. You can save your sketchbook if you wish through the File menu - make sure you choose a reasonable save location, as the default location is NOT reasonable!

---

## Programming Practice 3

Switch driver and navigator.

1. Use the same project.
1. Create a new class in the project called `WordMixMaster`.
1. Create a standard Java main in that class.
1. Create code that solves the following problem (adapted from Horstmann E4.7):

    _Create a program that creates a word jumble, following this algorithm:_

        Read a word with length >= 3 (re-prompt if necessary) 
        Repeat word.length() times  
            Pick a random position i in the word that is not the last position
            Pick a random position j > i in the word
            Swap the letters at positions i and j
        Print the word  

When you think you have completed the task, call your instructor over.

---

## Programming Practice 4

Switch driver and navigator.

1. Use the same project.
1. Create a new class in the project called `BlintzButlerRefined`.
1. Create a standard Java main in that class.
1. Create code that solves the following problem:

    _Your blintz butler was so awesome, the public is clamouring for more. You've decided to improve the program by adding the following additional features:_

    * If the user enters in a non-integer, the program will print "Ma'am? (or Sir?)" and then re-prompt.
    * If the user enters a 0, the program will print "Feeling unwell, ma'am? Perhaps another blintz might help." and then re-prompt.
    * If the user enters a negative number, the program will print "How droll." and then re-prompt.

    _Here is an example run of the improved program:_

        Please enter the number of blintzes in the house: 3

        How many blintzes would you like, ma'am? Avast there!
        
        Ma'am?

        How many blintzes would you like, ma'am? 0

        Feeling unwell, ma'am? Perhaps another blintz might help.

        How many blintzes would you like, ma'am? -4

        How droll.

        How many blintzes would you like, ma'am? 3

        Very good, ma'am - here are your 3 blintzes. Enjoy.

        I regret to inform you that we no longer have any blintzes remaining.
