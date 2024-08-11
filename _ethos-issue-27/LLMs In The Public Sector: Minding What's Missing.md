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



<em><small>ETHOS Issue 27, July 2024</small></em>

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




















<p>Desire to participate in the AI revolution is not limited to high-income countries. Lower and middle-income countries are increasingly looking to bridge the digital divide and reap the benefits that AI promises. To date, more than 60 countries have launched their respective national AI strategies, with over 1,000 AI policy initiatives being curated by the OECD.<sup><a href="#notestop">6</a></sup></p>

<p>Policymakers are coming to grips with AI’s revolutionary possibilities—from its versatility as a general-purpose technology to its potential to disrupt existing norms and forge new ‘operational logics’ guiding our societies. The challenge is to reimagine the state by steering AI development and adoption along multiple, concurrent dimensions vital to both present and future governance contexts: </p>



<div class="containerbox">

<ol class="numbered-squares">

<li>In the <b>socio-economic landscape</b>, AI will drive productivity and faster critical innovations in the fields of education, healthcare and public services. At the same time, there are concerns that such change will come at the cost of increased job insecurity for some, as well as a growing digital divide</li>

  

<li>AI's <b>socio-political impact</b> will be felt most keenly through its ability to transform decision-making processes across all levels of society. Here are two areas of critical concern: the integrity and security of our information systems and the biases inherent in AI-driven decisions.</li>

  

<li>Approaches to <b>governance and regulation</b> will need to be multidisciplinary, to balance the vast potential of AI for public good with its inherent risks.</li>

</ol>

</div>











<div class="break">
<p class="break1">Governments must act swiftly to harness the potential of AI as a social-levelling tool to narrow the digital divide.</p>

</div>	



<p>Alongside the use of AI to enable socio-economic development, there is also a growing interest in using AI to tackle <b>societal, developmental, and environmental challenges.</b> The innovative use of AI promises to help advance Sustainable Development Goals:<sup><a href="#notestop">17</a></sup> from using cognitive digital technologies to improve diagnostic capabilities in health, to improving financial inclusion for women, to enhancing disaster response with more accurate forecasting and real-time date analysis, among many other applications.</p>
	
<p>The adoption of <b>AI in the public sector</b> to improve service delivery for citizens, deliver greater public value and promote societal inclusion is high on the agenda of some governments. For example: </p>


<ul>
	
<li>Singapore’s National AI Strategy 2.0 (2023) aims to improve public service productivity with new value propositions for citizens_</li>	

	
<li>Canada’s AI Strategy (2017) ambition is to advance equity, diversity and inclusion in the Canadian AI ecosystem and globally, and to ensure that AI is developed and deployed to the benefit of all citizens of the world</li>	
	

<li>South Korea’s AI Strategy (2019) seeks to improve happiness of people and quality of life, and to respond proactively to social changes including job markets</li>	
	
<li>The United Kingdom’s National AI Strategy (2021) wants to ensure that AI benefits all sectors and regions, and to establish the public sector as an exemplar for AI procurement and ethics, in order to deliver greater public value for money
	
</li></ul>	

<p>Nevertheless, AI use has yet to become mainstream in many governments. A good  first step would be to equip civil servants with the right tools and environment for responsible experimentation, to help build institutional knowledge and practical understanding to better inform AI governance. Consider the example of ChatGPT: in its early days, countries like Italy banned it outright; schools in several countries prohibited its use. But the city of Boston chose to embrace it instead. They issued guidelines encouraging staff to experiment with generative AI to understand its potential, emphasising privacy, security, and public purpose. By shifting the focus from just governing the technology to using the technology for governance, Boston eventually reduced the initial alarmism and highlighted AI’s potential for social good. <sup><a href="#notestop">18</a></sup></p>


<h3>AI's Socio-Political Dimension</h3>

<p>AI is reshaping decision-making processes across different verticals in society and is thus increasingly becoming a focal point for political and security considerations. Two main concerns arise from this: the first is to do with <b>integrity of the information ecosystem,</b> and the second involves <b>biases that accompany AI-enabled decision-making.</b></p>


<p>With the capacity to reveal hidden variables and suggest potential correlations or causal relationships, AIdriven analytics can aid fraud detection, optimise resource allocation, and support more informed decision-making across different government functions. To support this, the Canadian government, for instance, has implemented a ‘Directive on Automated Decision-MakingSystems’ <sup><a href="#notestop">19</a></sup> and created a ‘Pre-qualified AI Vendor Procurement Program’ <sup><a href="#notestop">20</a></sup>to improve the accountability of AI tools utilised by government agencies.</p>


