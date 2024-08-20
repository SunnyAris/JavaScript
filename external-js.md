## External JavaScript

External scripts are practical when the same code is used in many different web pages.

JavaScript files have the file extension .js.

To use an external script, put the name of the script file in the src (source) attribute of a `<script>` tag:


```
<!DOCTYPE html>
<html>
<body>

<h2>Demo External JavaScript</h2>

<p id="demo">Paragraph.</p>

<button type="button" onclick="myFunction()">Click</button>

<p>This example links to "myScript.js".</p>
<p>(myFunction is stored in "myScript.js")</p>

<script src="myScript.js"></script>

</body>
</html>
```

It separates HTML and code

It makes HTML and JavaScript easier to read and maintain

Cached JavaScript files can speed up page loads

An external script can be referenced in 3 ways:

- With a full URL (a full web address)
```
<script src="https://github.com/SunnyAris/js/myScript.js"></script>
```
- With a file path (like /js/)
```
<script src="/js/myScript.js"></script>
```
- Without any path
```
<script src="myScript.js"></script>
```
