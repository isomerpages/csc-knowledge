---
title: "LLMs In The Public Sector: Minding What's Missing"
permalink: /llms-in-the-public-sector-minding-what-s-missing/
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

	margin-top:50px;
}
	
.break1
{
	font-family: Georgia;
	font-size:20px;
	font-style: italic;
	font-weight: bold;
}

.break2
{
background-color: #F7943E;
margin-top:30px;
padding:20px;
color:white;	
border-radius: 20px;	
}
	
.break2 q
{
font-family: Georgia;	
font-size:20px;
font-style: italic;
font-weight: bold;	
}
	
.break2 a
{
	color: white;
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
background-color: #eff0e9;
padding: 30px;
margin-top: 30px;
color: black;
}	
	

	
.containerbox a
{
	text-decoration: none;
	color:white;
}	
	
.containerbox ol li
{
	font-size: 15px;
	line-height:20px;
}
	
h3 {
color:#049c8c;
}
	
	
</style>



<em><small>ETHOS Issue 27, Forthcoming</small></em>

<div class="background-image">

<img src="/images/Ethos_Images/Ethos_Issue_27/LLMs_In_Public_Sector_banner.jpg">

</div>

  

<p>  As large language models (LLMs) are increasingly incorporated into government functions, there is a risk that people will trust these tools more than they should, resulting in poor decisions and poor outcomes. We need to ensure that this powerful technology is used in a way that is effective, safe, and equitable.</p>


<h3>Opportunities &amp; Risks for LLMs in Government Work</h3>

<p>While there are many applications of LLMs in the public sector, most fall into two broad categories.</p>

<p>The first is information retrieval. Unlike traditional search algorithms, LLMs can be trained to ‘guess’ the contextual intent of a query, allowing an approach called semantic search. This means users can find the information they need using natural language queries, without having to be subject experts or get the phrasing just right. Often manifest as chatbots, or simply as more robust responses to conventional searches, semantic search may also be used by government officials to identify and retrieve documents they need for work.<sup><a href="#notestop">1</a></sup></p>

<p>The risks of using LLMs in information retrieval are well-known: LLMs may hallucinate incorrect but plausible answers to questions. In addition to core research and engineering work to alleviate these issues, pragmatic approaches—such as pairing the LLM’s semantic search with pre-vetted responses, documents, and links—can enable LLMs to be integrated into search-based applications with relative ease. Importantly, from the point of view of validating results, the rate of errors from such searches can be measured and mitigated. </p>
	
	
<p>The second major category of government use cases involves the organisation and summarisation of unstructured data. Sometimes the goal may simply be data cleaning: for example, identifying and removing duplicates. In many others, however, the goal is to synthesise large amounts of unstructured information. One may want to understand the main themes from public comments,<sup><a href="#notestop">2</a></sup> key ideas from qualitative research data,<sup><a href="#notestop">3</a></sup> trends from court case documents,<sup><a href="#notestop">4</a></sup> or summarise the main points from a recorded online meeting.<sup><a href="#notestop">5</a></sup> A close cousin of summarisation is ideation: given some inputs, the LLM may provide ideas for initiatives or solutions as a starting point for further thinking and brainstorming. Unlike information retrieval, ideation is more open-ended.</p>


<div class="break">
<p class="break1">Determining what is relevant or salient involves some form of judgement.</p>

</div>	



<p>The summarisation (and ideation) functions of LLMs can enable the large amount of unstructured data in the public sector to be leveraged for the public good. Unlike for information retrieval, however, much less attention has been given to the risks associated with using LLMs for summarisation and how to mitigate them. The challenge of summarisation is that one inherently loses information in the process: the entire point is to highlight the most salient points and remove what is redundant or irrelevant.</p>



<p>However, determining what is relevant or salient involves some form of judgement. Information essential for one downstream task may not be essential for another. For example, a meeting summary that synthesises the final consensus and action items may leave out dissenting opinions and concerns, which may be important to retain. A summary may also elevate certain perspectives over others. For example, a summary of public discussions may inadvertently privilege comments made by a particular ethnic group or from a certain perspective, e.g. comments focused on convenience over comments highlighting environmental risks.</p>


