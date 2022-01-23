<!---
# Marks the first heading Level 1
...
down to 
....
###### level 6

Blank lines create paragraphs

**bold** will give you bold text

*italics* will give you a single italic

***bold and italic*** will give you bold and italic

> will give you blockquote

Just add > and > for each line for multi line block quote


To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.

If you need to start an unordered list item with a number followed by a period, you can use a backslash (\) to escape the period.

Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.markdownguide.org>
<fake@example.com> 
--------------------------------------------------------------------------------->

# JS Tutorials by Zibusiso Masuku

## What is this file?
 All things to learn JS, biased for DS

## What I learnt? **The CHEAT Sheet**

### Commenting Code
`// This is a comment` This is how you comment out code in JS. This is an example of a single line comment.

This is an example of  multi-line comment block  
`/* This is a  
multi-line comment */` 

### How do you print messages to console?
`console.log("Hello World")` What is a cheat sheet without printing the iconic `Hello World`

> **TIP** Just so you know: JS stores all numbers to 64-bit floating points, so this means they are almost always accurate to about 15 dp. _Not_ all real numbers can accurately be represented in floating point. This can lead to rounding errors.

### Operators and Functions
In JS there are operators and functions.

Operators just work with the object and functions need parentheses (or brackets).

Examples include `const`, `typeof`, etc.

### Data Type
Unlike R, C or Python, etc (that have floats, integers, etc.); JS stores all numbers under one data type `number`.

Other data types are:
- `boolean` returns the standard `true` or `false`
- `undefined` a very special function that means we have not yet decided what our object is, probably will not.
- `string` for text
- `null` when we intentionally want nothing
- `symbol` is an immutable primitive value that it unique.
- `object` can store various data types into one element. This is your equivalent of a list.

### Declaring Variables
`var` is used to declare variables for the whole program.
`let` is used within the context of where you declared it. Say, within a function or within a loop.
`const`is used to declar variables that will not change. If you attempt to change it, you will get an error.s

> **Tip** You end all line with `;`, it's not required but helps your readability.

> **Tip** JS is case sensitive. `camelCase` is usually the common style!

### Math Operators 
- `+` addition (*This can also be used to concactenate strings*)
- `-` subraction
- `*`multiplication
- `/` division
- `%` remainder
> **Tip** _Note_: The remainder operator is sometimes incorrectly referred to as the modulus operator. It is very similar to modulus, but does not work properly with negative numbers.
- `**` exponiantion 

#Incrementing and decrementing
myVar++ is same as sayig myVar = myVar + 1
myVar-- is same as saying myVar = myVar - 1
If you want to say myVar = myVar + 5, you can just say myVar += 5. True for division, subtraction, remainder and exponentiation.


> **Tip**  It is common for developers to use UPPERCASE variable identifiers for immutable values and lowercase or camelCase for mutable values (objects and arrays).

### Escaping Literal Quotes in Strings
When you need to escape literal quotes in strings, a code like this:
`const sampleStr = "Alan said, \"Peter is learning JavaScript\"."`

Will give you the following result:
`Alan said, "Peter is learning JavaScript".`

### Escaping other sequences in strings
Quotes are not the only element that can be escaped, the following can be escaped

-`\'` single quote
-`\"` double quote
-`\\` backslash (*do not confuse with forward slash `/`*)
-`\n` new line
-`\r` carriage return
-`\t` tab
-`\b` word boundary
-`\f` form feed

### Properties
I prefer to call these dot operators ( or at least I read so somewhere.)

For insance, you ca use the `.length` to find the length of a string.

Say myStr = "I love to code". then `console.log(myStr.length)` would be `14`

### Bracket Notation
Computers count from 0. So in a string assigment `myName = "Charles"`, `myName[0]` gives `C`.

> **Tip** In JavaScript, String values are immutable, which means that they cannot be altered once created. For instance, if `myStr = "Job"`, `myStr[0] = "B"` will lead to errors.

### Arrays
Arrays allow JS to store several variables at once. Ideally, this is how you would use them:
`const investments = ["risk", "reward", "return"]`

You can also nest arrags within each other, say:
`const grades = [["Maths", 96], ["Physics", 100]]`

> **Tip** You can use the same bracket notation to extract indices of array elements. You simply add additional square brackets for additional elements in a nested array.

### Manipulating Arrays
Using the `push()` function, will add data to the end of an array.

For instance:
`var myBananaBread = ["flour", "eggs", "butter", "banana"]`

Say our chef, tell us that Banana Bread tastes nicer with cinnamon, we can then use the `push()` function to add that element as follows:
`myBananaBread.push("cinnamon")`

The value of `myBananaBread` will now be `["flour", "eggs", "butter", "banana", "cinnamon"]`

## Where you can learn more?
1. Online free book [**JavaScript for Data Science**](https://js4ds.org/ "JavaScript for Data Science")
2. freeCodeCamp's [**JavaScript Algorithms and Data Structures**](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/ "JavaScript and Data Structures")
3. Learn JavaScript - Full Course for Beginners on YouTube [**Link here**](https://youtu.be/PkZNo7MFNFg "Play Learn JavaScript - Full Course for Beginners on YouTube")


