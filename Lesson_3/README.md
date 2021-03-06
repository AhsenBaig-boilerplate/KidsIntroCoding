# Learn HTML & CSS

We will go over the basics of HTML and CSS. Where it is used and how it works. 

For this demo we can use various editors to make it easy to write code: VSCode 

Online Editor: https://jsfiddle.net/

## HTNL - Hypertext Markup Language (.html/.htm)

Building block for websites. Defines elements in the page (buttons, links, images, text, etc.)

```HTML
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <h1>This is a heading</h1>
        <p>This is a paragraph</p>
        <p>This is another paragraph</p>
    </body>
</html>
``` 
### doctype - we can use a simple doctype for HTML 5 (the version of the html language.)

```HTML
    <!doctype html>
```

### Center the text

```HTML
<!doctype html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <center>
            <h1>This is text that is centered</h1>
        </center>
    </body>
</html>
```

### Add additional heading tags

```HTML
<!doctype html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <center>
            <h1>This is text that is centered</h1>
            <h2>Second heading</h2>
            <h3>Third Heading</h3>
        </center>
    </body>
</html>
```

### Add paragraphs and not center headers

```HTML
<!doctype html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <center>
            <h1>This is text that is centered</h1>            
        </center>
        <h2>Second heading</h2>
        <p>First paragraph</p>        
        <h3>Third Heading</h3>
        <p>Second paragraph</p>
    </body>
</html>
```

### Add Images

```HTML
<!doctype html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <center>
            <h1>This is text that is centered</h1>
            <h2>Second heading</h2>
            <img src="ImageLink">
        </center>
    </body>
</html>
```
