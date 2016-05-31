---
layout: post
title:  "AngularJS Demo"
date:   2016-05-28 00:00:00 -0400
categories: software
---

*Please contact me by <billy1341@gmail.com> if you are interested in AngularJS and want to make some projects*

[AngularJS link](https://angularjs.org/)

<script src="{{site.url}}/assets/angular.min.js"></script>

{% raw %}
<div ng-app="">

<h2>Demo 1 - Say Hello</h2>
<p>Hello<span ng-show="name.length">, </span>{{ name }}!</p>
<p>Name: <input type="text" ng-model="name"></p>

</div>
{% endraw %}
