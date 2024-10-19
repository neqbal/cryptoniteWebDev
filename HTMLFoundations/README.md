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


***

&nbsp;

[Odin Recipes](https://github.com/neqbal/cryptoniteWebDev/blob/main/HTMLFoundations/index.html)
