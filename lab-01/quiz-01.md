# Quiz-01
## MAP672, Fall 2020
1. Use the local host environment to take advantage of the web server capabilities within your text editor and easier web map development. Make sure that the URL displays a numeric IP address (http://127.0.0.1/) when testing application. If not the document will not load external files or render correctly.

<!-- Yep! Let's add that the local web server mimics a production environment (the host that we share to the world). The local web server hosts our page and allows a browser to make an http request. A successful request will return a rendered web page. If problems occur, such as broken links or errors in our code, the browser's Console will report information that can help debug our code and optimize our page.  -->

2. Example HTML code block in Markdown:

```html
<p>For additional information about open source JavaScript libraries visit <a href="https://leafletjs.com/">Leaflet JS</a>.</p>
```

renders to: 

<p>For additional information about open source JavaScript libraries visit <a href="https://leafletjs.com/">Leaflet JS</a>.</p>

3. Example HTML code block in Markdown:

```html
<style>
.blue {
    color:skyblue;
    } 
</style>
<body>
    <p class='blue'>Hello world!</p>
</body>
```

renders to: 

<style>
.blue {
    color:skyblue;
    } 
</style>
<body>
    <p class='blue'>Hello world!</p>
</body>

4. Use #id attribute for single unique element. We can attach an id attribute to a single unique element within the web document. In lesson example, there can be only one element with an id attribute value of map. Otherwise, the page or script may break. Use class attribute to select one or more elements. Use CSS selectors to select a single element with an id attribute value using the pound # symbol and the period . symbol for selecting multiple elements with their class attribute value.

<!-- And, we use CSS selectors to connect page elements with JavaScript. -->

5. Inline code: `<script>console.log("Hello World");</script>`
