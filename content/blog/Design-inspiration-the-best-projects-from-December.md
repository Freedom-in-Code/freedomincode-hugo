---
title: "Responsive Navigation Menu Pure HTML/CSS for Beginners"
date: 2019-12-24T13:45:06+06:00
image: images/blog/blog-post-04.jpg
feature_image: images/blog/blog-details-image.jpg
author: Surafel Yimam
---
### Responsive Navigation Menu Using HTML/CSS

When it comes to websites, the most handy element is the Navigation Bar. It is the most important element since it tell users where they currently are and where they can navigate to in the site. This element can be made using the two fundamental scripting languages. HTML and CSS. 

In many projects, you have already seen that the HTML is used to give structure to a component and CSS is used to style it. In this particular case, we will use CSS to make our navigation bar responsive. A responsive navigation bar is one that responds to the device being accessed. Smaller screeens and devices can still access our website if it's responsive. We will follow these basic steps to create our navigation bar. 

1. Lay Our Navigation Bar
2. The HTML for the Navigation Bar
3. The CSS for the Navigation Bar

First, let's take a look at how we want our navigation bar to look like. 


You will notice that our navigation bar looks pretty neat and it also has this hover effect on its buttons, this will tell the users that they can click on it and navigate to that said location. Which makes for great user experience! And it also has a logo of the business on the other end. 

Designing and laying out your navigation bar before actually coding it helps you have a clearer image of what you want your element to look like. It also helps you figure out the required CSS. So let's get working on the code. 

To make this navigation bar, you can use any simple text editor like Notepad. I am going to be using Visual Studio Code, which is a very powerful and free IDE.  Using an IDE or Integrated Developement Environment, helps you become a better, faster and smarter coder. So, let's create a file called `index.html` in our sites directory. 

The `index.html` file is the file that holds the entire structure of our navigation bar. And the way you start writing HTML files is usually the same. If you're using VSCode you can simply use an exclamation mark to use the Emmet abbreviation. This will give out an HTML5 boilerplate ready for you to use. 

You initialize the whole document type as `html` by using `<!DOCTYPE html>`. This reminds our browser to expect an HTML5 version document.  Next, you will find the `<html>` tag and inside it the `head` tag, which will hold our `metadata`, `title` and `link` to our styles file. After that you will find the `body` tag. Last, is the `</html>` closing tag which tells our browser that the document is finished. 

When starting to work on a Navigation Bar element, you will notice that most links and buttons are usually lists wrapped inside a container. So, we can use a simple unordered list with some items to structure our Navigation Bar.

And since our elements are links to other pages or elements, we can nest anchor tags (link tags) inside our list elements. 

This would look like: 

``` html
<ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">Contacts</a></li>
<ul>
``` 

If we save this and open our HTML file using the Live Server, which is another extension from VSCode that allows you to preview your changes instantly as you save your `index.html` file, you will find nothing more but a typical unordered list with a bunch of links. 

Now to the final part of our project, which is to style our HTML using CSS. So let's create a file that links to our previous link tag in our HTML head. We will call this file `styles.css` which matches with the reference of the link tag and is also common convention when styling an HTML page. 

Let's start by removing the dots at the start of each list item. We can do this by selecting the whole unordered list as `ul` and giving it's `list-style` property a value of `none`. Most navigation bars are aligned to the top and they have no space in between them and the browser window. We can set this up by giving our universal element 0 margin and 0 padding values. Next, to style our navigation, let's give it a slightly darker background color of #555.

Now let's move to styling our list tags which are wrapped inside our unordered lists. You will notice that they are displaying as block values by default. This means that each element takes up a line. The display element is set as block for most elements in HTML. One of them is the list tag. Let's change its display value inline, which would make our list elements all appear on the same line. 

Once we have styled our list elements as such, it's time to style the anchor tags inside our list elements. Links in HTML have a default text-decoration property. Let's remove this property by setting it to a value of none. Another default property they have, is the blue color. Let's change this to white, to offer our navigation element some contrast. 

Our Navigation Bar is looking much better now. But it's noticeable that the elements are pretty close apart to each other. Let's put some space between them by setting the padding to 10px. 




> Paul Rand, graphic designer