<p>However, the same AI capabilities that streamline information processing could be misused to corrupt the decision-making process, particularly by manipulating public opinion or spreading disinformation. While disinformation is not a new phenomenon, the application of AI has greatly increased the scale and speed of its spread, surpassing the pace at which policymakers can effectively cope. AI-generated fake news and deepfakes are becoming increasingly sophisticated, complicating the ability of individuals to differentiate between authentic and disingenuous content. The rapid creation and dissemination of AI generated
disinformation exploits preexisting societal fault-lines, each of which presents bad actors with an opportunity to accentuate differences and minimise similarities, thereby deepening divisions and eroding trust.<sup><a href="#notestop">21</a></sup>
	
</p><p>While AI can indeed enhance decisionmaking, such capabilities also carry significant risk of biases that stem from skewed data sets and algorithms. Consider the example of COMPAS, an AI tool used to make decisions in the American criminal justice system which has been shown to exhibit racial biases, leading claims that its victims _have been ‘set up for a lifetime of biased assessment’.<sup><a href="#notestop">22</a></sup> Biased AI might not be immediately apparent, but its impacts are profound: it can skew the perceived problem and solutions, leading to outcomes that are suboptimal. For policymakers, biases within AI could mean wrongly perceiving the needs and concerns of the populace, leading to policies that miss their mark—thereby eroding trust in public institutions or policy processes.</p>



<div class="break">
<p class="break1">Biases within AI could mean wrongly perceiving the needs and concerns of the populace, leading to policies that miss their mark.</p>

</div>	


<p>Faced with these challenges, policymakers must not only respond to present challenges but also anticipate the future implications of integrating AI more deeply within the sociopolitical sphere. National AI strategies should be conceptualised as dynamic frameworks that evolve with the operational milieu rather than remain static in the context in which they were originally formulated. As information ecosystems evolve, so too must the strategies and policy frameworks that support them</p>


<div class="break">
<p class="break1">
National AI strategies should be conceptualised as dynamic frameworks that evolve with the operational milieu rather than remain static.</p>
</div>	


<h3> AI Governance and Regulation </h3>

<p> As governments race to harness AI’s power, they must also establish clear guidelines to manage the dual-use nature of AI—both its vast potential for public good and its capacity to amplify negative outcomes—to ensure that its capabilities are directed towards societal benefit. Good AI governance should not be perceived as a handbrake on the path to progress. Instead, it is the opposite: a steering wheel that enables us to drive digital transformation at speed and scale, while supporting the development of appropriate guardrails.</p>

<p>Developing such oversight mechanisms can be tricky. Policymakers are not wrong to see the need to balance innovation with regulation, but it is not a question of what but how. Approaches to AI oversight commonly reference the need for ‘adaptable frameworks that keep pace with the rapid pace of AI development’ (e.g. the UK <sup><a href="#notestop">23</a></sup> and Singapore <sup><a href="#notestop">24</a></sup>), or to embed AI models with certain 'values' or ethical considerations (e.g. the United States<sup><a href="#notestop">25</a></sup> and the Netherlands<sup><a href="#notestop">26</a></sup>), or to ensure that AI-based decision-making is 'transparent' and auditable (e.g. Spain <sup><a href="#notestop">27</a></sup> and Canada<sup><a href="#notestop">28</a></sup>)</p>

<p>As any experienced policymaker can attest, the distinction between acting as a gatekeeper and serving as a facilitator is often a subtle yet profoundly significant one. Broader regulations can encompass a wide range of issues but may lack necessary precision, while narrower regulations can address specific problems more effectively but risk being outdated quickly or missing broader implications. Most AI regulation at present tends to be sector-specific and often voluntary in nature—leading to questions about their actual efficacy.</p>


<p>The current impulse of AI governance and regulation involves commitment_
to high-level ‘motherhood’ principles: virtually nobody will disagree with the need to ensure that AI is ‘fair’, or that it must respect ‘human privacy and dignity’. While such principles may easily fetch consensus, efforts to embed them into AI development beg the question: whose values? Most people will agree on the sanctity of human life (a high-level principle), yet such consensus does not resolve implementation-level dilemmas such as: ‘Should a self-driving car kill the baby or the grandma’?<sup><a href="#notestop">29</a></sup> Modern societies, even culturally homogenous ones, are rarely of a singular mind.</p>

