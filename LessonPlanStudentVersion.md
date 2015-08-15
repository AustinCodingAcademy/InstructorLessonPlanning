# 5E Model Lesson Plan – Lofton and Joe
 
* **Objective:** Students will use variables to represent values.
* **Prereading:** Students will read about variables and values from the following specific articles and make detailed notes of each article.
They will save these notes in a folder entitled “ACABackEndIntro” named “Variables_8_16_2015.txt”

* http://www.tutorialspoint.com/php/php_variable_types.htm 
* http://www.tizag.com/phpT/echo.php 
* http://php.net/manual/en/language.variables.basics.php (Up to “User Contributed Notes”)
* http://stackoverflow.com/questions/505642/escape-html-to-php-or-use-echo-which-is-better
* http://thedailywtf.com/articles/Confessions-The-Phone-Number 


## Instructional Plan

### Engage
 
*Slideshow about values

### Explore

* Show a webpage- Which values do you see? / Can we classify them in any way?
    + https://twitter.com/ 
    + https://twitter.com/settings/account



* What if I wanted to change my name on my twitter, how many different times would I have to rewrite it?

### Explain

* What if I wanted to change my name on my twitter, how many different times would I have to rewrite it?

* What is a variable?

**Exercise** Look up http://php.net/manual/en/language.variables.basics.php.  Define 3 variables that represent strings and 3 variables that represent integers based on the info you find on the website. (10 min)

**Exercise**: A local pizza joint, East Side Pies, has hired you to create an online ordering system for their store. Use your personal experiences with ordering food online to determine what variables would be required to fulfill the customer’s order. Assign example values to the variables to demonstrate how you intend the variables to be used.
(10 min)

Break
 
### Elaborate

* Make "I love learning PHP!" show up on a webpage.
    + First do the string as-is
    + Let students search and talk with each other.
    + Once a number of students do it, discuss with students how to do it 
    + Next, start with `$phrase = "I love learning PHP!"` and ask them to accomplish the same task
* Ask students why using a variable works - does PHP treat it differently?

Key Points:

* text in quotations
* variable name is started with $
* `echo` is used to make things show up on the screen.
* you don’t need to put the quotations around the variable. You can just use the variable. In this case, it’s `echo $phrase`;

* Hard-coding
    + Using literal values throughout the code

* Why variables are preferred to hard-coding
    + Readability - no “magic” numbers
    + Flexibility - program automatically adapts to changes in variable values
    + Safety - reduces the chances of forgetting to update sections of code when changes are necessary

Further assignments:

* Create 3 variables that store integers. Use `echo` to make them show up on the webpage.
* Create 3 variables that store floats. Use `echo` to make them show up on the webpage.
* Create 3 variables that store strings. Use `echo` to make them show up on the webpage.
* Create 3 variables that store booleans Use `var_dump` to make them show up on the webpage.

**Note**: Can’t echo out boolean variables, have to use var_dump.

* Discussion: Why do you think PHP requires strings to be surrounded in quotes?
* Discussion: Why do you think integers and floating points are split into separate
types instead of just having a single “number” type?

Do exercise #5

* Numbers vs numeric strings
    + phone numbers
    + credit card numbers
    + Story of Dallas friend

### Evaluate

Define a set of variable with values in the form of strings, integers, and floats. Then echo their value inside of the story below. 

```php
<?php

echo "Jack and Jill went up the _____. They would have driven their ____, but it cost ____,
so they could not afford it. The temperature was ____ degrees, so they were very ____.
In fact, they were so ____ that they decided not to climb the ____ and instead
spent ____ dollars on a ____ and used it to _____. Jack and Jill lived _____ _____ ______";

?>
```

Important Vocabulary:

* Strings
* Integers
* Variables


Students will read about variables and values from the following specific articles and make detailed notes of each article.
They will save these notes in a folder entitled “ACABackEndIntro” named “Variables_8_16_2015.txt”

* http://www.tutorialspoint.com/php/php_variable_types.htm 
* http://www.tizag.com/phpT/echo.php 
* http://php.net/manual/en/language.variables.basics.php (Up to “User Contributed Notes”)
* http://stackoverflow.com/questions/505642/escape-html-to-php-or-use-echo-which-is-better
* http://thedailywtf.com/articles/Confessions-The-Phone-Number 

### Exercise 1

1. Save each letter of the alphabet into a variable (ex. `$alpha1 = "a"`, `$alpha2 = "b"`, etc.)
2. Use the variables created in step 1 to display the alphabet in order in the browser.
3. Use the variables created in step 1 to display the alphabet in the browser in reverse order.
4. Assign your name to a variable and use the variable to display your name in the browser.

### Exercise 2

1. Save all the multiples of 8 into variables (ex. `$multiple1 = 8`, `$multiple2 = 16`, etc.) up to 96.
2. Display all the multiples of 8. 
3. Display every other multiple of 8.

### Exercise 3

1. Read about concatenation: 
2. Use it to join strings/integers - add a few examples here

### Exercise 4

Create a glossary to keep track of all the academic vocabulary we learn.

1. Create a new file on your computer called “ACA”.
2. Create a new document and save it as “Glossary”.
3. Add these words to your glossary:
    * Strings
    * Integers
    * Variables
    
Find definitions for each of the words. Include coding examples.

### Exercise 5

For each question below, store your answer to the question in an appropriately named variable:

1. What is your favorite color?
2. Who is your favorite band or musical artist?
3. Which year were you born?
4. Do you listen to Led Zeppelin once a week?
5. Do you follow Kim Kardashian on instagram?
6. What is your phone number?
7. What is your favorite drink? We might bring it to you if you do good enough in class? (probably not - don’t expect it)
8. What is the number portion of your street address?
9. What is your favorite number?
10. What is the product of 1,234 and 845?
11. If you have $500 in your bank account and a deposit of $750 is made, how much is now in your bank account? (Include currency in your answer)
