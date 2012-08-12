---
layout: post
description: a post about Stockholm
category : blog
image: http://demo.brankic.net/bigbang/streched/images/slider3.jpg
tags : [stockholm]
---
{% include JB/setup %}

This Jekyll introduction will outline specifically  what Jekyll is and why you would want to use it.
Directly following the intro we'll learn exactly _how_ Jekyll does what it does.


The `layout` parameter in the YAML Front Matter defines the template file for which the given post or template should be injected into.
If a template file specifies its own layout, it is effectively being used as a `sub-template.`
That is to say loading a post file into a template file that refers to another template file with work in the way you'd expect; as a nested sub-template.



