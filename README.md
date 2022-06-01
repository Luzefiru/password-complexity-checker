# Password_Complexity_Checker
## Allows the user to check whether their password meets the criteria according to: https://silkstartsupport.zendesk.com/.

### The password's "complexity score" ranges from 1 to 5. When a criterion is met, the score increases by 1 point. The "complexity score" is printed during the end of the program.

### Here is the current criteria:
- has 12 characters
- has 1 uppercase letter
- has 1 lowercase letter
- has 1 number
- has 1 special character

### It also prints helpful tooltips if a user inputs invalid characters. Here are the available ERROR messages:

>*"ERROR: You inputted nothing. Try again!"*

// when the user inputs nothing ("") & just presses enter on the input prompt, the program exits.

>*"ERROR: No spaces allowed. Try again!"*

// when the input contains spaces, the program exits.

>*"ERROR: Your password needs to be >= 12 characters! Please try again!"*

// when the user's password has less than 12 characters, the program exits.

>*"ERROR: Your password must only include ASCII characters!"*

// when the user's password contains non-ASCII characters, the program exits.

### This is a fun little program I thought of after diving deeper into <class 'str'> data types in my Python Programming course.
