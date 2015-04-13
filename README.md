Code Brush
==========
Easily add code snippits to your website and have them look great!

=========

### How to enable Code Brush

using code brush is easy, if you have downloaded the ZIP file and added it to your website's directory (unzipped of course), you can add the html code below in between the <code>head</code> tags.

```html
<link rel="stylesheet" type="text/css" href="tyrm.css" media="all" />
<link rel="stylesheet" type="text/css" media="print" href="theme_print.css" />
<script src="cbCore.js"></script>
<script src="cBrushXml.js"></script>
<script src="cBrushCss.js"></script>
<script src="cBrushPhp.js"></script>
<script src="cBrushSql.js"></script>
<script src="cBrushJScript.js"></script>   
<script>
    SyntaxHighlighter.defaults['auto-links'] = false;
    SyntaxHighlighter.defaults['toolbar'] = false;
    SyntaxHighlighter.all();
</script>

```

========

### How to use Code Brush

you can easlily use Code Brush by adding th code example below into your html file where you want your brushed code to render


```html
<pre class="brush:css">
body{
    color: #ffffff;
    background-color: #787878;
    cursor: pointer;
    
}
</pre>
```

you can brush the <code>pre</code> tag with whatever format your code is...

```html
<pre class="brush:html"></pre>
<pre class="brush:css"></pre>
<pre class="brush:php"></pre>
<!-- you get the idea -->
```
 it's even easy to highlight certain lines to make them stand out...
 
```html
<pre class="brush:js, highlight:[3,12,17]"></pre>
```

the example above highlights lines 3, 12, and 17 in your code that goes in betwen the <code>pre</code> tags.

========

### MIT License

Copyright (c) 2013-2015 Ben Fields

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

============

this project is based off of Alex Gorbatchev's [Syntax Highlighter](https://github.com/alexgorbatchev/SyntaxHighlighter), but with my own feel and flavor.
