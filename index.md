# class-01.md

**Introductory HTML and Java Script**

**HTML**

The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure. The new elements provide clearer code (compared with using multiple <div> elements).

X Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.

X To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.

For Process & Design you will learn to  approach building a site, understanding your audience and their needs and how to present information visitors want to see. Also you  will design theory for presenting information in a way that helps visitors achieve their goals and Design tips to help you create more attractive and professional sites.


**Java Script** 

It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension.

The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> element can be used to load a CSS file).

If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.

Examples:

<!DOCTYPE html> <html>
  <head>

<title>Constructive &amp; Co.</title>

<link rel ="stylesheet" href="css/cOl.css" />

</head> <body>

<hl>Constructive &amp; Co.</hl>

<p>For all orders and inquiries please call <em>555-3344</em></p> <script src="js/add-content.js"></script>

JAVASCRIPT RUNS WHERE IT IS FOUND IN THE HTML

When the browser comes across a <script>element, it stops to load the script and then checks to see if it needs to do anything.

</body> </html>



