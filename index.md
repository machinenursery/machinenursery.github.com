---
layout: page
title: Machine Learning For Beginners
---
{% include JB/setup %}

We're trying to learn about this whole machine learning/data science/big data thing and thought it'd be interesting to document that as we go. 

Hopefully it's useful and if you want to contribute, the repository containing all of this is on [github](https://github.com/machinenursery/machinenursery.github.com) so fork away and then send us a pull request.

#### [Mark Needham](https://twitter.com/markhneedham), [Jen Smith](https://twitter.com/jennifersmithco) & [Ashok Subramanian](https://twitter.com/a5hok).

***

## Kaggle

[Kaggle](http://www.kaggle.com/) is a website which hosts data related competitions - organisations provide data sets and problems they want solved and people compete to win prizes for coming up with the best solution.

They also recently started running competitions where the intention is to help people learn more about machine learning and the first of those is [Digit Recognizer](http://www.kaggle.com/c/digit-recognizer).

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