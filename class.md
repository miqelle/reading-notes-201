# Basics of HTML, CSS, and JavaScript

**HTML**

- When creating a web page you add tags to the contents of the page
- Tags provide extra meaning and tells the browser to show your info a certain way

**Structural Markup**: the elements that you can use to describe headings and paragraphs

**Semantic Markup**: Provides extra info about how your text should look like quotation marks, and where emphasis is placed in a sentence.

**HTML Tag List**

- Headings vary from sizes 1-6 
- Headings are created with an opening and closing tag like this: `(<h1></h2>)`
- Paragraph tag `(<p></p>)`
- Bold tag which makes text bold `(<b></b>)`
- Italic tag which makes text *italic* `(<i></i>)`
- Q tag is used to put quotes around text `(<q></q>)`

**CSS**

- CSS is used to style your webpage
- CSS treats each element as if it lives inside its own box.
- A CSS rule contains two parts: a **selector** and a **declaration**
- The selector is the HTML element you want to style such as (h1, h2, or p)
- The declaration tells the browser how your selected element should be styled

- CSS declarations are made up of two parts: **property** and **value**, separated by a colon

`h1, h2, h3 {
    font-family: Arial;
    color: yellow;
}`

- Properties are the things you want to change such as the color of the text, font, width, height, and border. 

- Values are the specific setting you want such as wanting your h1 element to be *yellow* (Yellow is the value here)

**List of CSS Selectors**

- `* {}`: This targets all elements on a page
- `h1. h2, h3 {}`: This targets specific elements on a page
- `.note {}`: This targets all elements whose class has the *note* value
- `#introduction {}`: This targets the element with the id value of *introduction*. 

Synopsis: * can be used to style all elements on your page, and . or # are used to style specific elements!

# JavaScript

**Basic JavaScript Instructions**

- A *script* is a set of step by step instructions written for the computer to follow one by one
- A script temporarily stores info needed in **variables** 
- Use *let* to declare a variable you may want to change later
- Use *const* to declare a variable you want to stay the same
- You must also name your variable, and the name cannot be any JavaScript keywords
- A variable's name should describe the kind of data the variable holds
- After that you assign your variable a value (the info you would like it to store)
 
 Example of variable declaration:
`let quantity = 3;`

**JavaScript Data Types**

- Number: includes all numbers, positive, negative, and decimals
- String: anything inside quotation marks 'What is you name?'
- Boolean: only have a true or false value

**How to use a variable to store a number**

`var price;`
`var quantity;`
`var total;`

`price = 5;`
`quantity = 14;`
`total = price * quantity;`

`var el = document.getElementById('cost');`
`el.textContent = '$' + total;`

**Quick Tip: Strings must ALWAYS be written on one line **

**`innerHTML` can be used to add HTML to a page**

**Boolean info**

- A Boolean variable can only have the value of true or false
- Booleans are used when the value can only be true/false
- Booleans are also used when your code can take more than one path (Different code runs in different circumstances)

**Variable Name Rules**

- The name must begin with a letter, dollar sign, or an underscore
- It cannot start with a number
- The name can contain letters, numbers, dollar sign, or an underscore
- You cannot use a dash or a period
- You cannot use keywords or reserved words
- Use a name that describes the kind of info the variable stores
- Use camel case like this `(userName)` or underscore `(user_Name)`

**Arrays**

- An *array* doesn't store just one value, it stores a list of values
- Use an array whenever you are working with a set or list of values that are related to each other
- Values in an array are separated by commas

Example of an Array: 

`var colors;`
`colors = ['white', 'black', 'custom'];`

`var el = document.getElementById('colors');`
`el.textContent = colors[0];`

- When you create an *array* give it a name
- Values are assigned to the array inside a pair of brackets [*values go here*]
- A boolean, number, and string can go in the same array because values in an array do not have to be the same data type


**Array literal Example:**

`colors = ['white',`
           `'black',`
           `'custom'];`


- Each item in an array is automatically given a number called an index
- The index is used to access a specific array item

**Array Index Example:**

`var colors = ['white',`
           `'black',`
           `'custom'];`

| Index  | Value   |
|--------|---------|
| 0      | 'white' |
| 1      | 'black' |
| 2      | 'custom'|


- As shown in the example above, index values start at 0 not 1
- To retrieve an item on a list, specify the array name along with the index number in square brackets

`var itemThree;`
`itemThree = colors[2];`

- Each array has a property called **length**, which holds the number of items in the array
- You can change the value of an item in an array by selecting it and assigning it a new value

**Expressions**

- An expression evaluates into a single value.

**Example**
`var area = 3 * 2;`

- Expressions rely on **operators** 

**List of operators**

- Assignment Operators: `=`
- Arithmetic Operators: `*`
- String Operators: `greeting = 'Hi ' + 'Molly';`
- Comparison Operators: `buy = 3 > 5;`
- Logical Operators: `buy = (5 > 3) && (2 < 4);`

**Decisions & Loops**

- In a script the code can take more than one path
- To determine which path to take, programs often rely upon the following three concepts

**Evaluations:** Analyze if values match expected results
**Decisions:** Use the results of evaluations to decide which oath the script should go
**Loops:** Perform the same steps repeatedly

**Decision Making**

- Flow charts can be used to plan decision points in your script
- A condition must be set to determine which path to take in a script
- You can check if one value is equal to, greater than, or less than another. If the condition returns `true`, you take one path; if it is `false` you take another path
- Comparison operators are used to compare values and test whether a condition is met or not

**Evaluating Conditions & Conditional Statements**

There are two components to a decision:

1: An expression is evaluated, which returns a value
2: A conditional statement says what to do in a given situation

**Evaluation of a Condition**

- In order to make a decision your code checks the current status of the script
- This is usually done by comparing two values using a comparison operator which returns a value of true or false

**Conditional Statements**

- Conditional Statements are based on the if/then/else concept
- If a condition is met, then you code executes one or more statements, else your code does something different or just skips the script

**Comparison Operators:**

- `===` Strict Equal to  
- `!==` Strict NOT equal to

**Logical Operators**

- `&&` Logical AND tests if two expressions evaluate to true. If one expression is false, then the whole thing returns false!
- `||` Logical OR tests if one of two expressions evaluates to true. If at least one IS true, the entire expression returns true


**Extra Facts**

- Logical expressions are evaluated left to right
- The *if statement* evaluates a condition. If the condition is true, it runs the first code in curly braces
- The *if...else* statement checks a condition. I fit resolves to true the first code block is executed. If the condition resolves to false the second code block is run instead
- An *if statemtent* only runs a set of statements if the condition is true
- An *if...else* statement runs one set of code if the condition is true or a different set if it is false





