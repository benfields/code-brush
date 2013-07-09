Code Brush
==========
Easlily add code snippits to your website and have them look great!

=========

### How to enable Code Brush

using code brush is easy, just add the following html to the 'head' section of your webpage

```html
    <link rel="stylesheet" type="text/css" href="http://terld.com/tdata/source/wikitds/codebrush/mouthtds.css" media="all" />

    <link rel="stylesheet" type="text/css" media="print" href="http://terld.com/tdata/source/wikitds/codebrush/theme_print.css" />
      <script src="http://terld.com/tdata/source/wikitds/codebrush/shCore.js"></script>
      <script src="http://terld.com/tdata/source/wikitds/codebrush/shBrushXml.js"></script>
      <script src="http://terld.com/tdata/source/wikitds/codebrush/shBrushCss.js"></script>
      <script src="http://terld.com/tdata/source/wikitds/codebrush/shBrushPhp.js"></script>
      <script src="http://terld.com/tdata/source/wikitds/codebrush/shBrushSql.js"></script>
      <script src="http://terld.com/tdata/source/wikitds/codebrush/shBrushJScript.js"></script>   
      <script>
        SyntaxHighlighter.defaults['auto-links'] = false;
        SyntaxHighlighter.defaults['toolbar'] = false;
        SyntaxHighlighter.all();
      </script>

```


or, if you have downloaded the ZIP file and added it to your website's directory (unzipped of course), use the html code example shown below

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

### Source License

The resources found here can be used freely in personal and commercial projects if integrated and built upon. If using this code, I expect that you let your users know that the source is available on GitHub, and tell them how to find it. This can be done in the form of a link. 

Please do not create templates based on my code unless you are granted permission by me first. You are not allowed to take my work “as-is” and sell it, but feel free redistribute it for free. If you want to publish or sell extensions or ports (including WordPress plugins) out of my work, please contact me and ask for permission first. I'd like to see what’s being done and evaluate each request. 

Please, respect the licenses of the resources (audio, video, images, or external links) that might be found through out. If you write about some of my work I would like you to credit me.

##### Summarized, write about it, integrate it, make it your own, but don’t copy and paste my work and sell it or claim that it’s yours.

========

Unfortunately, at this time, there is no live demo, but you can expect one in the near future. Enjoy!

========
