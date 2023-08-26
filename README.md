# A Basic Introduction to JavaScript and Output

JavaScript can be used to create output. This can be done many different ways:

- Using `document.write` to add content to the HTML webpage
- Use `alert()` to display a warning message in an alert popup
- Use `console.log()` to display a message in the developer tools of a browser

## Using `document.write`

The `document.write` command will add content to the document. 

Open up a new HTML file, name it output.html, add the standard HTML elements, and then add the following code:

```html
<script>
document.write( "<h1>Creating Output</h1>" );
document.write( "<p>Quotes can cause conflicts with creating output." + " " + 
    "To resolve quote issues there are three solutions:</p>" );
document.write( "<ul>" + 
    "<li>Escape them with a slash</li>" + 
    "<li>Use alternating quotes</li>" + 
    "<li>Use special characters</li>" + 
    "</ul>" );
</script>
```

Test the file using a browser. The `body` section of the webpage should have some useful information regarding JavaScript, output, and quotations. 

## Using `alert`

The `alert()` command will display a message using an alert style popup. 

Open up the previous file, right before the closing `script` tag, add the following code:

```javascript
alert("This is an alert message");
```

## Using `console.log`

The `console.log()` command will display a message using the browser developer tools. 

Open up the previous file, right before the closing `script` tag, add the following code:

```javascript
console.log( "This is a console log" );
```

To test the `console.log` line of code, follow these steps:

1. Open a browser
2. Right click on the web page and choose Inspect Element
3. From the developer tools, choose the Console tab
3. Open the `output.html` file
4. The message in the `console.log` command will be displayed

## Trying it Out

Create an HTML file and add the following code:

```html
<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Creating Output</title>
    </head>
    <body>
        
        <h1>W3Schools</h1>

        <p>W3Schools is a web developer information website, with tutorials
            and references relating to web development topics such as HTML, CSS,
            JavaScript and PHP.</p>

        <a href="http://www.w3schools.com/">W3Schools</a>

        <br>

        <img src="w3schools.png">

    </body>
</html>
```

Convert each line of HTML in the `body` section to use JavaScript and `document.write()`. For example, converting the `h1` element could look like this:

```html
<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Creating Output</title>
    </head>
    <body>

        <script>

        document.write("<h1>W3Schools</h1>");

        </script>

        <p>W3Schools is a web developer information website, with tutorials
            and references relating to web development topics such as HTML, CSS,
            JavaScript and PHP.</p>

        <a href="http://www.w3schools.com/">W3Schools</a>

        <br>

        <img src="w3schools.png">

    </body>
</html>
```

When you have completed the goal, the `body` tag will only include one `script` tag and a number of `document.write()` commands. 

> Full tutorial URL:  
> https://codeadam.ca/learning/javascript-output.html

***

## Repo Resourcecs

* [Visual Studio Code](https://code.visualstudio.com/)

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
