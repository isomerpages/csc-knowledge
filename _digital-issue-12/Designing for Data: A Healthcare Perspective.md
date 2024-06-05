---
title: "Designing for Data: A Healthcare Perspective"
permalink: /designing-for-data-a-healthcare-perspective/
variant: markdown
description: ""
---
<style>
		
.back a
{
	color: #9f2943;
	font-weight: bold;
}

.break
{
   border-top: 1px solid  black;
   border-bottom: 1px solid black;
	 padding:20px;
	text-align:center;
	font-size:30px;
	margin-top:50px;
}
	
.break1
{
	font-family: Georgia;
	font-size:20px;
	font-style: italic;
	font-weight: bold;
}
	
.num ol li

{
font-size: 16px;
}			

	

	
.author
{
border-bottom: 1px solid black;
margin-top:40px;
padding-bottom:30px;
border-top: 1px solid black;
}
	
.author p
{
font-size: 15px;	
line-height: 22px;
}
	
.notestop ol li
{
font-size: 15px;
line-height:22px;
}		

.containerbox
{
background-color: #101F42;
padding: 30px;
color: white;	
}
	
	
</style>

<em><small>ETHOS Digital Issue 12, Apr 2024</small></em>
<div class="background-image">
<img src="/images/Ethos_Images/Ethos_Digital_Issue_12/D12_Banner_Resize_3.jpg">
</div>
<h3>How does your current work support the healthcare sector in Singapore?</h3>

<p>There are three key strategic enablers underlying any modern healthcare system. The first is financing. The second is manpower, both in terms of the numbers of people needed, and the skillsets you need to have. And the third is technology and data, which is where I come in.</p>

<p>The challenge for healthcare in Singapore, like in many places, is that capacity building and investment into public healthcare enablers have tended to focus more on the area of acute care, including the public hospitals, over other aspects such as preventive health and primary care or intermediate long-term care (ILTC), which includes care for the elderly. Acute care accounts for the majority of our health budget, compared to a low figure for preventive care. Arising from our fast-ageing society and the rising cost of healthcare, we have to make important changes to our healthcare system to make it sustainable. This is what’s driving initiatives such as the Healthier SG movement, which shifts the focus to preventive health, primary care, and getting individuals and the community to take ownership of health outcomes.<sup><a href="#notestop">1</a></sup> This shift has significant implications for how we design and apply technology and the use of data.</p>

<p>Clinicians generally like their IT systems to be customised to their needs. A cancer expert in one hospital may have a different one from an expert in another hospital. With Singapore’s public healthcare system organised into three clusters, we often have multiple IT systems—sometimes different ones in the same cluster. Today, we have several hundred IT systems in public healthcare, which is many more than we need. In 2011, we came up with the National Electronic Health Record (NEHR) to consolidate health records across all the different acute public healthcare institutions under the Ministry’s mandate. This work has been the focus of my predecessors over the past decade.</p>

<p>What the Healthier SG initiative has done is to oblige us to look beyond the acute care space and more deeply to other sectors of healthcare, including primary care—which includes the approximately 1,200 general practitioners in Singapore. There are also other practitioners in the private sector, including specialists, hospitals and pharmacies, whose records are not currently included in the NEHR. </p>

<p>We are now laying the groundwork to move into these new sectors, from a data point of view. The upcoming Health Information Bill, for instance, will provide us with the legislative backing to make it possible to extend our data reach beyond the acute public healthcare system.<sup><a href="#notestop">2</a></sup> </p>


<h3>What challenges does this data expansion present in your field of work?</h3>

<p>One challenge is getting everyone on board. For acute care, MOH oversees the public hospitals, so we can mandate their participation to some degree. For preventive care, MOH also oversees the polyclinics, and while the government does not directly fund the general practitioners, we can use incentives, along with regulation, to get them to contribute their health data. The ILTC and ageing sectors, however, are based mostly on goodwill and community effort, so there is less leverage to get them to participate—and in particular to enforce data security. </p>

<p>The 2018 SingHealth cyberattack was a milestone event.<sup><a href="#notestop">3</a></sup> We had planned to table the key elements of the Health Information Bill as early as 2019, but because of this major data security breach, we had to hold back until we were sure we could protect this sensitive information. Following the report of the Public Sector Data Security Review Committee, we have spent the past few years hardening our systems, redesigning our IT and data infrastructure, and clarifying the concepts we want to adopt for data management and cybersecurity. </p>

<p>We have also sought to clarify our data governance policy: once we collect everyone’s health data, how do we manage it responsibly? A few years ago, the Smart Nation Office laid the groundwork for data governance, which has been helpful. Today, any Ministry can ask another Ministry for data, with the default being to agree to provide it. This is useful because we are starting to pay more attention to the social determinants of health: if you belong to particular vulnerable grounds, it will have an impact on your health, your ageing, your access to caregiving, and so on. Health data therefore needs to be looked at alongside other factors. Once the Health Information Bill is in place, we will have access to almost all the key national clinical data, as well as the socioeconomic data that resides across government. </p>

