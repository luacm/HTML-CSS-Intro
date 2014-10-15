HTML-CSS-Intro
==============

Supplement to TJ's beginner workshop on 10/13/14. Feel free to add resources!

##What is HTML?
HTML stands for HyperText Markup Language. It is the building block of all websites. For those of you with programming experience, you'll be delighted to find that it isn't nearly as syntactically rigorous as Java, for example.

HTML is a *markup* language. Even when you mess it up- your web browser will try its best to display what you've written. In other words, one little mistake won't take your site down.

####Write it!
The language is comprised of tags enclosed in angle brackets, such as ```<html>```, ```<img>```, ```<span>```, and ```<div>```. Ready to jump in?

Open a new text document- I recommend using [Sublime](http://www.sublimetext.com/) or [Notepad++](http://notepad-plus-plus.org/). Before you start writing your angle brackets, click ```save as``` and name your file ```index.html```. What's important is the .html extension. This tells your machine how to interpret the file's contents. For example, when you double click the icon, it will probably open the .html file in your web browser. 

Now you can start with a simple example. Copy the following code (yes, it's considered code) and explore different combinations of tags:

```
<html>
  <head>
    <title>ACM Workshop Test</title>
  </head>
  <body>
    <p>Hello world!</p>
  </body>
</html>
```

Is the indentation necessary? No, *but*, stylistically, it makes sense to indent your tags to show depth. The usefulness will be more clear when we get to CSS.


##What is CSS?

CSS stands for Cascading Style sheets. It is a language used to format markup languages. Handily, I just introduced you to the most common markup language- HTML. Let's talk about what CSS can do.

Style sheets are comprised of *rules*. A *rule* consists of one or more *selectors* followed by a *declaration block*. 

Selectors target elements and declaration blocks modify the style of those elements. Let's say you want to change all the text in ```<p>Hello World!</p>``` to blue and 35px. This code would accomplish that: 

```p {
font-size: 35px;
color: red;
}```

To take a step back, you might be wondering where to put this code. You can either declare it between ```<style> </style> ``` tags in your header, inline: ```<p style="color: red; font-size: 35px;" ```, or in a separate file, which is the most common.

To create the file needed, open your favorite text editor (which should be [Sublime](http://www.sublimetext.com/) by now). Create a new file and save it as style.css. If you're using a halfway-decent text editor, you'll notice different colors based on the style.

Next, implement the style change listed above:

```p {
font-size: 35px;
color: red;
}```

Go back to your html file and modifier the header so it looks like this:

```
<html>
  <head>
  	<link rel="stylesheet" type="text/css" href="style.css">
    <title>ACM Workshop Test</title>
  </head>
  <body>
    <p>Hello world!</p>
  </body>
</html>
```
Save and now check out your large red text!

##What piece is missing?
**Javascript**. HTML provides structure, CSS enhances style, and Javascript can do pretty much everything else. Javascript is *the* programming language of the web for client-side applications.

You can use the links below to learn more before moving onto JavaScript, which is more advanced.


##Learn More (Links)
- [Codecademy](http://www.codecademy.com/) (My favorite)
- [W3Schools](http://www.w3schools.com/) (Great reference)
- [Udemy](https://www.udemy.com/) (Typically more advanced)
- [HTMLDog](http://htmldog.com/guides/) (Lesser known)
