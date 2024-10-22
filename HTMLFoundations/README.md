# [Odin Recipes Source Code](https://github.com/neqbal/cryptoniteWebDev/blob/main/HTMLFoundations/index.html)
# [Live Preview](https://neqbal.github.io/odinRecipes/)

# HTML 
Hyper Text Markup Language
It is the raw data that a webpage is built out of. It is the most basic building block of a webpage. It defines the meaning and structure of a webpage. 

"Hypertext" It refers to links that connect web pages to one another, either within a single website or between websites.\
"Markups" are used to annotate texts, images and other contents to display them on the webpage. \

# CSS 
Cascading Style Sheets
It adds style to the webpage. 
HTML puts content on the webpage and CSS adds style to it so that it becomes more appealing.

# JavaScript
It is a scripting langauge that allows us to manipulate HTML and CSS of the webpage after the site has been uploaded.

***

&nbsp;
&nbsp;

# Getting started

## Elements and tags

Almost all HTML elements are enclosed between opening tag `<>` and closing tag `</>` \
Opening tag tells the browser that this is a start of the element. 

The tags and the content between those tags are collectively called as Element.

```html
<p> This is a paragraph </p>
```

`<p>` is the paragraph tag \
`</p>` is the closing paragraph tag

Similarly there many more tags available


Some HTML elements do not neet closing tags and they are called Void Elements

***

## HTML boilerplate

#### The DOCTYPE

```html
<!DOCTYPE html>
```

This elements tells the browser which version of html we will be using and since we wont be using any older version, just `html` is fine

#### HTML Element

After we declare the doctype we declare a `<html>` element which is knows as the root element
We also add a `lang` attribute which specifies the langauge of the text content \

```html
<html lang="en">
```

#### Head Element
`<head>` element is where we put our important meta information about out webpage and stuff required by our webpage to render correctly

```html
<head>
    <meta charset="UTF-8">
    <title>Odin</title>
</head>
```

The `<meta>` element specifies the encoding format of our webpage \
The `<title>` element is used to give the webpage a name which is visible on the browser's tab.  

#### Body Element
This is where all the contents that are to be displayed on webpage are written

```html
<body>

</body>
```

This is a typical boilerplate for an HTML document \


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Odin</title>
  </head>

  <body>
  </body>
</html>
```

## Working with texts

#### Paragraph 
```html
<body>
    Lorem ipsum dolor sit amet

    Ut enim ad minim veniam 
</body>
```
If try to write a paragraph like above the browser will compress the empty line and the result will be just one single line of text.

So for it to appear as paragraph seperated by a line we need to use the `<p>` tag and enclose every paragraph individually within it.

```html
<body>
    <p>lorem ipsum dolor sit amet</p>
    <p>ut enim ad minim veniam</p>
</body>
```
&nbsp;

#### Headings
we can use the headings tag `<h1>` to write headings. 
The heading tags are displayed larger and bolder compared to other tags and number specifies the importance. Where most important being `<h1>` and least important being `<h6>`

```html
<body>
    <h1>This is a heading 1</h1>
    <h2>This is a heading 2</h2>
    <h3>This is a heading 3</h3>
    <h4>This is a heading 4</h4>
    <h5>This is a heading 5</h5>
    <h6>This is a heading 6</h6>
</body>
```
&nbsp;

## Working with lists

#### Unordered Lists
In unordered lists the order of elements does not matter and the list items are prefixed with a bold dot.

```html
<ul>
    <li> item 1 </li>
    <li> item 2 </li>
</ul>
```

#### Ordered Lists
In ordered lists the order of elements does matter and the list items are prefixed with numbers in their serial order.

```html
<ol>
    <li> item 1 </li>
    <li> item 2 </li>
</ol>
```
&nbsp;

## Links and images

#### anchor element

```html
<a href="https://www.theodinproject.com/about">About The Odin Project</a>
```

The anchor element is `<a>` and we can use `href` attribute to embed links in text.
By clicking that text, the webpage will open on the same tab. 

To open the link in a seperate tab we can add `target="_blank"` attribute to anchor element.

#### Image

```html
<img src="path to image or link of that image">
```

An image can be included into the html page by using the `<img>` tag and providing the path to that image to `src` attribute.
We can also add `alt` attribute which can display a text if image is not displayed.
***
