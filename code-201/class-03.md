# Class 3

### When should you use an unordered list in your HTML document?
Lists of items without a particular order
Items of equal importance
Things like Nav menus

### How do you change the bullet style of unordered list items?
Use the `list-style-type` property. There are a few to choose from with autocomplete.

### When should you use an ordered list vs an unorder list in your HTML document?
Use ordered lists for things listed in order of importance. For example: 1st, 2nd and 3rd places in a bicycle race.
Use unordered lists when it really doesn't matter. Like a grocery list where all things have equal importance.

### Describe two ways you can change the numbers on list items provided by an ordered list?
CSS Counter Styles: CSS allows you to customize the appearance of the numbers in ordered lists using the list-style-type property. Some common values include:

decimal: This is the default style, displaying the list items with Arabic numerals (1, 2, 3, ...).
decimal-leading-zero: Similar to the decimal style, but ensures that single-digit numbers are prefixed with a leading zero (01, 02, 03, ...).
lower-roman: Displays list items with lowercase Roman numerals (i, ii, iii, ...).
upper-roman: Displays list items with uppercase Roman numerals (I, II, III, ...).
lower-alpha: Displays list items with lowercase alphabetical characters (a, b, c, ...).
upper-alpha: Displays list items with uppercase alphabetical characters (A, B, C, ...).

HTML Attributes: You can also use the type attribute directly within the <ol> tag to specify the numbering style. This allows you to override the default numbering style set by CSS for that specific list.

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Margin is how far away the box is from the walls of the room it's in.
Padding is how far away I am from the walls of the box I'm in which is in the aformentioned room.

### List and describe the four parts of an HTML elements box as referred to by the box model.
Content, border, padding, margin.

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
The easy answer is that margin is the space between castles (containers)
Padding is the space on the intererior of the castles.

### What data types can you store inside of an Array?
In JavaScript, you can store various data types inside an array, including:

Numbers: Integer or floating-point numbers.
Strings: Textual data enclosed in single ('') or double ("") quotes.
Booleans: True or false values.
Objects: Complex data structures containing key-value pairs.
Arrays: Nested arrays can be stored within an array.
Functions: JavaScript functions can be stored as elements in an array.
Undefined: The default value assigned to uninitialized elements.
Null: A special value representing the absence of any value.
Symbols: Unique and immutable data types introduced in ES6.
Arrays in JavaScript are flexible and can contain a mix of different data types, allowing you to organize and manipulate heterogeneous data collections efficiently.

(I copied this straight from ChatGPT. I can't improve on the answer. I did know Number and Strings before looking it up, though!)

### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
The people array is valid in JavaScript, representing information about individuals in a two-dimensional array format. To access specific values, use array indexing, specifying both the outer array index (for each person) and the inner array index (for specific details like age, name, etc.).

### List five shorthand operators for assignment in javascript and describe what they do.
<=, >=, +=, -= (I didn't have to look this up. This kind of thing is an assignment operator.

### Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
ChatGPT has great answer to this:
To evaluate (a + c) + b, we follow the order of operations (also known as operator precedence) in JavaScript:

a is a number (10).
c is a boolean (false). When used in a numerical operation, JavaScript treats false as 0.
a + c equals 10 + 0, which equals 10.
b is a string ('dog').
Adding 10 and 'dog' together concatenates them into a string, resulting in '10dog'.
So, (a + c) + b evaluates to '10dog'.

### Describe a real world example of when a conditional statement should be used in a JavaScript program.
In the casino game of craps, a conditional statement can be used to determine whether a player wins or loses based on the outcome of the dice roll.

Here's an example:

javascript
Copy code
let dice1 = /* roll the first die */;
let dice2 = /* roll the second die */;
let sum = dice1 + dice2;

if (sum === 7 || sum === 11) {
    // Player wins if the sum is 7 or 11
    console.log("Congratulations! You win!");
} else if (sum === 2 || sum === 3 || sum === 12) {
    // Player loses if the sum is 2, 3, or 12 (known as "craps")
    console.log("Sorry, you lose. Better luck next time!");
} else {
    // Any other sum becomes the "point" and the game continues
    console.log(`Your point is ${sum}. Keep rolling!`);
}
In this scenario, the conditional statement checks the sum of the dice roll. If the sum is 7 or 11, the player wins. If the sum is 2, 3, or 12 (known as "craps"), the player loses. Otherwise, the sum becomes the "point," and the game continues until the player either rolls the point again (wins) or rolls a 7 (loses). This conditional statement helps determine the outcome of the game for the player.

### Give an example of when a Loop is useful in JavaScript.
It would be like if that dude Vinnie from down the block who owes me money and I've asked him for it, like, 10 times... I ask him for it again and at this point I have to limit his failure to pay by telling him I'm only going to ask once more.

  Vinnie owing money: This represents the repetitive task or action that needs to be performed multiple times.
  Asking Vinnie for money multiple times: This mirrors the iterative nature of a loop, where the same action is   executed repeatedly.
  Limiting the number of times: This corresponds to setting a condition within the loop to control how many       times the action is repeated. Once the condition is met (e.g., asking Vinnie one last time), the loop stops.
