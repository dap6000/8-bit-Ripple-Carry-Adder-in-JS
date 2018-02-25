# Simulating an 8-bit ripple carry adder

I'm watching Crash Course: Computer Science with my son. When we got to video
5 How Computers Calculate, he told me he wanted to a deeper dive on binary
representations for numbers and doing addition with logic gates. He recently
completed a school project on electric circuits and thankfully he's making the
mental connection between circuitry and logic gates. *But* I'm not the sort of
maker dad with a workshop and soldering gun. Rather than trying to wire up an
actual, physical logic gate I thought this could be a good exercise to explore
bitwise operations in Javascript and working up the same layers of abstraction
outlined in the video using functions as reusable / composable building blocks.

We spent an afternoon kinda sorta pair programming, with me in the hot seat,
reasoning through the logic gate based arithmetic explained in the video and
recreating it in Javascript. We got to (briefly) talk about the DOM, how and why
`"5" + "5" = "55"`, convert user input strings into integers, convert integers 
into arrays containing 8 boolean values to represent our 8 bit numbers, convert
those arrays into 8 character strings for display, the reasoning behind all this
juggling of representations for the _same_ numbers, error reporting, events and
event handlers, and docblock comment style.

I think he even maybe *understood* some of it!

Anyway, the Crash Course video series on YouTube is pretty awesome. We're
enjoying the Computer Science course right now. And the particular video that
inspired this project can be found at:

https://www.youtube.com/watch?v=1I5ZMmrOfnA
