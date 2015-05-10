---
layout: page
title: "The Connected Learning Analytics (CLA) Toolkit"
description: ""
---
{% include JB/setup %}


<p> 
	<a href="http://connectedlearning.tv/infographicv">Connected Learning</a> is a modern pedagogical approach holding that knowledge and learning is distributed across a social, conceptual network. It holds that when people forge, negotiate and nurture connections for themselves (between people, information, knowledge, ideas and concepts), learning is more powerful and sustainable.
</p>
<p>
	Ideally, such learning could happen anywhere. People would create <a href="http://teacherchallenge.edublogs.org/creating-a-pln/">Personal Learning Networks</a> within a <a href="https://coi.athabascau.ca/">Community of Inquiry</a>. They would use whatever tools they consider relevant to this process, and connect with whoever they consider relevant to their network... However, this open connectivism is difficult to achieve in our current educational model. <a href="http://en.wikipedia.org/wiki/List_of_learning_management_systems">Learning Management Systems</a> maintain a <a href="http://mfeldstein.com/state-us-higher-education-lms-market-2014-edition/">dominant position</a> in the education sector.
</p>
<p>
	This affects what Learning Analytics (LA) we can carry out. Often, LA is a capability provided by LMS vendors, and this makes it difficult to use LA to "in the wild" (i.e. beyond the LMS). The CLA toolkit is one solution that we are creating in an attempt to fill this gap. It helps students and teachers to harvest data about their activities in standard social media environments, and then provide immediate feedback and reports. It is currently in development, but the basic design is sketched out below:	   
	<img src="../assets/images/schema.jpg" alt="A basic schema for the CLA toolkit" height="259" width="413" border="5">
</p>
<p> 
	The CLA toolkit relies heavily upon the <a href="http://www.adlnet.gov/tla/experience-api/">Experience API (xAPI)</a>, which makes it possible to capture student behaviour in a highly flexible manner and send it to a Learning Record Store (LRS) for immediate or later analysis. Indeed, if you are going to use the CLA toolkit then you will need to have access to a <a href="http://tincanapi.com/learning-record-store/">Learning Record Store</a>. We discuss this Open Source tool on <a href="../pages/lrs.html">another page</a>.
</p>
<p>
	We have some prototype tools that are functional enough to be tested by the general community. They interface with:
	<ul>
		<li>Twitter</li>    
		<li>Facebook</li>
	</ul>	   
	<!--You can try them out with a quick  out at <a href="">this page</a>.-->
</p>
<p>
	We have more tools in development that interface with:
	<ul>
		<li>Google+</li>
		<li>StackExchange</li>
		<li>Google Docs</li>
		<li>RSS feeds (i.e. blogs)</li>
	</ul>
	we will update this list as everything develops.
</p>
<p>If you want to go and check out the source code, then it is available on <a href="https://github.com/kirstykitto/CLAtoolkit">GitHub</a>, along with a  <a href="https://github.com/kirstykitto/CLRecipe">Connected Learning Recipe</a> that we are currently working on.
</p>
Some details of our early work can be found in this paper: 
<ul>
	<li> K. Kitto, S. Cross, Z. Waters & M. Lupton. <a href="http://dl.acm.org/citation.cfm?id=2723627">Learning Analytics beyond the LMS: the Connected Learning Analytics Toolkit</a>.  In Proceedings of the Fifth International Conference on Learning Analytics And Knowledge (LAK '15).  ACM, New York, NY, USA, 11-15. (See the free eprint <a href="http://eprints.qut.edu.au/81343/">here</a>.)
	</ul>
	<p class="lead">Scaling up</p>
	<p>This work has been funded by the Australian Government's Office for Learning and Teaching (OLT). 
		<p><b>ID14-3821:Enabling connected learning via open source analytics in the wild: learning analytics beyond the LMS</b><br>
			Office for Learning and Teaching, $320,000 over 2 years (2015-2017)<br>
			Lead institution: Queensland University of Technology<br>
			Partner institutions: University of South Australia; University of Technology, Sydney; University of Sydney, University of Texas, Arlington<br>
			Team: Kirsty Kitto (Lead), Mandy Lupton, John Banks, Dann Mallet, Peter Bruza (QUT)<br>
			Shane Dawson, Dragan Gasevic (UniSA); Simon Buckingham Shum (UTS); Abelardo Pardo (Uni Sydney); George Siemens (Uni Texas, Arlington).
			<p>
				This project aims to improve the quality of student engagement and learning in collaborative online environments by incorporating and analysing social media platforms that students already use. It will create an easy to use and open source Connected Learning Analytics (CLA) toolkit utilising the latest mathematical and computational approaches, grounded in connected learning pedagogy.
				<br>
				<b>Keywords:</b> Social Learning Analytics, Connected learning, Semantic Technologies, xAPI, mathematical modelling
			</p>
			<p>
				If you want to find out more then you can download the project proposal <a href="../assets/papers/prop.id.qut.kitto.2014-front.pdf">here</a>, and please use this email to <a href="mailto:CLAtoolkitemail">contact us</a> if you would like to get involved in some way. 
			</p>
