---
layout: post
title:  "Bootstrap Demo"
date:   2016-07-09 00:00:00 -0400
categories: software
---

[Bootstrap website](http://getbootstrap.com/){:target="_blank"}

[Youtube tutorial - by Derek Banas](https://youtu.be/gqOEoUR5RHg){:target="_blank"}

<!-- Bootstrap -->
<link href="{{site.url}}/assets/css/bootstrap.min.css" rel="stylesheet">

<h2>1. Page Header</h2>

<div class="container">

<div class="page-header">
	<h3>This is a Page Header</h3>
</div>

<div class="jumbotron">
	<p>This is a jumbotron content.</p>
</div>

</div>

{% highlight html %}
<div class="container">

<div class="page-header">
	<h3>This is a page Header</h3>
</div>

<div class="jumbotron">
	<p>This is a jumbotron content.</p>
</div>

</div>
{% endhighlight %}


<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
<script src="{{site.url}}/assets/js/jquery.min.js"></script>
<!-- Include all compiled plugins (below), or include individual files as needed -->
<script src="{{site.url}}/assets/js/bootstrap.min.js"></script>