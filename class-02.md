 ## HTML Chapter 2  *(Text)*

The HTML tags we use when creating a website allow the browsers to display the appropriate structure of the page. Tags are known as markup.  Structural markup used to describe headings and paragraphs and semantic markup, used to provide additional information such as quotations, emphasis, abbreviations, etc.  These elements should not be used to affect the structure of the webpage. 

Questions: what is the difference between the \<b>\</b> and \<strong>\</strong> elements? 

## HTML Chapter 10 *(Introducing CSS)*

CSS is used to styled HTML. Just like HTML, there are several versions of CSS. The most current version is CSS3. It is better to put the CSS rules in a different file, although it is possible to put in the same file where the HTML is. One of the advantages of creating a separate file is that you can use the same file for different pages, keeping consistency between all of them. Also, it is easier when it comes to making changes. If you do not use a CSS rules in a separate file, you would need to update every single page to update 1 CSS rule. 

When using external CSS, you need to use the \<link> element in the HTML page to tell the browser where to look for the CSS rules. To use internal CSS, you’ll need to write the rules between the \<style> element. 

Some rules are considered more specific than other rules in CSS. Generally, an id is more specific than a class, and a class is more specific than an element rule. If 2 rules are the same, the latter will take place. Important can be added to any property value to make sure it is more specific than any other rule that applies to the same element. 

## JavaScript Chapter 2 *(Basic Instructions)*

A script is a series of steps that computers follow one by one. Each step is called a statement. 
Variables need to be declared. IE: var age; Variables can have an assigned value. IE: var age = 18; Values can change and will be stored in short term memory. Variables can be numeric, strings, or boolean (true or false), or undefined. Multiple variables can be declared and assigned in 1 line of code, but it makes it harder to read. There are rules for naming variables:
-	Name can start with a letter, $, _, not with a number
-	Name cannot contain a dash (–) or a period (.)
-	Cannot use keywords or reserved words
-	All variables are case sensitive
-	Use a name that describes the information to be stored
-	If a variable name contains 2 or more words, the name is usually written using camelCase

Questions: what is the difference between array literal and array construction?

## JavaScript Chapter 4 (Decisions and Loops)

Scripts behave differently depending on how the user interacts with a website. To determine what path to take in a script, we use: evaluations, decisions, loops. 
If vs switch. With a series of if statements, they are all checked, even if a match has been found. It performs slower. With switch, we have a default option in case none of the cases match. When a match is found that code is run, and the break statement stops the other switch statements running. This improves performance.