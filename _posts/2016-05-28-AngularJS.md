---
layout: post
title:  "AngularJS Demo"
date:   2016-05-28 00:00:00 -0400
categories: software
---

[AngularJS link](https://angularjs.org/){:target="_blank"}

<script src="{{site.url}}/assets/angular.min.js"></script>

{% raw %}
<div ng-app="">

<h2>Demo 1 - Say Hello</h2>
<p>Hello<span ng-show="name.length">, </span>{{ name }}!</p>
<p>Name: <input type="text" ng-model="name"></p>

</div>
{% endraw %}
