# Checkpoint-Algorithm-and-its-Elements

 I declacred 4 counter variables and initilized them accordingly. Two string characters for dot(.) and the input were also declared.
 A read() function was used to read (accept) the input from the user.
 A while loop was used to count all the characters including space untill the point were a dot (.) is detected.
 A for loop is then then used to check for the number of words. A nested if - else statement is applied in the for loop. Any place a space character is detected, the word_count is incremented by 1. 
 The word_count is initialized with 1 because the smallest word in a sentence is 1.
 The else part of the if-else statement performs a character count by skipping all space characters.
 A switch statement is nested in the last for loop to count vowels.
 For each vowel detected, the vowel_count increments by 1 and breaks out of the switch statement and passes functionality to the for loop.
 THe loop runs for the total lenght of the for loop.
