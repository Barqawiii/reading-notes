13 march 
# Introduction:
## How People Access the Web :
1. **Browsers**
> People access websites using software called a web browser.
> Popular examples include Firefox, Internet Explorer, Safari, Chrome, and Opera.

2. **Web Servers**
> Web servers are special computers that are constantly connected to the Internet, and are optimized to send web pages out to people who request them.

3. **Devices**
> People are accessing websites on an increasing range of devices including desktop computers, laptops, tablets, and mobile phones.

4. **Screen readers**
> Screen readers are programs that read out the contents of a computer screen to a user. They are commonly used by people with visual impairments.

----------------------------------
## How Websites Are Created :

> All websites use HTML and CSS, but content management systems, blogging software, and e-commerce platforms often add a few more technologies into the mix.
 
## How the Web Works :

> When you visit a website, the web server hosting that site could be anywhere in the world.
> In order for you to find the location of the web server, your browser will first connect to a Domain Name System **(DNS)** server

![pic1](r01-1.png)
---------------------------------
------------------------------------------
# Structure
*HTML Uses Elements to Describe the Structure of Pages*

*There are several different elements. Each 
element has an opening tag and a closing tag.*

![pic2](r01-2.png)

## Attributes 
*Tell Us More About Elements*
> Attributes provide additional information 
about the contents of an element. They appear 
on the opening tag of the element and are 
made up of two parts: a name and a value, 
separated by an equals sign.

![pic3](r01-3.png)

## Body, Head & Title
![pic4](r01-4.png)

---------------------
----------------------

# Extra Markup
### 1. DOCTYPEs
> tell browsers which version of HTML you are using.
```
<! DOCTYPE html>
```
### 2. Comments 
```
<!--This is a comment -->
```
### 3. ID Attribute
> - Every HTML element can carry  the id attribute. It is used to  uniquely identify that element  from other elements on the page .
> - id attributes can be 
used to allow the script to work 
with that particular element.
```
<p id="pullquote">Every time I view the sea I feel 
 a calming sense of security, as if visiting my 
 ancestral home; I embark on a voyage of seeing.
</p>
```

### 4. Class Attribute
> Every HTML element can 
also carry a class attribute
```
<p class="important">For a one-year period from 
 November 2010, the Marugame Genichiro-Inokuma 
 Museum of Contemporary Art (MIMOCA) will host a 
 cycle of four Hiroshi Sugimoto exhibitions.</p>
 ```
### 5. Block Elements
> + Some elements will always 
appear to start on a new line in 
the browser window. These are 
known as block level elements. 
> + Examples of block elements are : 
```
<h1>, <p>, <ul>, and <li>.
```

### 6. Inline Elemnts 
> Some elements will always 
appear to continue on the 
same line as their neighbouring 
elements. These are known as 
inline elements.
Examples of inline elements are :
```
<a>, <b>, <em>, and <img>.
```
### 7. Grouping Text & Elements In a Block
> The < div > element allows you to  group a set of elements together in one block-level box.

![pic5](r01-5.png)
### 8. Grouping Text & Elements Inline
 ![pic6](r01-6.png)
### 9. Iframes
> An iframe is like a little window 
that has been cut into your 
page — and in that window you 
can see another page. The term 
iframe is an abbreviation of inline 
frame.
```
<iframe 
width="450" 
height="350" 
src="http://maps.google.co.uk/maps?q=moma+new+york&amp;output=embed">
</iframe>
```
![pic7](r01-7.png)
### 10. meta 
> + The < meta > tag allows you to supply all kinds of 
information about your web page.
> + The < meta > element lives 
inside the < head > element and 
contains information about that 
web page.

-----------------------
----------------------
# html5 layout
### HTML5 introduces a new set of elements that allow you to divide up the parts of a page.

![pic8](r01-8.png)

### Headers & Footers :
> The < header > and < footer >
elements can be used for:
> + The main header or footer 
that appears at the top or 
bottom of every page on the 
site.
> + A header or footer for an 
individual < article > or 
< section > within the page

### navigation : 
> The < nav > element is used to 
contain the major navigational 
blocks on the site such as the 
primary site navigation

```
<nav>
<ul>
 <li><a href="" class="current">home</a></li>
 <li><a href="">classes</a></li>
 <li><a href="">catering</a></li>
 <li><a href="">about</a></li>
 <li><a href="">contact</a></li>
</ul>
</nav>
```
### Figures :
> < figure > < figcaption >
> + used to contain any content that is referenced from the main flow of an article (not just images).
> + The < figure > element should 
also contain a < figcaption >
element which provides a text 
decription for the content of 
the < figure > element
```
<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>
```

----------------------
---------------------
# Process & Design 
### 1. Site Maps
> the aim is to create a diagram 
of the pages that will be used 
to structure the site. This is 
known as a site map and it will 
show how those pages can be 
grouped.

![pic9](r01-9.png)

### 2. WireFrames
> A wireframe is a simple sketch of the key 
information that needs to go on each page of a 
site. It shows the hierarchy of the information 
and how much space it might require.

![pic10](r01-10.png)

+  Design is about communication. Visual hierarchy helps 
visitors understand what you are trying to tell them.
+ You can differentiate between pieces of information 
using size, color, and style. 
+ You can use grouping and similarity to help simplify 
the information you present.

--------------------------------
----------------------------
# JS 
## What is a script ?
>+  A script is a series of instructions that a computer can follow to achieve a goal. 

> + to write your code you should achieve your goal that the computer can do more than one instraction at the same time it is follow the orders in step to achieve the goal so the correct steps to write the code should be as follow :
   1. define the goal
   2. design the script by deviding to steps
   3. code each step
> after we deign the flowchart that every step should be writing in that way the computer understand it : 
- Vocabulary: The words that computers understand 
- Syntax: How you put those words together to create instructions computers can follow

## FLOWCHART KEY
![](fc1.jpg)

## rules to giving a variable a name:
1. The name must begin with a letter.
2. should not contain a spical charecter .
3. we can not use the instractions to make the names .
4. All variables are case sensitive.
5. Use a name that describes the kind of information that the variable stores.
6. use a capital latter for the first word if the name more than one word.

## arrays
>  it is a variable had a list of values related to each other
```
var colors;
colors ['white', 'black', ' custom '];
var el document.getElementByld('col ors');
el . textContent = col ors[O];
```
## Expressions :
> An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.

1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE

2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE


## What is a function 
> Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements)

## HTML
![image](https://user-images.githubusercontent.com/79833651/109936663-ce3ecd80-7cd6-11eb-8e20-5eceec8aadce.png)

  

## JAVASCRIPT

![image](https://user-images.githubusercontent.com/79833651/109936776-e9114200-7cd6-11eb-8a88-1fcb021daefe.png)


