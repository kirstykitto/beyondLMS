---
layout: page
title: "Learning Record Stores"
description: ""
---
{% include JB/setup %}

<p>
	A <a href="http://tincanapi.com/learning-record-store/">Learning Record Store</a> (LRS) is just a database built specificially for storing data about learning (which means that LRSs are a part of the <a href="http://www.adlnet.gov/capabilities/tla/experience-api.html">Experience API (xAPI)</a> specification).
</p> 
<p>
	There are a number of LRSs that you could use if you decide that you want to use xAPI in your teaching beyond the LMS. Some will require more effort than others, and not all of them are <a href="http://opensource.org/licenses">Open Source</a>. (Some of the proprietary ones are quite expensive to use too.)  However, as the <a href="https://github.com/adlnet/xAPI-Spec/blob/master/xAPI.md">xAPI specification is open source</a> we will include them all here so that people who need one can choose between them easily. 
</p>
<p>
	Here are our recommendations, and instructions for how you could get started. 
	<ol>
		<h3>Cloud LRS servers</h3>
		<li>Rustici software offer a <a href="http://tincanapi.com/public-lrs/">Public LRS</a> service that lets you just try sending statements. This is entered as a default endpoint in our currently available <a href="">Twitter scraper</a> so if you authenticate a username and hashtag that you want to try scraping then it will send the resulting data there. </li>
		<li>SCORM Cloud</li> has a <a href="http://scorm.com/scorm-solved/scorm-cloud-features/">free service</a> (for up to 10 registrations) and also lets you scale up with a more extensive LRS system if you need to. This is a good first choice if you just want to try stuff out.</li>
		<li>The <a href="http://www.saltbox.com/wax-learning-record-store.html">Wax LRS Cloud</a> service offers a fairly advanced service for a price. They have a nice looking starter pack that you could explore for $39 a month.</li>
		<li>HT2 also offer a cloud version of <a href="http://learninglocker.net/services/">Learning Locker</a>. This is free for 14 days and then costs $199 per month.</li>


		<h3>Build your own solution on a server</h3>
		<li>
			As an open source product (GPL3) <a href="http://learninglocker.net/">Learning Locker</a> can be downloaded for free and installed on your own server. It takes a bit of expertise to build (you probably need some Systems Administration experience), but we have found the instructions by <a href="http://www.jpablo128.com/how_to_install_learning_locker/">jPablo128</a> and those on the <a href="http://docs.learninglocker.net/installation/">LL website</a> pretty useful.
		</li>
		<li>
			ADL also has an  LRS that you can install. This one is released under an Apache License. We have not tried to install it, so are not sure how easy it is, or how well it works, but the instructions are quite straightforward if you are used to using Ubuntu. It is available on <a href="https://github.com/adlnet/ADL_LRS">GitHub</a>.
		</li>
		<li>
			Sakai has released an OS LRS under its <a href="https://www.apereo.org/content/learning-analytics-initiative">Apereo Learning Anaytics Initiative</a>. Their <a href="https://github.com/Apereo-Learning-Analytics-Initiative/OpenLRS">OpenLRS</a> is a Java based LRS and is released under a <a href="http://opensource.org/licenses/ECL-2.0">Educational Community License (ECL2.0)</a>. We have not tried to install this one yet either, but as it is running on Java it looks pretty portable and easy to deploy. 
		</li>

		<h3>Fully fledged commercial offerings</h3>
		<li> 
			If you really decide that you want to make use of the xAPI at an institutional level then Rustici offer <a href="http://scorm.com/scorm-solved/scorm-engine/">SCORM Engine</a> and <a href="http://watershedlrs.com/">Watershed LRS</a>, and Saltbox offer a <a href="http://www.saltbox.com/learning-record-store-pricing.html">set of serious cloud solutions</a>.
		</li>
	</ol>

	<p> Even if you don't want to use the CLA toolkit, the xAPI standard gives you a really fantastic way to gather data about your students' behaviour beyond the LMS. If you are at all interested in performing Learning Analytics, then it is worth your while learning how to use LRSs.
	</p>
	
</p>