<p>Although the challenges posed by AI are complex, they are not insurmountable,_
and certainly do not leave policymakers short of practical solutions. For instance, although it does not constitute an AI strategy itself, the European Union's General Data Protection Regulation(GDPR) sets a precedent for data privacy and protection and offers a foundation for ensuring that AI systems operate transparently and ethically.</p>


<div class="break">
<p class="break1">The distinction between acting as a gatekeeper and serving as a facilitator is often a subtle yet profoundly significant one.</p>
</div>	



<p>At its core, the AI governance and regulation challenge is a multidisciplinary one, and any proposed approach should reflect this. A robust starting point for AI governance and regulation harnesses the collective expertise of government, academia, and industry— what is sometimes called a 'triple-helix partnership'.<sup><a href="#notestop">30</a></sup> Policymakers provide regulatory insights, scholars from both the natural and social sciences offer technical knowledge and societal perspectives, and industry leaders contribute innovation and practical experience. To be clear, this collaborative synergy is not a panacea for the challenges associated with AI governance and regulation. It does, however, help to ensures that policies are more comprehensive, balanced, and equipped to address the multifaceted impacts of AI across all sectors of society.</p>



<div class="break">
<p class="break1"> The AI governance and regulation challenge is a multidisciplinary one, and any proposed approach should reflect this.</p>
</div>	


<p>We must acknowledge that human decision-making also has its own set of limitations. Cognitive bias, opacity, and inconsistency plague decision-making at the individual level, while challenges such as groupthink exist at the group level. In many cases, the yardstick for evaluating an AI system should move beyond a ‘good vs. bad’ dichotomy, to consider whether it improves existing decision-making processes along relevant dimensions such as efficiency, transparency, and fairness. The integration of AI should be viewed as an opportunity to enhance and refine decision-making, where technology is leveraged to fill the gaps left by human limitation, while still maintaining ethical and equitable standards aligned with the values of those impacted by AI.</p>

<h3>Pathways Toward a Global Consensus</h3>

<p>AI’s effects are not limited to national borders. AI services deployed by multinational companies are already global in reach. International collaboration will inform a large part of national AI strategy setting. Countries can benefit massively from the exchange of information and sharing best practices with each other, which will in turn enable them to better align with international norms and standards. This could increase the interoperability of national AI ecosystems, affording governments better risk management options.</p>


<p>However, the current landscape is fragmented, and global AI governance is often clustered with its thematic cousin—global digital governance—despite being distinct from it.<sup><a href="#notestop">31</a></sup> To date, there are more than 10 global AI governance initiatives and over 25 sets of AI principles in circulation worldwide. The proliferation of AI governance principles could make it more challenging for resource-poor countries to meaningfully participate in AI development and adoption, deepening the global digital divide.<sup><a href="#notestop">32</a></sup></p>


<p>To be clear, it is highly unlikely that a unified global model of AI governance will be achieved anytime soon. That said, it may be possible to achieve some degree of harmonisation for global AI governance—a new form of ‘integrated internet internationalism’.<sup><a href="#notestop">33</a></sup> A multipartite partnership approach could foster greater coherence in AI policies among countries worldwide and also amplify the collective global capacity to manage AI’s far-reaching implications.<sup><a href="#notestop">34</a></sup> The private sector could leverage their technical expertise to help governments worldwide collectively navigate and address the ethical, operational, and strategic challenges posed by AI, strengthening global AI governance efforts.<sup><a href="#notestop">35</a></sup>

	</p><div class="break">
<p class="break1">The yardstick for evaluating an AI system should move beyond a ‘good vs. bad’ dichotomy, to consider whether it improves existing decision-making processes.</p>
</div>
	
<p></p><h3>Conclusion</h3>

<p>AI is a multi-faceted domain, yet this need not deter policymakers. Effective interventions in each of the three dimensions—socio-economic impact, socio-political considerations, and governance and regulation—can help ensure AI delivers on its promise of innovation and societal benefit. The challenge now lies in transforming the strategic ingredients into a cohesive and successful AI ecosystem—proving the value of AI by realising its implementation in thoughtful and inclusive ways.</p>