<p>The rise of wearables and other lifestyle tracking technologies—for sleep, training, food intake, health monitoring and so on—along with nation-wide initiatives such as HPB’s Healthy365 app, means we could also collect lifestyle data as well, to help us better analyse trends that impact Singaporeans’ health. In a few years’ time, Singapore could be the most advanced nation in the world in terms of population data. Nobody has managed to collect and integrate clinical and lifestyle data on a national scale before, so there is immense opportunity for us to innovate in this area. But the data has to be treated with respect and it has to be governed well. </p>

<p>The challenge then is also an opportunity: how best to steward and make use of this wealth of data.</p>

<h3>What considerations guide your approach to the design and governance of data systems at MOH?</h3>

<p>As Covid-19 has demonstrated, we do need very good data as well as aggregated data for analysis to reap the benefits of an integrated data system. This requires fundamentals such as interoperability and data standardisation. It is about getting the plumbing right so that other applications can work well—we have teams in MOH looking at data engineering, data cleansing, which is to do with this foundational work. My advantage in wearing both hats (CIO and CDO) is that I can help ensure that our IT systems are giving us good data, which we can then use for analytics. The earlier systems in many government agencies were built for transactions and are not geared to generate good data. Besides, different clinicians also often want different things from their IT and data systems. We must be able to synthesise all these different views and data flows, and still act upon it.</p>

<p>My approach is to develop a common architecture. It is like building a road network. Everyone has to use it, with top-down mandated rules like traffic rules. But there can be some flexibility in the small side roads near your estate, while the expressways must have common rules everyone abides by. In two to three years, we should be able to get our architecture for the health system in place.</p>

<p>Another consideration I am mindful of is cost. The temptation in tech is always that there are so many sexy things to do. But tech also contributes to rising costs. New clinical treatments and drugs can be expensive. IT systems and data centres must be developed and maintained. We may gain better care, new capabilities, higher quality services, more resilience and perhaps 24/7 availability. But all these do not necessarily come cheap. How then do you manage all this tech investment so it can give a good return in value?</p>

<p>Technologists can get carried away. The consultancy Gartner has a concept called RGT: Run, Grow, Transform.<sup><a href="#notestop">4</a></sup> The idea is that if you have $100 in your budget, it will take up to $80-$90 to keep the lights on and your operations running. This means there are fewer dollars to grow and transform. I come from the private sector, so I am more cost-conscious: if we keep adding systems, we will soon use up our budget on running costs. So we have to constantly prune our operational costs to allow for growth and transformation. </p>

<p>We will also need to think more carefully about digital inclusion. For instance, the number of elderly seniors who use e-health systems properly is not high. As we add more such systems, we must make sure we do not leave them and other disadvantaged groups out. For instance, we do give full paper of records to those who do not want to digitally enrol in Healthier SG, particularly those among the elderly who cannot cope. There will also be others, such as some with special needs, who may not be able to manage certain aspects of the new systems. We may think about those who are in and those who are out of our initiatives and systems, but we also need to think through the cases who fall between. </p>

<p>In the end, these systems are about supporting and augmenting our clinicians, not replacing good ones. What we are trying to achieve is what the military calls Ops-Tech integration. We need to bring clinicians, policymakers and technologists to the table together as equal partners, to have deeper conversations about what the future looks like, and then we design towards to that. </p>

<div class="author">
<h6>ABOUT THE AUTHOR</h6>	
<p><b>Colin Lim is the Chief Information Officer and Chief Data Officer of the Singapore Ministry of Health (MOH). He is also Group Director, InfoComm, Technology and Data Group. Prior to MOH, he was the founder and CEO of mobilityX, a start-up that received funding from SMRT and Toyota Tsusho. His previous experience includes the private (IBM UK and SMRT) and public (Singapore Administrative Service—Ministries of Home Affairs, Manpower and Transport, as well as the Land Transport Authority) sectors.</b></p><b>
</b></div><b>


<div class="notestop" id="notestop">
<h6>NOTES</h6>
<ol>
<li id="num1"><a href="https://www.healthiersg.gov.sg/">https://www.healthiersg.gov.sg/</a></li>
<li id="num2"><a href="https://www.healthinfo.gov.sg/overview/introduction/">https://www.healthinfo.gov.sg/overview/introduction/</a></li>
<li id="num3"> Irene Tham, <a href="https://www.straitstimes.com/singapore/personal-info-of-15m-singhealth-patients-including-pm-lee-stolen-in-singapores-most">"Personal info of 1.5m SingHealth patients, including PM Lee, stolen in Singapore's worst cyber attack"</a>, <em>The Straits Times</em>, October 2, 2021.</li>
<li id="num4"> Sharon George, <a href="https://www.gartner.com/smarterwithgartner/align-it-functions-with-business-strategy-using-the-run-grow-transform-model">"Align IT Functions With Business Strategy Using the Run-Grow-Transform Model"</a>, <em>Gartner</em>, December 8, 2017.</li>

</ol>	
</div>





<br><br>
<div class="back">
<a href="/ethos/">Back to Ethos Page</a>	
</div></b>