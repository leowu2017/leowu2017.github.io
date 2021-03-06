---
layout: post
title:  "Bootstrap Demo"
date:   2016-07-09 00:00:00 -0400
categories: software
---

+ [Bootstrap website](http://getbootstrap.com/){:target="_blank"}
+ [w3schools](http://www.w3schools.com/bootstrap/default.asp){:target="_blank"}
+ **This demo is made from a [Youtube tutorial - by Derek Banas](https://youtu.be/gqOEoUR5RHg){:target="_blank"}**

<!-- Bootstrap -->
<link href="{{site.url}}/assets/css/bootstrap.min.css" rel="stylesheet">

<h2>1. Button</h2>

<div class="container-fluid">

<div class="page-header">
	<h3>This is a Page Header</h3>
</div>

<div class="jumbotron">
	<p>This is a jumbotron content.</p>

	<a class="btn btn-lg btn-info" role="button">&lt;a&gt; button</a>

	<button type="submit" class="btn btn-link" role="button">&lt;button&gt; button</button>

	<input type="button" value="disabled &lt;input&gt; button" class="btn btn-xs btn-primary" role="button" disabled="disabled">

	<a class="btn btn-danger disabled" role="button">disabled &lt;a&gt; button</a>

	<hr>
	<div class="btn-group btn-group-sm" role="group">
		<button class="btn btn-warning disabled">Left</button>
		<button class="btn btn-default">Middle</button>
		<button class="btn btn-success">Right</button>
	</div>
</div>

</div>

{% highlight html %}
<div class="container-fluid">

<div class="page-header">
	<h3>This is a Page Header</h3>
</div>

<div class="jumbotron">
	<p>This is a jumbotron content.</p>

	<a class="btn btn-lg btn-info" role="button">&lt;a&gt; button</a>

	<button type="submit" class="btn btn-link" role="button">&lt;button&gt; button</button>

	<input type="button" value="disabled &lt;input&gt; button" class="btn btn-xs btn-primary" role="button" disabled="disabled">

	<a class="btn btn-danger disabled" role="button">disabled &lt;a&gt; button</a>

	<hr>
	<div class="btn-group btn-group-sm" role="group">
		<button class="btn btn-warning disabled">Left</button>
		<button class="btn btn-default">Middle</button>
		<button class="btn btn-success">Right</button>
	</div>
</div>

</div>
{% endhighlight %}

<h2>2. Responsive Layout</h2>

<div class="container-fluid">
<div class="row">

<div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
	<h4><a href="#col1Content" data-toggle="collapse">Column 1</a></h4>

	<div id="col1Content" class="collapse in">
		Bootstrap (currently v3.3.6) has a few easy ways to quickly get started, each one appealing to a different skill level and use case. Read through to see what suits your particular needs.
	</div>
</div>

<div class="col-lg-3 col-md-8 col-sm-6 col-xs-12">
	<h4><a href="#col2Content" data-toggle="collapse">Column 2</a></h4>

	<div id="col2Content" class="collapse">
		Bootstrap uses Autoprefixer to deal with CSS vendor prefixes. If you're compiling Bootstrap from its Less/Sass source and not using our Gruntfile, you'll need to integrate Autoprefixer into your build process yourself. If you're using precompiled Bootstrap or using our Gruntfile, you don't need to worry about this because Autoprefixer is already integrated into our Gruntfile.
	</div>
</div>

<div class="clearfix visible-sm visible-md"></div>

<div class="col-lg-3 col-md-6 col-sm-6 col-xs-12">
	<h4>Column 3</h4>
		Bootstrap is downloadable in two forms, within which you'll find the following directories and files, logically grouping common resources and providing both compiled and minified variations.
</div>

<div class="col-lg-3 col-md-6 col-sm-6 col-xs-12">
	<h4><a href="#col4Content" data-toggle="collapse">Column 4</a></h4>

	<div id="col4Content" class="collapse">
		Bootstrap uses Grunt for its build system, with convenient methods for working with the framework. It's how we compile our code, run tests, and more.
	</div>
</div>

</div>
</div>

{% highlight html %}
<div class="container-fluid">
<div class="row">

<div class="col-lg-3 col-md-4 col-sm-6 col-xs-12">
	<h4><a href="#col1Content" data-toggle="collapse">Column 1</a></h4>

	<div id="col1Content" class="collapse in">
		Bootstrap (currently v3.3.6) has a few easy ways to quickly get started, each one appealing to a different skill level and use case. Read through to see what suits your particular needs.
	</div>
</div>

<div class="col-lg-3 col-md-8 col-sm-6 col-xs-12">
	<h4><a href="#col2Content" data-toggle="collapse">Column 2</a></h4>

	<div id="col2Content" class="collapse">
		Bootstrap uses Autoprefixer to deal with CSS vendor prefixes. If you're compiling Bootstrap from its Less/Sass source and not using our Gruntfile, you'll need to integrate Autoprefixer into your build process yourself. If you're using precompiled Bootstrap or using our Gruntfile, you don't need to worry about this because Autoprefixer is already integrated into our Gruntfile.
	</div>
</div>

<div class="clearfix visible-sm visible-md"></div>

<div class="col-lg-3 col-md-6 col-sm-6 col-xs-12">
	<h4>Column 3</h4>
		Bootstrap is downloadable in two forms, within which you'll find the following directories and files, logically grouping common resources and providing both compiled and minified variations.
</div>

<div class="col-lg-3 col-md-6 col-sm-6 col-xs-12">
	<h4><a href="#col4Content" data-toggle="collapse">Column 4</a></h4>

	<div id="col4Content" class="collapse">
		Bootstrap uses Grunt for its build system, with convenient methods for working with the framework. It's how we compile our code, run tests, and more.
	</div>
</div>

</div>
</div>
{% endhighlight %}

<hr>

<div class="container-fluid">
<div class="well visible-xs">
	<p>Screen &lt; 768px</p>
</div>

<div class="well visible-sm">
	<p>Screen &gt; 768px and &lt; 992px</p>
</div>

<div class="well visible-md">
	<p>Screen &lt; 992px and &lt; 1200px</p>
</div>

<div class="well visible-lg">
	<p>Screen &gt; 1200px</p>
</div>
</div>

{% highlight html %}
<div class="container-fluid">
<div class="well visible-xs">
	<p>Screen &lt; 768px</p>
</div>

<div class="well visible-sm">
	<p>Screen &gt; 768px and &lt; 992px</p>
</div>

<div class="well visible-md">
	<p>Screen &lt; 992px and &lt; 1200px</p>
</div>

<div class="well visible-lg">
	<p>Screen &gt; 1200px</p>
</div>
</div>
{% endhighlight %}

<hr>

<div class="container-fluid">
<div class="row">

<div class="col-md-8 col-md-offset-2">
<table class="table table-bordered table-striped table-hover">
<thead>
<tr>
<th class="text-center">Name</th>
<th class="text-center">Age</th>
</tr>
</thead>
<tr>
<td>Alice</td>
<td>23</td>
</tr>
<tr>
<td>Bill</td>
<td>47</td>
</tr>
<tr>
<td>Catherine</td>
<td>35</td>
</tr>
</table>
</div>

</div>
</div>

{% highlight html %}
<div class="container-fluid">
<div class="row">

<div class="col-md-8 col-md-offset-2">
<table class="table table-bordered table-striped table-hover">
<thead>
<tr>
<th class="text-center">Name</th>
<th class="text-center">Age</th>
</tr>
</thead>
<tr>
<td>Alice</td>
<td>23</td>
</tr>
<tr>
<td>Bill</td>
<td>47</td>
</tr>
<tr>
<td>Catherine</td>
<td>35</td>
</tr>
</table>
</div>

</div>
</div>
{% endhighlight %}

<h2>3. Carousel</h2>

<style>
.slide {
	height: 400px;
	background-repeat: no-repeat;
	background-position: center;
	background-size: cover;
}
.slide1 {
	background-image: url(http://c7.staticflickr.com/6/5057/5393392294_a08975b832_b.jpg);

}
.slide2 {
	background-image: url(http://c5.staticflickr.com/9/8754/16910348444_895262b1b9_k.jpg);
}
.slide3 {
	background-image: url(http://c5.staticflickr.com/2/1700/24422557244_60feff8dfc_k.jpg);
}
</style>

<div id="slideshow" class="carousel slide" data-ride="carousel">

<ol class="carousel-indicators">
<li data-target="#slideshow" data-slide-to="0" class="active"></li>
<li data-target="#slideshow" data-slide-to="1"></li>
<li data-target="#slideshow" data-slide-to="2"></li>
</ol>

<div class="carousel-inner">
	<div class="item active">
		<div class="slide slide1"></div>
		<div class="carousel-caption">
			<h1>Slide 1</h1>
		</div>
	</div>
	<div class="item">
		<div class="slide slide2"></div>
		<div class="carousel-caption">
			<h1>Slide 2</h1>
		</div>
	</div>
	<div class="item">
		<div class="slide slide3"></div>
		<div class="carousel-caption">
			<h1>Slide3</h1>
		</div>
	</div>
</div>

<a class="left carousel-control" href="#slideshow" data-slide="prev">
<span class="glyphicon glyphicon-chevron-left"></span>
</a>

<a class="right carousel-control" href="#slideshow" data-slide="next">
<span class="glyphicon glyphicon-chevron-right"></span>
</a>

</div>

{% highlight html %}
<style>
.slide {
	height: 400px;
	background-repeat: no-repeat;
	background-position: center;
	background-size: cover;
}
.slide1 {
	background-image: url(http://c7.staticflickr.com/6/5057/5393392294_a08975b832_b.jpg);

}
.slide2 {
	background-image: url(http://c5.staticflickr.com/9/8754/16910348444_895262b1b9_k.jpg);
}
.slide3 {
	background-image: url(http://c5.staticflickr.com/2/1700/24422557244_60feff8dfc_k.jpg);
}
</style>

<div id="slideshow" class="carousel slide" data-ride="carousel">

<ol class="carousel-indicators">
<li data-target="#slideshow" data-slide-to="0" class="active"></li>
<li data-target="#slideshow" data-slide-to="1"></li>
<li data-target="#slideshow" data-slide-to="2"></li>
</ol>

<div class="carousel-inner">
	<div class="item active">
		<div class="slide slide1"></div>
		<div class="carousel-caption">
			<h1>Slide 1</h1>
		</div>
	</div>
	<div class="item">
		<div class="slide slide2"></div>
		<div class="carousel-caption">
			<h1>Slide 2</h1>
		</div>
	</div>
	<div class="item">
		<div class="slide slide3"></div>
		<div class="carousel-caption">
			<h1>Slide3</h1>
		</div>
	</div>
</div>

<a class="left carousel-control" href="#slideshow" data-slide="prev">
<span class="glyphicon glyphicon-chevron-left"></span>
</a>

<a class="right carousel-control" href="#slideshow" data-slide="next">
<span class="glyphicon glyphicon-chevron-right"></span>
</a>

</div>
{% endhighlight %}

<h2>4. Dropdown Menu</h2>

<div class="container-fluid">
<div class="dropdown">

<button class="btn btn-primary btn-lg dropdown-toggle" id="dropdownMenu1" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">Favorite Hero
<span class="caret"></span>
</button>

<ul class="dropdown-menu">
<li class="dropdown-header">Marvel</li>
<li><a>Spiderman</a></li>
<li><a>Captain America</a></li>
<li><a>Iron Man</a></li>
<li role="separator" class="divider"></li>
<li class="dropdown-header">DC</li>
<li class="disabled"><a>Superman</a></li>
<li><a>Batman</a></li>
<li><a>Flash</a></li>
</ul>

</div>
</div>

{% highlight html %}
<div class="container-fluid">
<div class="dropdown">

<button class="btn btn-primary btn-lg dropdown-toggle" id="dropdownMenu1" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">Favorite Hero
<span class="caret"></span>
</button>

<ul class="dropdown-menu">
<li class="dropdown-header">Marvel</li>
<li><a>Spiderman</a></li>
<li><a>Captain America</a></li>
<li><a>Iron Man</a></li>
<li role="separator" class="divider"></li>
<li class="dropdown-header">DC</li>
<li class="disabled"><a>Superman</a></li>
<li><a>Batman</a></li>
<li><a>Flash</a></li>
</ul>

</div>
</div>
{% endhighlight %}

<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
<script src="{{site.url}}/assets/js/jquery.min.js"></script>
<!-- Include all compiled plugins (below), or include individual files as needed -->
<script src="{{site.url}}/assets/js/bootstrap.min.js"></script>