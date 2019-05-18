# Test01- Total possible points, 225

Test1 must be submitted to your personal private repo (ST0??) by 5:30 pm May 14th. Late submissions will not be accepted, therefore it is recommended that you start this as early as possible. Leaving this to the last minute (including your push to your repo) could result in last minute issues that you cannot address in time. Test submissions must be your own work - copied work will result in an academic violation, and a zero for the test. 

Read each question carefully. 

## Part 1: 

Choose one on the following (note: if you do both of these, only the first one will be marked):

### A: 50 pts
Find and fix at least one typo found within the class notes repo (I put a couple in there on purpose). Pull request this change with a message that indicates this is for ITM695, Test1, Part1 question A.

### B: 50 pts

 Each student in the class has a public repo. This can be found as a link on their profile page (See ClassNotes/student_repos.csv for a list of the students and their github profile page).

 Your task is to do a pull request to add a hello message in each students public repo (you'll need to do this 5 times). Add a file named <firstname>_<lastname>.md. Write in this file a greeting. Your file must include at least one header and a link to your personal repo (using markdown link, the link should display as "see my repo here").

 NOTE: You do not have to accept the pull requests you will receive on your own personal repo. This is something we will go over in class next week.


## Part 2: 75 pts

Ask the user to enter a number between 2 and 2000. Your program will determine if the number they entered is prime (or not). Your program should all the user to continue to test numbers numbers until the user enters a number less than 2.

HINT: See class05 notes for a list comprehension that produces a list of prime numbers. You will use this list comprehension pattern to generate all primes from 2 to 2000 and determine if the user enter a number that is in this list of prime number.

Your interface is required to behave as follows (closeness to this counts!):

```
Please enter a number: 2
The number 2 is prime.
Please enter another number: 3
The number 3 is prime.
Please enter another number: 8
The number 8 is not prime.
Please enter another number: -1
This terminates our session. Have a nice day.
```

## Part 3: 

Choose one on the following (note: if you do both of these, only the first one will be marked):

###  A: 100 pts

![squirrel](/Images/squirrel.png)

The squirrels in Tampa spend most of the day playing. In particular, they play if the temperature is between 60 and 90 (inclusive). Unless it is summer, then the upper limit is 100 instead of 90. Write a function that given an int temperature and a boolean is_summer, returns True if the squirrels play and False otherwise. Sufficiently test this function in your may program (not by asking for user input - you want to have your tests inside the code so that you have a record of what values you used to test the function)

##  B: 100 pts + a possible bonus of 20 points for an excellent submission

Using a dictionary structure, create a program that encrypts a phrase given by the user. It should display the cipher text, and a table representing the decrypt key. Each phrase encrypted should use a newly generated encrypt/decrypt key (start with the word scramble example and alter it to provide this solution). Demonstrate good programming structure by inserting comments, using appropriate looping structures, and functions.