<p>How can we check if a summarisation system is failing in these ways? While the field of natural language processing has been studying summarisation for some time, the main difference between earlier works and LLM-based summarisation is that prior work tended to focus on much more specific settings. For example, a pre-LLM summarisation system may have been trained specifically to summarise only short news articles. Such a system would have been trained on human-generated bullet points or tags and validated against humangenerated summaries.</p>


<div class="break">
<p class="break1">LLMs are being applied
to many more settings
than for which quality
benchmarks exist.</p>

</div>	



<p>However, the ease with which LLMs summarise many different kinds of documents means that they are being applied to many more settings than for which quality benchmarks exist. Indeed, from a machine learning perspective, even use cases that look similar—such as summarising meetings for one agency versus another, or comments regarding one law or another—are actually quite different.</p>

<p>As the use contexts for LLM summarisation increase, it is highly unlikely that we will be able to keep up in terms of validating the quality of the summarisation system in advance. We need a paradigm shift in thinking about validation: while we should always check as much as we can about a system in advance, we must prepare for a reality where users of LLM-based summarisation will need to validate the summaries at task-time, for their context and their specific set of inputs. We must develop interface design that supports task-time human inspection, especially at scale.<sup><a href="#notestop">6</a></sup></p>


<h3>The Need for Task-Time Evaluation</h3>

<p>The standard way to validate AI systems has been to test the system on some held-out data with gold-standard answers. The logic is that if an AI system performs well on these unseen queries, then it will likely perform well in real settings. When acquiring a new AI-based system, a government agency can and should run the system on some of its data to determine how well it performs. For example, in the context of information retrieval, one could create a test set of questions and answers drawn from a public agency’s specific intended purpose (for example, questions about policies for food and safety inspections). Next, one would check how well the LLM performs on these. This evaluation prior to deployment can tell us whether the system is likely to perform well on similar questions if put into use.</p>
	
	
<p>That said, LLMs and other foundation models have ushered in a new era of challenges for vetting machine learning models. There are two key reasons for this.</p>

<p>The first is due to the large surface of both their inputs and outputs. For example, a task like counting types of traffic through an intersection in video footage may seem complex because of the many appearances of people and their modes of locomotion, but there are still sensible ways to describe errors and predict a system’s responses ahead of deployment. When it comes to LLMs, however, it is likely impossible to describe all the types of documents a system may be asked to summarise, or all the kinds of ideas it may be asked to generate, in a way that would meaningfully anticipate its future performance. These models are also too big to interpret for global qualities (e.g., overall relying on the right features). Thus, our toolkit of ways to vet these models prior to deployment, including those involving human inspection of models and data, will fall short.</p>
	
	
	
<p>The second reason is the expansion of tasks that LLMs and other foundation models can support. Indeed, one of the draws of LLMs for public sector uses is that they often do not require much fine-tuning or additional training. With a bit of prompt engineering, LLMs seem to be able to summarise meeting minutes for any kind of meeting, synthesise documents from any unit, identify the common themes in any set of reports or comments. We can apply them to many tasks, much more easily than other AI systems.</p>


<div class="break">
<p class="break1">There will be many more
situations for which
the correctness of a
summarisation output is
dominated by user and task
specific considerations.</p>

</div>	


<p>However, this also means that there will be many more situations for which the correctness of a summarisation output is dominated by user and task specific considerations, making it difficult to validate the system in advance. What a specific user considers a useful response will depend on their values, perspectives, contexts, goals, and preferences.<sup><a href="#notestop">7</a></sup>Just because one user believes that an input-output pair is of high quality does not mean another user will agree.</p>

<p>This issue is further compounded because it may be difficult for a user to specify exactly what type of summary they want in a way that is sufficiently precise to the LLM. The user may also not know exactly what they require in advance. Their goals may be evolving as they learn more about the context and the data.<sup><a href="#notestop">8</a></sup> For example, a government official may first use an LLM to identify common patterns in traffic incidents, then refine their investigation to whether the types of incidents that occur around rush hour are different than those that occur late at night.</p>
	
	
	
