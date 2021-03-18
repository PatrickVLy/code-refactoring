# Code-Refactoring

## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
<hr>

## Acceptance Criteria
GIVEN a webpage meets accessibility standards<br><br>
WHEN I view the source code<br>
THEN I find semantic HTML elements<br><br>
WHEN I view the structure of the HTML elements<br>
THEN I find that the elements follow a logical structure independent of styling and positioning<br><br>
WHEN I view the image elements<br>
THEN I find accessible alt attributes<br><br>
WHEN I view the heading attributes<br>
THEN they fall in sequential order<br><br>
WHEN I view the title element<br>
THEN I find a concise, descriptive title<br><br>
<hr>

## Description

### Step 1: 
***WHEN I view the source code<br>
THEN I find semantic HTML elements***

What I did for this step was broke the page up into diffrent sections using these tags:
<br> ```<header></header>```<br>
<br> ```<nav></nav>```<br>
<br> ```<section></section>```<br>
<br> ```<aside></aside>```<br>
<br> ```<article></article>```<br>
<br> ```<footer></footer>```<br>

### Step 2: 
***WHEN I view the structure of the HTML elements<br>
THEN I find that the elements follow a logical structure independent of styling and positioning***

What I did here was edited the HTML code to improve the logical structure and flow of elements. I moved the ```<aside></aside>``` element so that it goes right after the ```<section></section>``` element


### Step 3: 
***WHEN I view the image elements<br>
THEN I find accessible alt attributes***<br><br>
What I did here was added alt attributes to all the ```<img>``` Tags

### Step 4:
***WHEN I view the heading attributes<br>
THEN they fall in sequential order***

What I did here was to make sure headings were used correctly in sequential order. <br>
ie.  ```<h1>```,```<h2>```,```<h3>```, and ```<h4>```

### Step 5:
***WHEN I view the title element<br>
THEN I find a concise, descriptive title***

Lastly, I edited the title to "Horiseon - Digital Media Marketing" so that the page has a clear, descriptive title. 



