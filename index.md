---
layout: page
title: Machine Learning For Beginners
---
{% include JB/setup %}

We're trying to learn about this whole machine learning/data science/big data thing and thought it'd be interesting to document that as we go. 

Hopefully it's useful and if you want to contribute the repository containing all of this is on [github](https://github.com/machinenursery/machinenursery.github.com) so fork away and then let us know what you want to add.

#### [Mark Needham](https://twitter.com/markhneedham), [Jen Smith](https://twitter.com/jennifersmithco) & [Ashok Subramanian](https://twitter.com/a5hok).

***

## From around the web
<div class="posts">
		<ul>
  			{% for post in site.posts %}
	  			{% assign post = site.posts.first %}
	  			{% assign content = post.content %}
				{% if post.title %}
				    <li class="home">{{ post.date | date: '%d %B, %Y' }} &raquo; <a href="{{ root_url }}{{ post.url }}">{{ post.title }}</a></li>
				{% endif %}
			{% endfor %}
		</ul>
</div>