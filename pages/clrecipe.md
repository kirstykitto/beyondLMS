---
layout: page
title: "xAPI Recipe for Connected Learning Analytics"
description: ""
---
{% include JB/setup %}

<div class="sidebarnav">

	<h6>CLA Toolkit Pages</h6>
	<ul>

		<li><a href="/pages/clatoolkit.html">CLA Toolkit</a></li>
		<li><a href="/pages/OLTparticipants.html">Project Participants</a></li>
		<li><a href="/pages/clrecipe.html">CL Recipe</a></li>
		<li><a href="https://github.com/kirstykitto/CLAtoolkit">Project on Github</a></li>
	</ul>

        <a class="twitter-timeline" href="https://twitter.com/hashtag/clatoolkit" data-widget-id="605959017777631234" data-chrome="noscrollbar noborders nofooter" data-tweet-limit="1">#clatoolkit Tweets</a> <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
</div>

xAPI provides an extremely flexible way of representing events that can be saved to a Learning Record Store (LRS). The introduction of xAPI has been a great step forward for learning analytics because it allows a variety of events that originate from different systems to be tracked. The trouble with anything that is flexible is that there may be multiple ways to represent and track the same type of event and this has implications for building analytics tools that work across LRS installations. The community solution has been to design and share event representations as recipes. A recipe prescribes the structure for an xAPI and is made publically available via the Recipe Registry.

The Connected Learning Analytics (CLA) Toolkit is concerned with providing analytics for learning activities that occur outside of the traditional Learning Management System (LMS). The CLA Toolkit will allow teaching staff to import student interactions from social media platforms (e.g. Twitter, Facebook Groups, etc) into an LRS and provide advanced analytics. One of the first steps along this path has been to design an xAPI recipe for social media. The technical elements of the design decisions made in building the recipe have all been transparent and open for community feedback and contribution on the [CLRecipe Github site]( https://github.com/kirstykitto/CLRecipe).

While designing an xAPI recipe falls in the technical realm of data modelling, the team focus has really been to get an accurate representation of interactions that occur on social media platform and ensure that tracked data can easily be retrieved for advanced analytics such as social network analysis and content analysis (e.g., Cognitive Presence classification).  Moving beyond the LMS also means moving beyond simplistic aggregate counts of activity!

In summary the CLRecipe project:
<ol>
	<li>Provides common terminology for working with multiple social media platforms (e.g., Facebook Like and Twitter Favorite are both mapped to Like).</li>
	<li>Provides an xAPI Recipe for building xAPI statement for modeling social media interactions that include the relationship between social media posts (i.e. reply, share, like, tag, rate, etc) so that advanced analytics (including content analysis and social network analysis) can be performed. </li>
	<li>Provides recipe examples for Microblogging, Content Authoring, Content Collaboration and Content Curation.</li>
</ol>

Once the recipe stabilises, we’ll start providing examples of the type of analytics that can be provided for various types of learning activities that use different social media platforms and start to seek engagement from the learning design community. Lots more coming soon!