<div class="author">
<h6>ABOUT THE AUTHORS</h6>	
<p><b>Kenddrick Chan</b> is Senior Policy Analyst at the Tony Blair Institute for Global Change, where he conducts policy-relevant research on the intersection of technology, geopolitics, and international development. He is also a member of the United Nations ESCAP Informal Working Group on sustainable digital transformation in the Asia-Pacific region and was previously a G20 delegate at the Think20 for India's G20 presidency.</p>
	
	
<p><b>PeiChin Tay</b> specialises in the fields of future of work, AI and public sector transformation at the Tony Blair Institute for Global Change. Prior to this, PeiChin led and delivered multi-million-dollar national and regional programmes, such as the flagship London Mayor's Digital Talent programme, a pan-European consortium on design innovation at Design Council UK, and an entrepreneurship project in the Government of Singapore. She contributes regularly to high-level working groups (UN), conferences and events (OECD, World Bank, Asia Tech X, IGF).</p>	
	
	
</div>



<div class="notestop" id="notestop">
<h6>NOTES</h6>

<ol>
<li><a href="https://www.cnbc.com/2017/07/21/china-ai-world-leader-by-2030.html#:~:text=China%20laid%20out%20plans%20to,the%20military%20to%20smart%20cities.">https://www.cnbc.com/2017/07/21/china-ai-world-leader-by-2030.html#:~:text=China%20laid%20out%20plans%20to,the%20military%20to%20smart%20cities.</a></li>
    <li><a href="https://ai.gov.ae/wp-content/uploads/2021/07/UAE-National-Strategy-for-Artificial-Intelligence-2031.pdf">https://ai.gov.ae/wp-content/uploads/2021/07/UAE-National-Strategy-for-Artificial-Intelligence-2031.pdf</a></li>
    <li><a href="https://mission-ki.de/en/">https://mission-ki.de/en/</a></li>
    <li><a href="https://www.nordicinnovation.org/news/new-expert-group-will-make-nordics-leading-region-ethical-ai">https://www.nordicinnovation.org/news/new-expert-group-will-make-nordics-leading-region-ethical-ai</a></li>
    <li><a href="https://www.imf.org/en/Blogs/Articles/2024/01/14/ai-will-transform-the-global-economy-letsmake-sure-it-benefits-humanity">https://www.imf.org/en/Blogs/Articles/2024/01/14/ai-will-transform-the-global-economy-letsmake-sure-it-benefits-humanity</a></li>
    <li><a href="https://oecd.ai/en/dashboards/overview">https://oecd.ai/en/dashboards/overview</a></li>
    <li><a href="https://goingdigital.oecd.org/data/notes/No14_ToolkitNote_AIStrategies.pdf">https://goingdigital.oecd.org/data/notes/No14_ToolkitNote_AIStrategies.pdf</a></li>
    <li><a href="https://www.institute.global/insights/tech-and-digitalisation/from-strategy-to-synergy-what-can-we-learn-from-singapores-ai-journey#footnote_list_item_9">https://www.institute.global/insights/tech-and-digitalisation/from-strategy-to-synergy-what-can-we-learn-from-singapores-ai-journey#footnote_list_item_9</a></li>
    <li><a href="https://www.institute.global/insights/economic-prosperity/accelerating-the-future-industrialstrategy-in-the-era-of-ai">https://www.institute.global/insights/economic-prosperity/accelerating-the-future-industrialstrategy-in-the-era-of-ai</a></li>
    <li><a href="https://www.imf.org/en/Publications/fandd/issues/2023/12/Macroeconomics-of-artificialintelligence-Brynjolfsson-Unger">https://www.imf.org/en/Publications/fandd/issues/2023/12/Macroeconomics-of-artificialintelligence-Brynjolfsson-Unger</a></li>
