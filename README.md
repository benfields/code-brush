Code Brush
==========
Easlily add code snippits to your website and have them look great!

=========

### How to enable Code Brush

using code brush is easy, if you have downloaded the ZIP file and added it to your website's directory (unzipped of course), use the html code example shown below

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
 it's even easy to highlight certain lines to make the stand out...
 
```html
<pre class="brush:js, highlight:[3,12,17]"></pre>
```

the example above highlights lines 3, 12, and 17 in your code that goes in betwen the <code>pre</code> tags.

========

## Source Licenses

### My License

The resources found here can be used freely in personal and commercial projects if integrated and built upon. If using this code, I expect that you let your users know that the source is available on GitHub, and tell them how to find it. This can be done in the form of a link. 

Please do not create templates based on my code unless you are granted permission by me first. You are not allowed to take my work “as-is” and sell it, but feel free redistribute it for free. If you want to publish or sell extensions or ports (including WordPress plugins) out of my work, please contact me and ask for permission first. I'd like to see what’s being done and evaluate each request. 

Please, respect the licenses of the resources (audio, video, images, or external links) that might be found through out. If you write about some of my work I would like you to credit me.

##### Summarized, write about it, integrate it, make it your own, but don’t copy and paste my work and sell it or claim that it’s yours.

### MIT License

Copyright (c) 2013 Ben Fields

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
