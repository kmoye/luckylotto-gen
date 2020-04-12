Kevin Moye
Project Step 4
11 Feb 2020

#Feature: 
In order to generate random numbers for a lottery game
As a Customer
I want to use a console-based application

## Scenario 1: Choose game
Given I want all to select either Powerball or MegaMillion
And I have just opened the application
When I press either the "P" key on the keyboard
Then the Powerball generator option screen will appear

## Scenario 2: Choose game
Given I want all to select either Powerball or MegaMillion
And I have just opened the application
When I press either the "M" key on the keyboard
Then the MegaMillion generator option screen will appear

## Scenario 3: Choose numbers
Given I want to generate all lottery numbers
And I do not want to use any user defined numners
When I press the "G' key on the keyboard
Then a random set of numbers will be generated for the selected game

## Scenario 4: Input user defined numbers
Given I want select some of my own set of numbers for chosen game
And I know how many in the set I want to choose
When I press enter that amount on the keyboard
Then those numbers will appear in the set

## Scenario 5: Add another set to the numbers
Given I want to add more sets of numbers
And I know how many more sets I want to add
When I press "A" on the keyboard
Then I will have the option to generate more sets of lottery numbers

## Scenario 6: Export Numbers
Given I want all to export the list of numbers to a .txt file
And I want the text auto-named in a date/time/seriesnumber format
When I press the "E" key on the keyboard
Then the list will be exported to a specificed file location