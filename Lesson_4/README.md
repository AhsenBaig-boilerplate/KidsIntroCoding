# Lesson 4 - hr, br & CSS

## Continue from lesson 3

### hr & br

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
            <hr>
            <img src="ImageLink" width="400">
            <br>
            <br>
        </center>
    </body>
</html>
```

## CSS - Cascading Style Sheets
  
```HTML
<!doctype html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <center>
            <h1 style="color:blue;font-size:60px;">This is text that is centered</h1>
            <h2>Second heading</h2>
            <hr>
            <img src="ImageLink" width="400">
            <br>
            <br>
        </center>
    </body>
</html>
```

### Define styles class

```HTML
<!doctype html>
<html>
    <head>
        <title>Page Title</title>
        <style>
            h2 {
                color: blue;
                font-size:70 px;
                font-family: Arial, Helvetica, sans-serif;
            }
        </style>
    </head>
    <body>
        <center>
            <h1>This is text that is centered</h1>
            <h2>Second heading</h2>
            <hr>
            <img src="ImageLink" width="400">
            <br>
            <br>
        </center>
    </body>
</html>
```
#### How class works

```HTML
<!doctype html>
<html>
    <head>
        <title>Page Title</title>
        <style>
            h2 {
                color: blue;
                font-size:70 px;
                font-family: Arial, Helvetica, sans-serif;
            }
        </style>
    </head>
    <body>
        <center>
            <h1>This is text that is centered</h1>
            <h2>Second heading</h2>
            <h2>Another h2 tag</h2>
            <hr>
            <img src="ImageLink" width="400">
            <br>
            <br>
        </center>
    </body>
</html>
```

#### Give the class a name

```HTML
<!doctype html>
<html>
    <head>
        <title>Page Title</title>
        <style>
            .myClass {
                color: blue;
                font-size:70 px;
                font-family: Arial, Helvetica, sans-serif;
            }
        </style>
    </head>
    <body>
        <center>
            <h1>This is text that is centered</h1>
            <h2 class="myClass">Second heading</h2>
            <h2>Another h2 tag</h2>
            <hr>
            <img src="ImageLink" width="400">
            <br>
            <br>
        </center>
    </body>
</html>
```

#### Hyperlink

```HTML
<!doctype html>
<html>
    <head>
        <title>Page Title</title>
        <style>
            .myClass {
                color: blue;
                font-size:70 px;
                font-family: Arial, Helvetica, sans-serif;
            }
        </style>
    </head>
    <body>
        <center>
            <h1>This is text that is centered</h1>
            <h2 class="myClass">Second heading</h2>
            <h2>Another h2 tag</h2>
            <a href="www.google.com">
                <h2>Visit Google</h2>
            </a>
            <hr>
            <img src="ImageLink" width="400">
            <br>
            <br>
        </center>
    </body>
</html>
```
