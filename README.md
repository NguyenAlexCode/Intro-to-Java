Java File = All of our code
.md file = definitions, text, ect...
## Intro to Java

A Java program can be characterized as an **object** represented as a **class**

Currently our program has a *Main* object. Inside of this object we have the *Main* Class

## Output
In Java to output an item to the consol we use: 'System.out.print()' and 
`System.out.println()` prints the statement and moves to the next line, while `System.out.print()` just prints the statement

## Comments
A comment is used as a user annotation with the purpose of being human readable.
**Line Comments** follow dobule backslashes `//`
**Block Comments** are contained within `/* Comments */` 

## Identifiers

In Java use the term **identifier** to describe a variable, parameter, constant, user-defined method or user-defined class. 

- Cannotbegin with digit
- Can only contain letters, digits, and underscores age
-Case-sensitive `age != Age` (age is not equal to Age)

*Note: *
- class name starts with a capital letter
- reserved words are entirely lowercase and may not be used as identifiers ( Reserved words will show up in blue.)

## Types
**Primitive** or **built-in** types in Java are 
- `int` An integer
- `bollean` True or False (boolean shirtColor = false)
- Write lowercase for boolean when saying true or false 
- `double` floating-point number (2.73) (compared to float in Python)
- `char` single character

*Note: * Integers have a fixed amount of memory, so there is a limit to how many digits you can store(2^31-1)

## Variables
Variables are a type of indentifier that stores a value of a specific type

we can create variables using **declarartion**
- `int age;` We can declare the variables with type and identifier without declaring the value unlike Python
- `double x, y;` 
- `boolean found;`
- `char letter;`

We can also inialize a variable in its **declaration**
- `int count = 1;`
- `double p = 3.14;`
- `char c = '8';`

Each character is associated with an ASCII value https://docs.google.com/document/d/1oubLTqAHmdkadtjbR8xxREG7auvuUqiQ/edit

## Type cast

One type can be cast to another compatible type if appropriate

`char letter = 'c'` 
```

int total, n;

`double average;`
`average = (double)total/n //total cast to double to ensure real division is used`
```

*Note: * Casting a floating-point number to an integer simply truncate the number (rounds down)

## Final Variables 
A *final variable* or *user-defined constant*, udentified by the keyword `final`, is a quantity whose value will not change. 
`final double TAX_RATE = 0.08;`

- Constant identifiers are, by convention, capitalized
- `final` variable can be declared without initializing immediately








































