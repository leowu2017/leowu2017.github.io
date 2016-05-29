---
layout: post
title:  "AngularJS"
date:   2016-05-28 00:00:00 -0400
categories: software
---

<script src="{{site.url}}/assets/angular.min.js"></script>
<script src="http://localhost:4000/assets/angular.min.js"></script>

<div ng-app="">

<p>Hello<span ng-show="name.length">, </span><span ng-bind="name"></span>!</p>

<p>Name: <input type="text" ng-model="name"></p>
</div>