<p>These challenges call for a fundamental shift in how government officials approach validation in LLMs and other foundation models. While prior testing of these models will continue to be important—for example, one might test to see if an LLM produces reasonable summaries of case notes for a social worker—such tests can only be used to flag problems. If a model does poorly on these initial tests, we should be concerned about its performance if deployed. But if it passes these tests, we cannot then be confident in its performance once deployed.</p>

	
<p>How then do we use LLMs with confidence? We need ways to vet these systems at task-time, while users are working in their own contexts on tasks that matter to them. A small group of engineers and domain experts can no longer vet the system for most errors in advance. Instead, workflows and interfaces must be designed and built that empower users to efficiently and accurately determine whether the output created in response to their specific input is in accordance with their needs and values.<sup><a href="#notestop">9</a></sup></p>


<div class="break">
<p class="break1">It may be difficult for a user to specify exactly what type of summary they want in a way that is sufficiently precise to the LLM.</p>

</div>	



<p>Users will need to play a part in contextually evaluating responses—not on behalf of the system designer, but for their own benefit.<sup><a href="#notestop">10</a></sup> At the same time, system and evaluation designers must work to ensure that the system (1) has minimal negative impact on users if it outputs information or summaries that do not match the user’s contexts, preferences, and goals and (2) supports user in creating an accurate mental modelling of what the AI system is doing for their context.</p>





<p>The idea of having to validate a system at task time is not new. For example, consider how we currently handle suspicious emails, text messages, or phone calls. While some messages may automatically go to a spam folder, others are tagged as potentially spam. This encourages the user to pay more attention to that specific message or call—a form of tasktime facilitation—but leaves the final decision of how to treat the message up to the user. This approach acknowledges that spam-detection systems cannot be fully vetted in advance. In the same way, spell and grammar checking systems do not automatically change potentially incorrect text for you; they highlight potential errors and posit suggestions</p>


<p>The core challenge, when it comes to applying these ideas to using LLMs for summarisation, is how to make this process of task-time validation sufficiently easy. Underlining a supposedly misspelled word adds very little burden for great benefit. What is the equivalent of that for LLMs?</p>


<h3>Mitigating the Risks of the Missing</h3>


<p>In general, irrelevant information or poorly aligned ideas that are surfaced by the LLM might be an annoyance but are easily disregarded.11 However, what is not surfaced by the LLM can cause much larger issues. For instance, if a case worker uses a summary to quickly check for a person’s relevant history, and the summary excludes the fact they are supporting a relative with a severe chronic condition, then incorrect presumptions might be made about the person’s available time and finances. Automated meeting minutes may leave out important minority viewpoints, and then those viewpoints will be lost to everyone who only looks at the summary. To effectively use LLMs for summarisation and ideation, we need ways of identifying the missing, at task-time.</p>


<div class="break">
<p class="break1">Irrelevant information or poorly aligned ideas are easily disregarded. What is not surfaced by an LLM can cause much larger issues.</p>

</div>	



<h4><i>Addressing what’s missing in summarisation</i></h4>

<p>For summarisation, we do know exactly what the complete information is: it is everything the user has provided to the LLM to summarise. Thus, defining what has been left out is relatively clear: it is all the information that is in the documents but not in the summary.</p>

<p>The question is, of all the things that we know have been left out by the summary, what may have been left out inappropriately? Only the human user during task time can fully answer that question, given their context and goals, and yet the full information is too large for someone to go through and check.<sup><a href="#notestop">12</a></sup></p>


<p>One approach to resolve this could be to <b>summarise what has been left out</b>, with the goal of helping the user efficiently identify information that they might have wanted but the original summary did not include. However, the designer must then consider how to help the user notice and recover when the system is confidently wrong about what it left out.<sup><a href="#notestop">13</a></sup></p>


<p>A possibly more robust approach could be <b>to organise and render the excluded information so that users are more likely to notice and discern patterns in the left-out data</b>. To do this, we might use tools and techniques from data visualisation, clustering, and theories of human concept learning<sup><a href="#notestop">14</a></sup> to enable a user to quickly skim large amounts of data. For example, clustering parts of public comments that an LLM did not include in a summary might help a government official quickly realise that many clusters are indeed irrelevant (e.g. variants of salutation text) but some should not have been excluded (e.g. a pattern around issues caretakers face that seemed too disparate for the LLM to correctly synthesise).</p>


<p>The user could also interact with this rendering to ask for the missing to be sliced in certain ways, e.g. to show all information deemed irrelevant that referenced a particular aspect of a regulation, to specifically check if the original summary was sufficiently complete. These tools for rendering missing information can be built in-house by the government unit or requested when an LLM-based tool is purchased. Either way, such tools are needed for government officials and citizens to use LLMs responsibly.</p>



