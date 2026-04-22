HTML Review 

What does HTML stand for?
Hypertext Markup lamguage

What is the differnce between <head> and <body>? 
    <head> --> Metadata - read by the browser 
    <body> --> This content DISPLAYED in the browser

Name THREE semantic HTML elements?
<header></header>
<main></main>
<footer></footer>
<nav></nav>
<article></atricle>
<aside></aside>
<section></section>

What attribute does an <a> tag need to creat a link?
    href --> <a href="https://www.google.com">

What is a self-closing HTML tag?
Are tags that do not have closing tags, also known as void elements 
<br>
<img>
<link>
<meta>

What does <!DOCTYPE html> do?
This tells the browser that the file is an HTML file

Every HTML file has the same SKELETON (Boilerplate, template) structure:

<!DOCTYPE html>
<html lang="en">
<head>
    <title></title>
    <link>
    <style></style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width", inital-scale="1.0">
                -Makes the page Responsive on all devices automatically 
</head>
<body>
    <header>
    <nav>Contains any Navigation bar elements</nav>
    </header>
    <h1>Largest header/moat important heading. Only ONCE per page </h1>
    <!--all visible elements go inside the body -->
</body>
</html>

Part 2: Core HTML Elements
<h1> --> There should be only 1 <h1> per page
<h2> --> section titles, subtitles
<h3> --> 
<h4> --> 
<h5> --> 
<h6> --> 

links 

How do i create a link to sllboces.org?

<a href="https://www.sllboces.org" target="_blank">SLL BOCES</a>

How do i create a link about.html to a relative path (page in the same directory)?
<a href="about.html">About</a>

Link to a file in the content folder? 
<a href="content/page.html">Page</a>

A link to another section of page?
<a href="#about">Jump to the about section</a>

A link to send a email?
<a href="mailto:student@sllboces.org">Email Me</a>

Images
What are the two required attributes for <img> tags? 
alt - accessebility text
src - file path to the image

<img src="images/hero.jpg" alt="Adirondacks Mountains in fall">
<img src="images/logo.png" alt="sll boces logo">

What is hot-linking a image? 
Linking to an image somewhere on the internet
Place holder images for design purposes
replace hot links before publishing the site
Whi? If the hotlinked image gets moved it will break your design

<img src="https://google.com/2/abc/file/images/myGoogleImage.png" alt="my hotlinked image">



Part 3 
What is a semantic HTML ELEMENT?
semantic elements describe the meaning of the content inside of the element not just the way it looks.

Reasons why we use semantic elements?
Organization (Teamwork - allows other developers to more easily read and understand your code)

Effects the document object model 

Accesbility - allows screen readers to understand the structure and meaning 

Search engine optimization - how search engines rank well-structured pages - moves them higher in the search results 






