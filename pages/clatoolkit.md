---
layout: page
title: "The Connected Learning Analytics (CLA) Toolkit"
description: ""
---
{% include JB/setup %}

<div class="sidebarnav">

	<h6>CLA Toolkit Pages</h6>
	<ul>

		<li><a href="/pages/clatoolkit.html">CLA Toolkit</a></li>
		<li><a href="/pages/OLTparticipants.html">Project Participants</a></li>
		<li><a href="/pages/clrecipe.html">CL Recipe</a></li>
	</ul>

        <a class="twitter-timeline" href="https://twitter.com/hashtag/clatoolkit" data-widget-id="605959017777631234" data-chrome="noscrollbar noborders nofooter" data-tweet-limit="1">#clatoolkit Tweets</a> <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
</div>

<p> 
	<a href="http://connectedlearning.tv/infographicv">Connected Learning</a> is a modern pedagogical approach holding that knowledge and learning is distributed across a social, conceptual network. It holds that when people forge, negotiate and nurture connections for themselves (between people, information, knowledge, ideas and concepts), learning is more powerful and sustainable.
</p>
<p>
	Ideally, such learning could happen anywhere. People would create <a href="http://teacherchallenge.edublogs.org/creating-a-pln/">Personal Learning Networks</a> within a <a href="https://coi.athabascau.ca/">Community of Inquiry</a>. They would use whatever tools they consider relevant to this process, and connect with whoever they consider relevant to their network... However, this open connectivism is difficult to achieve in our current educational paradigms. How can we help people to teach "in the wild"? <a href="http://en.wikipedia.org/wiki/List_of_learning_management_systems">Learning Management Systems</a> maintain a <a href="http://mfeldstein.com/state-us-higher-education-lms-market-2014-edition/">dominant position</a> in the education sector, which means that technical support is generally provided only for those teachers who choose safety over openness. 
</p>
<p>
	It doesn't matter that our students tend to wander off into the wild..  a LMS might provide discussion fora, wikis, file sharing services, but our students are often not even there. They tend to favour tools that they are using already, things like Google drive, Facebook, Dropbox, StackExchange and others.  This affects what Learning Analytics (LA) we can carry out, we only see a tiny portion of their behaviour, and they almost never get to see any data about their own learning behaviour. LA is a capability usually provided by LMS vendors, and this makes it difficult to provision LA capabilities beyond the LMS. 
</p>
<p>
	The CLA toolkit is one solution that we are creating in an attempt to fill this gap. It helps students and teachers to harvest data about their activities in standard social media environments, and then provide immediate feedback and reports. It is currently in development, but the basic schema for the CLA toolkit is sketched out below.	   
	<img src="../assets/images/schema.jpg" alt="A basic schema for the CLA toolkit" width='635' border="5">
</p>
<p> 
	The CLA toolkit relies heavily upon the <a href="http://www.adlnet.gov/tla/experience-api/">Experience API (xAPI)</a>, which makes it possible to capture student behaviour in a highly flexible manner and send it to a Learning Record Store (LRS) for immediate or later analysis. Indeed, if you are going to use the CLA toolkit then you will need to have access to a <a href="http://tincanapi.com/learning-record-store/">Learning Record Store</a>. We give some basic information about LRSs that you could use with the CLA toolkit on <a href="../pages/lrs.html">another page</a>.
</p>
<p>
	Importantly, the CLA toolkit only works within specified learning activities. We do not harvest all data pertaining to a student's interactions in social media, only the data that pertains to their learning. Sudent's sign up to data harvesting for specified social media, and only for specific activities. Thus, we harvest data that relates to a Twitter hashtag, or a Facebook group, and the before a teacher can link this data to specific students, students will need to tell their instructor their relevant social media username. This preserves student privacy, giving them control over what data they choose to gather. Dashboards have been created for both students and instructors, and enable students to explore information about their social network, the content that they are discussing, and their overall activity within the system. More tools will become available as the CLA toolkit develops.
</p>
<p>
	We harvest data using standard social media APIs, and currently have tools that collect data for:
	<dl>
		<dt>Twitter:</dt> Students sign up to having their data harvested for a specific Twitter hashtag related to a learning activity. Then their tweets to this hashtag will be captured by the CLA toolkit.
		<dt>Facebook:</dt> Students sign up to having their data harvested for a specific Facebook group where they will be meeting online as a part of their learning.
	</dl>	   
	These tools are due to be rolled out at QUT with a couple of trial classes starting in late July 2015 - watch this space! (We will <a href="/archive.html">blog</a> about this as we go.)
</p>
<p>
	We have more tools in development that interface with:
	<dl>
		<dt>Google+</dt>
		<dt>StackExchange</dt>
		<dt>Google Docs</dt>
		<dt>RSS feeds (i.e. blogs)</dt>
	</dl>
	but other tools are possible too. We will update this list as everything develops.
</p>

<h2>Source Code</h2>
<p>If you want to go and check out the source code, then it is available on <a href="https://github.com/kirstykitto/CLAtoolkit">GitHub</a>, along with a  <a href="https://github.com/kirstykitto/CLRecipe">Connected Learning Recipe</a> that we are currently working on. Recipes are an important common vocabulary for xAPI which will make it easier to perform LA on diverse datasets, so they are very important to this project. We discuss this recipe on <a href="../pages/clrecipe.html">another page</a>.
</p>
<h2>Publications</h2>
<ul>
	<li> K. Kitto, S. Cross, Z. Waters & M. Lupton. <a href="http://dl.acm.org/citation.cfm?id=2723627">Learning Analytics beyond the LMS: the Connected Learning Analytics Toolkit</a>.  In Proceedings of the Fifth International Conference on Learning Analytics And Knowledge (LAK '15).  ACM, New York, NY, USA, 11-15. (See the free eprint <a href="http://eprints.qut.edu.au/81343/">here</a>.)
	</li>
</ul>

