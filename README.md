# Library-Sharing
A pet project to build an application/ database that would allow user input for books, owner and a system to track current holder for sharing purposes

I will start by building a mockup of the features I want and the database structure in Excel and Excel VBA.
Each User will have a unique Worksheet that will store their libraries with fields
Title Author Genre Owner Hold
Title Author would be free character strings, highly considering using data validation for genre to simplify categorization. When built as an actual application, may also consider using an API to pull genre from the internet
Owner will be equivalent to the Worksheet name 
Hold will be a logic statement (TRUE/FALSE) and will refer to whether the current person (in larger database) is currently in poesssion of the book

Initial buildup in Excel will also serve as a useful categorization of my own library.
If implemented in Python, I can build a class object named Book with previously mentioned fields.