<div class="break">
<p class="break1">The question is, of all
the things that we know
have been left out by
the summary, what
may have been left out
inappropriately?</p>

</div>	





<h4><i>Addressing what’s missing in ideation</i></h4>

<p>While in summarisation we have a clear sense of what is being left out, for ideation it is less clear how to imagine what ideas are being excluded. Particularly when LLMs are trained with data largely from non-local contexts, there may be gaps in the kinds of suggestions it may provide. Nevertheless, there are still some concrete ways forward.</p>



<p>For example, one can <b>group the different ideas generated</b> to help the user (1) recognise additional ideas within existing clusters and (2) imagine ideas that go beyond the existing clusters. If an LLM is used to imagine ways to improve the efficiency of services, and the generated ideas cluster around streamlining forms and processing payments, then that may help a user realise that LLM is not outputting ideas related to other aspects that may matter, such as access to transport for physical meetings.</p>


<div class="break">
<p class="break1">When LLMs are trained with data largely from non-local contexts, there may be gaps in the kinds of suggestions it may provide.</p>

</div>	



<p>Ideas can also be <b>clustered along known factors</b> (e.g. risk, cost, fun, or value to certain constituencies) to reveal what types of ideas are more or less common. This process could help a user realise that all the ideas for improving traffic safety are very costly or are relevant only for certain parts of the city, providing the opportunity to prompt the LLM or consider independently less costly solutions or solutions for other parts of the city.</p>

<p>Finally, as these systems evolve, there may be more technical solutions <b>for the LLM to itself expose what parts of representation space it is and is not surfacing</b> in a way that aligns with what the user’s way of thinking about the problem.</p>




<h4><i>Accounting for missing voices</i></h4>



<p>Beyond focusing on what is missing from a summary or set of ideas in terms of content, an important category to consider in government work is that of missing voices. This is especially important in the context of leaving out information or opportunities that are relevant to marginalised communities.</p>


<p>For certain common types of categories, such as culture or political leaning, we may be able to use other text to at least classify the ideas and information. In doing so, we could highlight if a summary includes voices from a certain group and not others, or that the ideas all share a certain political perspective.</p>


<p>That said, such approach may still be imperfect. Even when subgroups of interest are reasonably clearly defined, such as by gender or ethnicity, it may not be possible to accurately make those determinations based on just the text provided. Not everyone from one community writes in a particular way, and the relevant communities may vary significantly between settings. Clustering-type approaches that can help identify the missing in ideation may also be useful. Ultimately, there may need to be checks by diverse teams and different stakeholders to ensure that certain voices are not being systematically left out.</p>



<h3>Conclusion</h3>

<p>The need for task-time human evaluation (and possible corrective feedback or tuning in the moment) has always existed with AI systems. However, with prior AI systems significant evaluation could be done in advance. At present, large-surface AI systems, including versatile LLMs, are increasingly being applied to tasks in which user context is a dominant factor. In the case of both summarisation and ideation, the tasks are not completely specified (e.g., what exactly is the summary or set of ideas for?) nor can the user’s particular context, preferences, and values ever be fully transparent to the system. For very specific use cases, such as using LLMs to produce summaries of highly procedural court proceedings, the output could become trustworthy given enough testing and design iteration. However, for the many general situations in which LLMs are being used—even case reports, public comments and meeting minutes change across time and context—it is highly unlikely that we will be able to certify an LLM as being a “good” summariser or idea generator ahead of actual use. Therefore, we must presume that the system will be imperfect and provide the user with the tools to vet the quality of LLM output at task-time.15 As LLM technologies mature, more categories of use cases will appear. These use cases may have different qualities but will share this quality of needing tools to help the user evaluate the output in the context of their specific task.</p>

<p>Accurate references—that is, making sure that the LLM is not hallucinating information—will remain important, but attention must also be given to what the LLM output leaves out. Through a better understanding of what the LLM output is missing, a user will be able to leverage the imperfect system to get farther still towards what they want as a final outcome than they could have on their own.</p>





<div class="author">
<h6>ABOUT THE AUTHORS</h6>	
	<p><b>Finale Doshi-Velez</b> is Herchel Smith Professor in Computer Science at the Harvard Paulson School of Engineering and Applied Sciences. Her work focuses on interpretability, probabilistic modelling, and decision-making for effective human+AI teaming in health applications and beyond..</p>
	
	
