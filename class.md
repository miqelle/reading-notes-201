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
`total = price * quantitiy;`

`var el = document.getElementById('cost');`
`el.textContent = '$' + total;`