<li><a href="https://www.nber.org/papers/w31161">https://www.nber.org/papers/w31161</a></li>
<li>Pair Chatbot is an experimental AI bot that will allow the secure and efficient use of large language models as a writing assistant within the government space.</li>
   <li>Transcribe is a secured Speech-to-Text (STT) platform with auto-transcription technologies that can be used to produce transcripts of interviews, speeches and meeting minutes, and was developed for the Singapore government.</li>
    <li><a href="https://www.ft.com/content/8f7b9b52-9243-4c34-af80-223522273ab4">https://www.ft.com/content/8f7b9b52-9243-4c34-af80-223522273ab4</a></li>
    <li><a href="https://www.khanmigo.ai/">https://www.khanmigo.ai/</a></li>
    <li><a href="https://www.weforum.org/agenda/2023/05/ai-skills-gaps-future-jobs/">https://www.weforum.org/agenda/2023/05/ai-skills-gaps-future-jobs/</a></li>
    <li><a href="https://repository.unescap.org/bitstream/handle/20.500.12870/6810/ESCAP-2024-FS-Seizing-Opportunity.pdf?sequence=3&amp;isAllowed=y">https://repository.unescap.org/bitstream/handle/20.500.12870/6810/ESCAP-2024-FS-Seizing-Opportunity.pdf?sequence=3&amp;isAllowed=y</a></li>
    <li><a href="https://www.wired.com/story/boston-generative-ai-policy/">https://www.wired.com/story/boston-generative-ai-policy/</a></li>
    <li><a href="https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=32592">https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=32592</a></li>
    <li><a href="https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/responsible-use-ai/list-interested-artificial-intelligence-ai-suppliers.html">https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/responsible-use-ai/list-interested-artificial-intelligence-ai-suppliers.html</a></li>
    <li>Several countries have implemented counter-disinformation initiatives to combat the spread of online disinformation in areas of public interest, such as the UK government’s National Security Online Information Team (NSOIT) unit.</li>
    <li><a href="https://www.technologyreview.com/2020/07/17/1005396/predictive-policing-algorithms-racist-dismantled-machine-learning-bias-criminal-justice/">https://www.technologyreview.com/2020/07/17/1005396/predictive-policing-algorithms-racist-dismantled-machine-learning-bias-criminal-justice/</a></li>
    <li><a href="https://www.gov.uk/government/consultations/ai-regulation-a-pro-innovation-approach-policy-proposals/outcome/a-pro-innovation-approach-to-ai-regulation-government-response">https://www.gov.uk/government/consultations/ai-regulation-a-pro-innovation-approach-policy-proposals/outcome/a-pro-innovation-approach-to-ai-regulation-government-response</a></li>
    <li><a href="https://file.go.gov.sg/nais2023.pdf">https://file.go.gov.sg/nais2023.pdf</a></li>
    <li><a href="https://asiatimes.com/2023/11/us-stresses-ethical-ai-use-in-its-latest-strategy">https://asiatimes.com/2023/11/us-stresses-ethical-ai-use-in-its-latest-strategy</a></li>
    <li><a href="https://data-en-maatschappij.ai/en/policy-monitor/nederland-impact-assessment-mensenrechtenen-algoritmes">https://data-en-maatschappij.ai/en/policy-monitor/nederland-impact-assessment-mensenrechtenen-algoritmes</a></li>
    <li><a href="https://www.dataguidance.com/opinion/spain-agency-supervision-ai-overview">https://www.dataguidance.com/opinion/spain-agency-supervision-ai-overview</a></li>
    <li><a href="https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=32592">https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=32592</a></li>
    <li><a href="https://www.technologyreview.com/2018/10/24/139313/a-global-ethics-study-aims-to-help-ai-solve-the-self-driving-trolley-problem/">https://www.technologyreview.com/2018/10/24/139313/a-global-ethics-study-aims-to-help-ai-solve-the-self-driving-trolley-problem/</a></li>
    <li>For instance, Singapore has adopted a model, with the Government as ecosystem enabler, that convenes the research community, industry and public agencies to facilitate research collaborations, quickly commercialise fundamental AI research, and rapidly deploy AI solutions.</li>
    <li><a href="https://eprints.lse.ac.uk/119637/1/Chan_multilateralism_in_the_digital_age_published.pdf">https://eprints.lse.ac.uk/119637/1/Chan_multilateralism_in_the_digital_age_published.pdf</a></li>
    <li><a href="https://www.institute.global/insights/tech-and-digitalisation/state-of-compute-access-how-to-bridge-the-new-digital-divide">https://www.institute.global/insights/tech-and-digitalisation/state-of-compute-access-how-to-bridge-the-new-digital-divide</a></li>
    <li><a href="https://www.orfonline.org/wp-content/uploads/2023/08/TF7_InternetInternationalism.pdf">https://www.orfonline.org/wp-content/uploads/2023/08/TF7_InternetInternationalism.pdf</a></li>
    <li><a href="https://www.smehorizon.com/singapore-sets-her-sights-on-being-a-global-hub-for-ai-solutions/">https://www.smehorizon.com/singapore-sets-her-sights-on-being-a-global-hub-for-ai-solutions/</a></li>
    <li><a href="https://eprints.lse.ac.uk/121603/1/Alden_et_al_Global_Digital_Governance_policy_brief.pdf">https://eprints.lse.ac.uk/121603/1/Alden_et_al_Global_Digital_Governance_policy_brief.pdf</a></li>
</ol>

	
	
	
</div>