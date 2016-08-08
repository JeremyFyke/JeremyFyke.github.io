---
layout: default
---

<a class="twitter-timeline" href="https://twitter.com/JeremyFyke">News</a> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

![Painting: Zaria Forman]({{ site.url }}/images/150728-zaria-forman-07.jpg)
<p style="text-align: center;"> <em><a href="http://www.zariaforman.com/">Zaria Forman</a>, Greenland no. 71, 2014</em> </p>

**Recent news**

{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
