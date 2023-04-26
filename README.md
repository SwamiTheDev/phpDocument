
## PHP Documentation  

This PHP document provides an overview of the PHP programming language and its syntax. It includes examples and exercises to help you understand and practice using PHP.

### Prerequisites

To use this document, you should have a basic understanding of programming concepts such as variables, data types, functions, and control structures.

You should also have PHP installed on your computer. If you don't have PHP installed, you can download it from the official PHP website: https://www.php.net/downloads.php.

### Getting Started

To get started, open a new PHP file in your text editor of choice. You can save the file with any name you like, as long as it has a .php extension.

In your PHP file, you can start writing PHP code. PHP code is enclosed in <?php and ?> tags. For example:

```php
<?php
// PHP code goes here
?>
```

### Variables

Variables in PHP are used to store values that can be used later in the program. Variables in PHP are declared using the $ symbol, followed by the variable name. For example:

```php
<?php
$myVariable = "Hello World";
?>
```

### Data Types

PHP supports various data types, such as strings, integers, floats, booleans, and arrays. You can declare a variable with a specific data type using the type before the variable name. For example:

```php
<?php
$stringVariable = "Hello World"; // string
$intVariable = 42; // integer
$floatVariable = 3.14; // float
$boolVariable = true; // boolean
$arrayVariable = array(1, 2, 3); // array
?>
```

### Functions

Functions in PHP are used to encapsulate a block of code and make it reusable. PHP has many built-in functions, such as echo, strlen, and substr. You can also create your own functions using the function keyword. For example:

```php
<?php
function myFunction($parameter1, $parameter2) {
  // code to be executed
  return $result;
}
?>
```

### Control Structures

Control structures in PHP are used to control the flow of a program. PHP has various control structures, such as if/else statements, loops, and switch/case statements. For example:

```php
<?php
if ($variable == "value") {
  // code to be executed if condition is true
} else {
  // code to be executed if condition is false
}

for ($i = 0; $i < 10; $i++) {
  // code to be executed repeatedly
}

switch ($variable) {
  case "value1":
    // code to be executed if variable is value1
    break;
  case "value2":
    // code to be executed if variable is value2
    break;
  default:
    // code to be executed if variable is not value1 or value2
    break;
}
?>
```

### Sample Exercise

Here is a sample exercise that you can use to practice writing PHP code. In this exercise, you will create a function that takes two parameters and returns the sum of the parameters.

```php
<?php
function sum($num1, $num2) {
  $result = $num1 + $num2;
  return $result;
}

echo sum(2, 3); // Output: 5
?>
```

In this example, the sum function takes two parameters, $num1 and $num2, and returns the sum of the parameters. The echo statement calls the sum function with the arguments 2 and 3, and outputs the result, which is 5.
