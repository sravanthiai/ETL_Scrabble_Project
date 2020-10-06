# ETL_Scrabble_Project
Program that transforms the legacy data format to the shiny new format.
ETL
Extract-Transform-Load (ETL) is a fancy way of saying, "We have some crufty, legacy data over in this system, and now we need it in this shiny new system over here, so we're going to migrate this."

(Typically, this is followed by, "We're only going to need to run this once." That's then typically followed by much forehead slapping and moaning about how stupid we could possibly be.)

The goal
We're going to extract some scrabble scores from a legacy system.

The old system stored a list of letters per score:

1 point: "A", "E", "I", "O", "U", "L", "N", "R", "S", "T",
2 points: "D", "G",
3 points: "B", "C", "M", "P",
4 points: "F", "H", "V", "W", "Y",
5 points: "K",
8 points: "J", "X",
10 points: "Q", "Z",
The shiny new scrabble system instead stores the score per letter, which makes it much faster and easier to calculate the score for a word. It also stores the letters in lower-case regardless of the case of the input letters:

"a" is worth 1 point.
"b" is worth 3 points.
"c" is worth 3 points.
"d" is worth 2 points.
Etc.
Your mission, should you choose to accept it, is to transform the legacy data format to the shiny new format.

Goals
#practice breaking down a problem and solving itin Python from scratch.
#practice working with dictionaries and for loops.

Resources
legacy_data= {
    1: ["A", "E", "I", "O", "U", "L", "N", "R", "S", "T"],
    2: ["D", "G"],
    3: ["B", "C", "M", "P"],
    4: ["F", "H", "V", "W", "Y"],
    5: ["K"],
    8: ["J", "X"],
    10: ["Q", "Z"]}
    
Breaking down the problem

Step1:
Created a legacy words list as specified in the requirement.
Step 2:
Created a dictionary with each correspoinding word in the program.
Step 3:
Sorted the dictionary list and append.