<p><b>Elena L. Glassman</b> is an Assistant Professor in Computer Science at the Harvard Paulson School of Engineering and Applied Sciences. Her work focuses on creating tools that augment human sensemaking and human- computer collaboration, including for outputs of large language models.</p>	
	
	
</div>



<div class="notestop" id="notestop">
<h6>NOTES</h6>

<ol>
    <li>For example, Singapore’s Pairsearch; see: 
        <a href="https://hack.gov.sg/hack-for-public-good-2024/2024-projects/pairsearch/">https://hack.gov.sg/hack-for-public-good-2024/2024-projects/pairsearch/</a>
    </li>
    <li>For example, CommunityPulse; see: Mahmood Jasim, Enamul Hoque, Ali Sarvghad, and Narges Mahyar. 2021. Community-Pulse: Facilitating Community Input Analysis by Surfacing Hidden Insights, Reflections, and Priorities. In Proceedings of the 2021 ACM Designing Interactive Systems Conference (Virtual Event, USA) (DIS ’21). Association for Computing Machinery, New York, NY, USA, 846–863. 
        <a href="https://doi.org/10.1145/3461778.3462132">https://doi.org/10.1145/3461778.3462132</a>
    </li>
    <li>For example, PaTAT; see: Simret Araya Gebreegziabher, Zheng Zhang, Xiaohang Tang, Yihao Meng, Elena L. Glassman, and Toby Jia-Jun Li. 2023. PaTAT: Human-AI Collaborative Qualitative Coding with Explainable Interactive Rule Synthesis. In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (CHI ’23). Association for Computing Machinery, New York, NY, USA, Article 362, 19 pages. 
        <a href="https://doi.org/10.1145/3544548.3581352">https://doi.org/10.1145/3544548.3581352</a>
    </li>
    <li>Also for example, Cody; see: Tim Rietz and Alexander Maedche. 2021. Cody: An AI-Based System to Semi-Automate Coding for Qualitative Research. In Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems (CHI ’21). Association for Computing Machinery, New York, NY, USA, Article 394, 14 pages. 
        <a href="https://doi.org/10.1145/3411764.3445591">https://doi.org/10.1145/3411764.3445591</a>
    </li>
    <li>For example, CaseText’s CoCounsel.</li>
    <li>For example, MeetScript; see: Xinyue Chen, Shuo Li, Shipeng Liu, Robin Fowler, and Xu Wang. 2023. MeetScript: Designing Transcript-Based Interactions to Support Active Participation in Group Video Meetings. Proc. ACM Hum Comput Interact 7, CSCW2, Article 347 (Oct 2023), 32 pages. 
        <a href="https://doi.org/10.1145/3610196">https://doi.org/10.1145/3610196</a>
    </li>
    <li>Katy Ilonka Gero, Chelse Swoopes, Ziwei Gu, Jonathan K Kummerfeld, and Elena L Glassman. 2024. Supporting Sensemaking of Large Language Model Outputs at Scale. ACM CHI (2024).</li>
    <li>Glassman. 2023. Designing Interfaces for Human-Computer Communication: An On-Going Collection of Considerations. arXiv preprint arXiv:2309.02257 (2023).</li>
    <li>Ibid.</li>
    <li>Ziwei Gu, Ian Arawjo, Kenneth Li, Jonathan K. Kummerfeld, and Elena L. Glassman. 2024. An AI-Resilient Text Rendering Technique for Reading and Skimming Documents.</li>
    <li>Perhaps but not necessarily captured for the training of a personalised version of the system.</li>
    <li>Assuming that when summarising, the LLM can provide accurate references to where its output came from, that is, it is not hallucinating information. Many methods are being developed to trace the sources of LLM outputs.</li>
    <li>See note 9.</li>
    <li>Elena L Glassman and Jonathan K Kummerfeld. 2024. AI-Resilient Interfaces [Working Draft]. (2024).</li>
    <li>Ference Marton. 2014. Necessary conditions of learning. Routledge.</li>
    <li>See note 13.</li>
</ol>

	
	
	
</div>


<br><br>
<div class="back">
<a href="/ethos/">Back to Ethos Page</a>
</div>