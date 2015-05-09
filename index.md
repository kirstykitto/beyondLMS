---
layout: page
title: Beyond LMS
tagline: Learning Beyond the LMS
---
{% include JB/setup %}


<p> 
  The Learning Management System (LMS) pervades the EdTech space. This is great if you like using LMSs, you get content management tools, assessment tools, some analytics functionality, ... the works! (Well, at least a level of support from EdTech people and companies.) So why BeyondLMS? Because not everyone likes to use a Learning Management System. There is a small but significant cohort of teachers who like to teach beyond the LMS, and they are not well supported by the EdTech industry. Many of these people are the innovators of education. Imagine what could be unleased if they were supported with tools for teaching beyond the LMS. What new pedagogies and practices could emerge? 
</p>
<p>
  These pages attempt to provide some tools and ideas for those who want to teach outside of the LMS.  If you want to break free and go teaching in the wild, then hopefully you will be able to find some things here that you can use. Similarly, if you have at tool that you think might help someone escape the confines of the LMS, then you can <a href="includeMyTool.html">request that it be included</a>. If you would like to propose new ideas or ways in which other people can teach in the wild then we have a blog to which you can contribute these ideas. <a href="">Contact us</a> and find out how you can get involved.
</p>
<p>
  So.. why BeyondLMS? We hope to act as a meeting place for educators and solution developers. 
  More information will appear as we go, but for now, you might want to check out our first set of pages which introduce the <a href="..pages/clatoolkit.html">Connected Learning Analytics Toolkit</a>.
</p>

#####Recent Posts

<ul class="posts">
  {% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

