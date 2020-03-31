# Notes HTML Ch. 2
Tags (markups) provide extra meaning and allow browsers to display structure.

Structural markup: elements to describe headings and paragraphs.

Semantic markup: extra info like emphasis, quotations, etc.

## Structural Markup css
1. <h1> to <h6> </h>
  Headings (<h1> is a main heading, with higher numbers being subheadings that decrease in size when displayed).
  
2. <p> </p>
 Paragraphs
  
3. <b></b>
  bold

4.<i></i>
  italics
  
5. <sup>
  superscripts

6. <sub>
  subscript
 
7. <br />
  line break
  
8. <hr /> 
  horizontal rule (a horizontal line that separates elements.
  
*You can use a visual editor to control the presentation of text.*
*The info for whitespace collapsing on p.47 doesn't make sense to me based on the sample code*

### Semantic Markup- used inside elements css
1. <strong>
  bold
  
2. <em>
  italics
  
3. <blockquote> (used with cite attribute <blockquote cite="url">)
  for long quotes. Don't use to just indent a piece of text.
  
4. <q> (used with cite attribute, doesn't work with Internet Explorer)
  used for shorter quotes 
  
5. <abbr> (used with <abbr title="Professor">Prof</abbr>)
  For both abbreviations and acronyms
  
6. <cite>
  indicates where a citation is from when refrencing a piece of work like a book, film, research paper.  Renders these  elements in italics.
  
7. <dfn>
  indicates the defining instance of a new term (the first time you explain new terminology in a document)
  
8. <address>
  author details
  
9. <ins> (underlines content) and <del> (crosses out content)
  shows content that has been inserted and deleted, respectively.
  
10. <s> (crosses out content)
  something no longer accurate or relevant but shouldn't be deleted. 
  
  
  
#### Notes CSS ch. 10 
CSS allows you to create rules that specify how content should appear.

Imagine boxes around HTML elements, and use CSS to control how the box and its contents are presented.

The selector gets the HTML element and the declaration indicates how the selector should be styled:

    p {
      font-family: Arial;
      }
      
The declarations are inside curly brackets and contain and property:value pair.  
1. properties indicate the aspects of the element you want to change.
2. Values specify the settings you want to use.

You can use CSS externally as a link (tells the browser where to look to find the css elements to style the page) and can use more than one stylesheet in single HTML document:

    <link href="css/styles.css" type="text/css" rel="stylesheet" />
    
You can use CSS internally within HTML by placing them within a <style type="text/css"> element.  Only deal if building a site with only one page.
  
*CSS Selectors are on p. 238!*

Some rules will take precedence over others depending on the order in which they're presented.  Last rule = last selector of 2 identical selectors takes precedence.  More specifity = more precedence. !important

properties can be inherited.

Test in more than one browser to see how the proerties display.  There could be a browser quirk or CSS bug!



###### Basic JavaScript Instructions Ch.2
A script is a series of instructions the computer followes.  Each step = statement and should end with ;

Case sensitive!

//Write comments to explain what your code does. (single line)
/* multi line comments */

A variable stores bits of info that is likely to change.

Declare the variable with a keyword (const, let), define the variable (with a name that describes the kind of data it holds), use an assignment operator (like =), assign it a value.

    var quantity = 3;
    
 Data Types:
 1.'strings'
 2. numbers
 3. boolean (true/false)
 4. arrays (store ,ore than one piece of related info)
 5. expressions (evaluate into a single value, relies on operators to calculate the value).
 
 There is shorthand for creating variables (p.67)
 
 Variable values can be changed (p.68)
 
 Rules for naming variables (p.69)
 
 
 ####### Ch. 4 Decisions and Loops p. 145-162 js
 Code can take more than one path and the browser can run different code in different situations.
 
 To determine which path to take, use:
 1. evaluations
 2. decisions
 3. loops
 
Flowcharts can help plan which code to run next.

Decisions can be made by setting a condition.  If it returns true, take one path.  If it returns falso, take another.

comparison operators (<,>,==) allow you to compare values and test whether a condition has been met or not.

Conditional statements (p.149) determine what to do in a given situation using if, else statements.  
    if (someCondition > 50) {
      console.log('It's met');
      } else {
      console.log('it's not met');
      }
      
  comparison operators p. 150-151 (usually return single values of tue or false).
  
  logical operators p. 156-157 (allow you to compare results of more than one comparison operator).
  
  if statements p. 160 checks a condition. if true, runs the code block.
  
  if else statements p. 162 checks a condition.  if it resolves true, the first block is run.  if it resolves false, the second block is run instead.
  
  

    

 
 
