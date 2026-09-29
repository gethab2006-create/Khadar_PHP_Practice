# PHP Variables, If-Else & Switch Practice

## Overview

This beginner-friendly PHP project demonstrates variables, output, conditional statements, and switch-case logic.

## Code




Code Explanation

 1. Variables

php
$name = "Ali";
$age = 20;

`$name` stores the text value "Ali".
`$age` stores the integer value 20.
PHP variables begin with the dollar sign (`$`).

2. Output with echo

php
echo $name;
echo $age;

The `echo` statement displays information on the webpage. Since there is no space or line break, the output appears as `Ali20`.

3. Comparing Numbers

php
$num1 = 10;
$num2 = 20;

These variables store two numbers that will be compared.

4. If-Else Statement

if...else statement allows PHP to make a decision based on a condition.

- If `$num1 > $num2` is true, the first block runs.
- Otherwise, the `else` block runs.

Since 10 is not greater than 20, the output is: `20 is greater than 10`.

 5. Switch Statement

switch statement compares a variable against several possible values.

$day = 3 sets the selected day number.
case 1 through case 5 represent weekdays.
break stops execution after a matching case.
default` runs when no case matches.

Because the value is 3, the program displays `Wednesday`.

 Expected Output

Ali20
20 is greater than 10
Wednesday
```

