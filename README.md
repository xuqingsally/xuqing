<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">

<head>

<meta charset="utf-8" />
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="generator" content="pandoc" />




<title></title>

<script src="site_libs/jquery-1.11.3/jquery.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link href="site_libs/bootstrap-3.3.5/css/bootstrap.min.css" rel="stylesheet" />
<script src="site_libs/bootstrap-3.3.5/js/bootstrap.min.js"></script>
<script src="site_libs/bootstrap-3.3.5/shim/html5shiv.min.js"></script>
<script src="site_libs/bootstrap-3.3.5/shim/respond.min.js"></script>
<script src="site_libs/navigation-1.1/tabsets.js"></script>
<link href="site_libs/highlightjs-1.1/default.css" rel="stylesheet" />
<script src="site_libs/highlightjs-1.1/highlight.js"></script>
<link href="site_libs/font-awesome-4.5.0/css/font-awesome.min.css" rel="stylesheet" />

<style type="text/css">code{white-space: pre;}</style>
<style type="text/css">
  pre:not([class]) {
    background-color: white;
  }
</style>
<script type="text/javascript">
if (window.hljs && document.readyState && document.readyState === "complete") {
   window.setTimeout(function() {
      hljs.initHighlighting();
   }, 0);
}
</script>



<style type="text/css">
h1 {
  font-size: 34px;
}
h1.title {
  font-size: 38px;
}
h2 {
  font-size: 30px;
}
h3 {
  font-size: 24px;
}
h4 {
  font-size: 18px;
}
h5 {
  font-size: 16px;
}
h6 {
  font-size: 12px;
}
.table th:not([align]) {
  text-align: left;
}
</style>


</head>

<body>

<style type = "text/css">
.main-container {
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
}
code {
  color: inherit;
  background-color: rgba(0, 0, 0, 0.04);
}
img {
  max-width:100%;
  height: auto;
}
.tabbed-pane {
  padding-top: 12px;
}
button.code-folding-btn:focus {
  outline: none;
}
</style>


<style type="text/css">
/* padding for bootstrap navbar */
body {
  padding-top: 51px;
  padding-bottom: 40px;
}
/* offset scroll position for anchor links (for fixed navbar)  */
.section h1 {
  padding-top: 56px;
  margin-top: -56px;
}
.section h2 {
  padding-top: 56px;
  margin-top: -56px;
}
.section h3 {
  padding-top: 56px;
  margin-top: -56px;
}
.section h4 {
  padding-top: 56px;
  margin-top: -56px;
}
.section h5 {
  padding-top: 56px;
  margin-top: -56px;
}
.section h6 {
  padding-top: 56px;
  margin-top: -56px;
}
</style>

<script>
// manage active state of menu based on current page
$(document).ready(function () {
  // active menu anchor
  href = window.location.pathname
  href = href.substr(href.lastIndexOf('/') + 1)
  if (href === "")
    href = "index.html";
  var menuAnchor = $('a[href="' + href + '"]');
  // mark it active
  menuAnchor.parent().addClass('active');
  // if it's got a parent navbar menu mark it active as well
  menuAnchor.closest('li.dropdown').addClass('active');
});
</script>


<div class="container-fluid main-container">

<!-- tabsets -->
<script>
$(document).ready(function () {
  window.buildTabsets("TOC");
});
</script>

<!-- code folding -->






<div class="navbar navbar-default  navbar-fixed-top" role="navigation">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="index.html">Qing</a>
    </div>
    <div id="navbar" class="navbar-collapse collapse">
      <ul class="nav navbar-nav">
        
      </ul>
      <ul class="nav navbar-nav navbar-right">
        <li>
  <a href="Resume.html">Resume</a>
</li>
<li>
  <a href="about.html">About</a>
</li>
<li>
  <a href="mailto:&lt;qx2178@cumc.columbia.com&gt;">
    <span class="fa fa-envelope fa-lg"></span>
     
  </a>
</li>
<li>
  <a href="https://www.facebook.com/people/Qing-Xu/100011556522258">
    <span class="fa fa-facebook-square fa-lg"></span>
     
  </a>
</li>
<li>
  <a href="https://www.linkedin.com/in/qing-xu-633839139/">
    <span class="fa fa-linkedin-square fa-lg"></span>
     
  </a>
</li>
<li>
  <a href="http://github.com/xuqingsally">
    <span class="fa fa-github fa-lg"></span>
     
  </a>
</li>
      </ul>
    </div><!--/.nav-collapse -->
  </div><!--/.container -->
</div><!--/.navbar -->

<div class="fluid-row" id="header">




</div>


<div class="figure">
<img src="1.jpg" />

</div>
<div id="key-words-about-me" class="section level2">
<h2>key words about me</h2>
<ul>
<li><strong>Biostatistics MS Student</strong><br />
</li>
<li><strong>Columbia University Medical Center</strong><br />
</li>
<li><strong>Movie</strong><br />
</li>
<li><strong>China</strong><br />
</li>
<li><strong>Data analysis in health</strong><br />
</li>
<li><strong>Nanjing University</strong></li>
</ul>
</div>




</div>

<script>
// add bootstrap table styles to pandoc tables
function bootstrapStylePandocTables() {
  $('tr.header').parent('thead').parent('table').addClass('table table-condensed');
}
$(document).ready(function () {
  bootstrapStylePandocTables();
});
</script>

<!-- dynamically load mathjax for compatibility with self-contained -->
<script>
  (function () {
    var script = document.createElement("script");
    script.type = "text/javascript";
    script.src  = "https://mathjax.rstudio.com/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML";
    document.getElementsByTagName("head")[0].appendChild(script);
  })();
</script>

</body>
</html>