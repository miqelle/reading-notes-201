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

## Synopsis: * can be used to style all elements on your page, and . or # is used to style specific elements!

# JavaScript

**Basic JavaScript Instructions**

- A *script* is a set of step by step instructions written for the computer to follow one by one
- Each individual step is a *statement*
- Statements should end with a semicolon

