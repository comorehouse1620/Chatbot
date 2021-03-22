# Lab 2 - Data Classification & Chatbots
# Summarization of What my Scripts Do 
Part 1 - My script in this part of the assignment first creates the variable temp and creates and input function, but converts to an integer because input function accepts string inputs. I then defined my function feeltemp, inserted parameter temp, and then with if/elif/else statements designated that given the integer input, the function when called would print out what range that number fell into. At the bottom of the script I call the function with the parameter. 

Part 2 - My script for the chatbox part of the assignment acts as a bot that is collecting information on behalf of the Biden campaign. The script starts out by defining a function with the parameter username, which at the bottom of the script username equals and input function that asks for the users name. From there, the script creates a questions function that asks the user a series of functions using if/elif/else statements. Based on what the user enters, the chatbox may or may not lead to another question. The function's purpose is to convince the user to either donate to register to vote, Vote for Joe Bien, and donate to Joe Biden. At the bottom of the script I call both the greeting function and the questions function. 

# Any many Errors
My main errors in this script was in building out the chatbox it took me a while to figure out how to position the embedded if-statements (where to tab over). 

# Resolving the Issue
After researching on stack overflow, I figured out that statements on the same tab level read like a book, so to speak. So if the answer was "no" to an if question, and I wanted the script to move on to an "else" statement, then put that else on the same level as that if statement, but the answer is yes, and I want to go to a new if statement, tab right underneath that particular if statement, and so on. 
