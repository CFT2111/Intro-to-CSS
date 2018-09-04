# Intro to CSS

## Exercise 1
* Download and save the webpage [*tbl.html*](./tbl.html) (or use your own copy).  
* In a text editor create a new file, paste in the following
```css
body {
    font-family: Arial, Helvetica, sans-serif;
    background-color:#646464;
    color: #0295F3;
    line-height: 1.5;
}
```
* Save the file as *style.css* in the same directory as your copy of *tbl.html*.
* Return to your copy of *tbl.html*, add the following link element in the head the document
```html
<link href="style.css" rel="stylesheet" type="text/css">
```
* Save the HTML page and view it in a browser.
* The page should be 'styled'
* Add some additional CSS rules in *style.css* and experiment with different CSS properties. The number of CSS properties can be overwhelming for beginnners. To start with just try to make yourself familiar with:
    * **Text-related properties** : alignment, changing fonts, line height, letter spacing etc.
    * **Basic box properties** : border, outline, padding and margin
    * **Setting the color of elements** using color names, hexadecimal values, and RGB values. 
        * Use a simple image editor such as Paint to obtain RGB/hex values. 
    * See https://developer.mozilla.org/bm/docs/Web/CSS for more info. 

## Exercise 2
This exercise is all about using selectors. 
* Download [*population.html*](./population.html). 
* This is a simple HTML page 
* Create an external CSS file for this document and check this works i.e. add a simple rule for changing the background-color of the page.
* Now try the following:
    * Write a CSS rule that will set the font family of all the *li* elements to be Arial.
    * Write a CSS rule that will place a border around the *div* with the id attribute of *other_countries*.
    * Write a CSS rule that will colour all the *li* elements of the class *europe* red.
    * Write a CSS rule that will colour the background of all the *li* elements that are in an ordered list (*ol*) blue
    * Write a CSS rule that will colour the Word *seychelles* green 

**Don’t make any changes to the HTML! Use CSS selectors to select specific parts of the document.**

## Exercise 3
This exercise is about using multiple classes, a common technique in web design. 
* Download [*multiple-classes.html*](./multiple-classes.html) and [*multiple-classes.css*](./multiple-classes.css).
* Open the HTML page in a browser. Simply using the existing classes in the CSS file try the following:
    * Make the entire contents of the page Arial
    * Give the *h1* element a solid border
    * Put some space between the *h1* element and it's border 
    * Make the entire list have a background-color of red and a solid rounded border
    * Put some space between the list elements
    * Put some space around the last paragraph

**Don’t make any changes to the CSS! Use the class attribute to apply the existing CSS rules to the HTML elements.**