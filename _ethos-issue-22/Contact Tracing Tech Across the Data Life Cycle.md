---
title: Contact Tracing Tech Across the Data Life Cycle
permalink: /ethos-issue-22/contact-tracing-tech-across-the-data-life-cycle/
description: ""
---
<style>

.back a
{
	color: #9f2943;
	font-weight: bold;
}

#banner img
{
	width:100%;
}
	
.author
{
border-bottom: 1px solid black;
margin-top:40px;
padding-bottom:30px;
border-top: 1px solid black;	

}

.author p {
	font-size: 0.9em;
	line-height:24px !important;
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

.boxheader {
	color: white !important;
	}	

.containerbox {
	background-color: #B7C9E2;
	border-radius: 10px;
	padding: 5%;
	margin-top: 5%;
	
	}	

li {
	font-size: 15px !important;
	
	}	

</style>

<em><small>ETHOS Issue 22, June 2021</small></em>
<img src="/images/Cropped_images/Ethos_Issue_22/print22-07.jpg">


<p>To stem the spread of the COVID-19 pandemic, governments around the world have created digital tools to quickly identify actual and potential COVID-19 infections. Together with traditional methods of contact tracing (i.e., interviewing patients to identify their close contacts), these digital tools aim to speed up tracing,<sup><a href="#notes">1</a></sup> reducing the time taken from days to a matter of minutes.<sup><a href="#notes">2</a></sup> This shortens the interval between an individual’s possible exposure to the virus and entry into quarantine, which is especially useful since asymptomatic and pre-symptomatic carriers are known to be significant spreaders of the virus. Such tools also help tracers work backwards to identify clusters, curbing the spread of an illness in which patients are most infectious in the first week of illness.<sup><a href="#notes">3</a></sup></p>

<p>However, these digital tools have also sparked privacy and other concerns. Scholars at the Oxford Internet Institute<sup><a href="#notes">4</a></sup> have highlighted two aspects of the ethics and governance questions involved. First, there are the high-level principles: are the apps necessary, proportional, scientifically sound, and temporary? Second, there are the enabling factors: such as whether use of the apps is voluntary, whether people can consent to their data being used, and the extent to which the purpose of the apps are defined.</p>

<p>Countries have struck different balances between public health utility and civil liberties in the use of digital contact tracing tools. In some countries, participation is practically compulsory and data is centralised. In China, for example, many cities use Alipay Health Code to determine whether people may enter buildings or use public transit. A <em>New York Times</em> analysis of the app’s code found that it shares data with the police by sending each user’s location and identifying code numbers to a server.<sup><a href="#notes">5</a></sup> In Singapore, the use of SafeEntry, which people use to log their presence, is compulsory at a wide range of venues: offices, shops, worksites, schools, healthcare facilities, places of worship, hotels, recreation and entertainment venues, restaurants, and cultural institutions among others.<sup><a href="#notes">6</a></sup> Data is stored and encrypted in a server for 25 days.</p>

<p>Other countries use apps that maximise choice and emphasise privacy protections. Canada and several European Union (EU) countries have launched apps that citizens are not required to use. As of March 2021, Canada’s COVID Alert had been downloaded by just 6 million people, roughly 16% of the population.<sup><a href="#notes">7</a></sup> As of January 2021, Germany’s Corona-Warn-App had been downloaded by just 24 million people, roughly 29% of the population.<sup><a href="#notes">8</a></sup></p>

<p>Governments have a duty to protect both the safety and the rights of their citizens; they must do both in a way that maintains trust. Policymakers and citizens can better think about what trade-offs to make and what guard rails against abuse to erect by considering the data life cycle of contact tracing technology.</p>

<h3>Decisions Across the Data Life Cycle</h3>

<p>Data lies at the core of any digital system. A digital system uses hardware and software to turn data into a solution. Take for example what happens when we have virtual meetings. Software (e.g., applications like Zoom/Skype, or operating systems such as Windows 10 or iOS) and hardware (e.g., a computer, cables, routers, Wi-Fi signals) combine to take sound and light on one end and turn them into bits of data that emerge on the other end as audio and video. All the companies involved in this process could be collecting various sorts of data, such as data about the quality of the connection, the time and duration of the meeting, and the performance of devices.</p>

<hr>



<p style="text-align: center;"><a target="_blank" href="../../images/default-source/ethos-images/ethos-issue-22/data_life_cycle.jpg"><img width="750" src="../../images/default-source/ethos-images/ethos-issue-22/data-life-cycle-small.jpg" height="171" alt="data life cycle small"></a></p>

<p class="small-text text">Professor Jeanette Wing’s model of the data life cycle encompasses all but the last phase (archival/destruction), as part of her argument that privacy and ethical concerns ought to be considered throughout the life cycle of data. Click to see the larger image</p>


<p>As Jeanette Wing—Professor of Computer Science and Director of Columbia University’s Data Science Institute—describes in an influential 2019 essay, data in a digital system goes through a life cycle with various phases.<sup><a href="#notes">9</a></sup> When it comes to COVID-19 technology, policyowners need to make important decisions for each of these key phases, throughout the life cycle of the data in question.</p>

<h3>Collection</h3>

<p>Our smartphones contain sensors and devices that generate data about us in order to function. Accelerometers detect motion and can be used to measure our steps taken. GPS specifies our location. Bluetooth enables our phones to “talk” to other devices, thereby registering the device’s presence.</p>

<p>Not all data generated needs to be collected. Policyowners must determine what data generated is <em>meaningful</em> to collect. That is, does the data have quality, and is it a good proxy for the social condition being analysed? Also, <em>how</em> might they get the data they want to collect? Should they settle for less meaningful data if it is more readily collected?</p>

<p>Some COVID-19 contact tracing technologies collect location data (<em>where</em> you were); others collect proximity data (<em>whom</em> you were with). For the former, data can be collected in different ways. For example, some apps in China use data about user GPS locations, acquired from telcos, to determine an individual’s travel history and possible exposure in high-risk areas. In this case, data is acquired automatically, with little participation from users. Singapore’s SafeEntry app also logs location, but by having users scan a QR code when they visit various venues. The advantage to both approaches is their use of familiar technologies. QR code scanning has the added privacy advantage of <em>not</em> continuously logging users’ locations wherever they might be, including at home.</p>

<hr>

<h5><em>Not all data generated needs to be collected. Policy owners must determine what data generated is meaningful to collect.</em></h5>

<hr>

<p>There are, however, downsides to using these familiar technologies of location-based tracing. QR code-based systems expose users to security threats.<sup><a href="#notes">10</a></sup> Additionally, where droplet-based transmission dominates, location-based tracking is less useful than proximity-based tracking, since our vulnerability to infection by people with COVID-19 is shaped more by how near we were to them, and for how long, than whether we were at the same venue as them.</p>

<p>Besides the <em>type</em> of data to collect, policyowners must also decide <em>how</em> much data to collect to make contact tracing effective. How much does the government need to know about a person who might have been exposed to the virus?</p>

<p>Apps built on Apple and Google’s Exposure Notifications System (ENS)<sup><a href="#notes">11</a></sup> only transmit and store random and regularly changing identification numbers that are linked to users’ devices rather than their identities. This approach has won plaudits from privacy advocates,<sup><a href="#notes">12</a></sup> but creates a different challenge, because devices could be used by different people. How do we know that the person using the device when it registers proximity with an infected person is the same person who is called up for possible exposure? In contrast, India’s Aarogya Setyu, which has raised privacy concerns, collects a person’s name, phone number, gender, travel history, and smoking habits (if any), on top of both location and proximity data.</p>

<p>In deciding how much information is needed to identify individuals, authorities need to consider two issues: what information is useful for public health efforts, and potential risks to privacy and data security.</p>

<h3>Storage</h3>

<p>Data collected is data that must be stored somewhere. In the case of potentially sensitive personal information, this stored data must also be secured. Here, policyowners need to weigh threat assessment (who would want to compromise the data collected, for what purpose, and how?) against public health utility.</p>

<p>Unlike solutions that collect location data, both BlueTrace<sup><a href="#notes">13</a></sup> (derived from Singapore’s TraceTogether) and the Apple-Google ENS use Bluetooth to collect proximity or associational data. Both transmit and receive random “nicknames” associated with users’ devices. Both enhance privacy and data security by only storing nicknames on these devices. If the encryption keys that linked these nicknames to devices or identities were ever compromised, a hacker would still have to break into individual phones to access the proximity data stored within.</p>

<p>This means that both systems have a security advantage over systems that store data on a server. Storing data on a server creates a single point of failure—the server could be compromised by a hack, an accidental leak, or sabotage by a rogue insider. If the data is stored in plain text (i.e., readable by a human being), and if large amounts of data have been collected so that one leak exposes a great deal of information about individuals, then the leak becomes more severe. In China, COVID-19-related data, including names, identification numbers, phone numbers, and addresses, have been leaked:<sup><a href="#notes">14</a></sup> as a result, people who may have been exposed to the virus have been harassed. The leak of data that is difficult to change—e.g., a national identification number or biometric data—would be particularly egregious, since that could compromise people across multiple systems in ways that are challenging to quickly correct.</p>

<p>BlueTrace and the Apple-Google ENS differ in whether they allow information gathered to be uploaded to a server where it can be decrypted to identify individuals: BlueTrace does; the Apple-Google ENS does not. BlueTrace allows data centralisation because it enables health authorities to quickly identify and isolate potential carriers of the SARSCoV-2 virus. As a safeguard, BlueTrace only stores and uploads information on exposure gathered over a certain period. As such, BlueTrace’s compromise on data centralisation arguably makes it a better option for most health systems. Notably, centralising information and contact tracing by health authorities are already standard practices with many other infectious diseases (e.g., sexually transmitted infections,<sup><a href="#notes">15</a></sup> tuberculosis,<sup><a href="#notes">16</a></sup> Ebola<sup><a href="#notes">17</a></sup>).</p>

<p>Apple and Google have refused to allow centralisation due to privacy concerns. As global companies, their tough stance on privacy is understandable, since they would not want their technology to be used in countries where government possession of individuals’ data could enable serious incursions against civil liberties. Governments have clashed with the tech giants by asking that the ENS allow them to collect more data and centralise information for COVID-19 infections.<sup><a href="#notes">18</a></sup> These governments question why the tech giants’ commercial policies should prevent them from better integrating technology with public health operations to combat an unprecedented health crisis.<sup><a href="#notes">19</a></sup></p>

<p>Nevertheless, many governments have launched apps based on the Apple-Google protocol, leveraging their ready-to-use digital contact tracing technology to help ameliorate rising outbreaks. The efficacy of such apps does depend on governments’ success in persuading citizens to update their status in the apps if they happen to test positive for COVID-19.</p>

<h3>Management and Analysis</h3>

<p>Wing writes that data needs to be managed in ways that “maximise our ability to access and modify the data for subsequent analysis”.<sup><a href="#notes">20</a></sup> This raises a highly salient data governance issue, especially in cases where COVID-19 data is centralised: who gets access to the data collected, and what are they authorised to do with it? How this concern is addressed, and assurances that provisions will be adhered to, are key to building trust with citizens over the trade-offs in privacy that governments ask of them.</p>

<p>Singapore’s experience underscores the need for legislative guarantees to limit data use. The team behind Singapore’s TraceTogether initially publicly committed that data shared with the Ministry of Health would only be used for contact tracing. Politicians repeated this assurance as well. However, in January 2021, in response to a question posed by a Member of Parliament, Singapore’s Ministry of Home Affairs acknowledged that, contrary to these public assurances, the police had in fact accessed TraceTogether data for an investigation in May 2020. The TraceTogether team subsequently clarified that TraceTogether data had always been subject to the Criminal Procedure Code, which empowers the police to access any data for the purpose of criminal investigation.</p>

<p>Singaporeans reacted less to the violation of privacy and more to the fact that a public assurance had been broken, with the information about it only being released months after the fact. The undermining of trust was arguably made worse by the fact that, as Computer Science Associate Professors Terence Sim<sup><a href="#notes">21</a></sup> and Ben Leong<sup><a href="#notes">22</a></sup> argued separately, TraceTogether data would not have been that useful in criminal investigations anyway. Indeed, Minister of State for Home Affairs Desmond Tan acknowledged that investigators did not find useful data since the suspect had not downloaded the app onto his phone.<sup><a href="#notes">23</a></sup> Singaporeans began to uninstall the app or leave their TraceTogether tokens at home. In response, the Government passed legislation to limit the use of TraceTogether data to investigations for specified serious crimes.</p>

<hr>



<p class="small-text text">What are the privacy concerns in Israel, Australia and the United Kingdom?</p>




<div class="container">


<h3 class="title"> Contact Tracing and Privacy Concerns Elsewhere</h3>
<p class="text">&nbsp;</p>
<p>Israel’s contact tracing technology is managed by the state security agency, Shin Bet. The agency traces close contacts of COVID-19 patients by using the “Tool”, a database which contains the details of phone users in Israel. There is little transparency about how health information collected by the Tool is stored and protected. The use of the Tool for health purposes has been challenged in courts and requires periodic authorisation by the Israeli parliament. Israel’s Health Ministry reported that traditional contact tracing had only uncovered a third of COVID-19 cases, while the Tool had identified the rest. Israeli society seems to have accepted the temporary use of a security service for public health purposes, arguably because of its governance and effectiveness.<sup>1</sup></p>
<p>Fear that a lack of robust governance would deter people from using contact tracing apps has led authorities to commit to limiting the purpose of contact tracing data.</p>
<p>The United Kingdom’s Department of Health and Social Care assured individuals that police would not get access to data acquired by the National Health Service’s COVID-19 app.<sup>2</sup> Australia has outright criminalized the use of contact tracing data for non-health reasons. <sup>3</sup></p>
<hr>
<p style="font-weight: bold; letter-spacing: 1px;" class="small-text">NOTES</p>
<ol>
<li class="small-text">Tehilla Schwartz Altshuler and Rachel Aridor Hershkowitz, <a target="_blank" href="https://www.brookings.edu/techstream/how-israels-covid-19-mass-surveillance-operation-works/">“How Israel’s Covid-19 Mass Surveillance Operation Works”</a>, Brookings: Tech Stream, July 6, 2020, accessed March 31, 2021. </li>
<li class="small-text">Zoe Kleinman, <a target="_blank" href="https://www.bbc.com/news/technology-54599320">“Covid Contact-Tracing App Not Sharing Data with Police”</a>, <em>BBC</em>, October 19, 2020, accessed March 31, 2021.
    </li>
<li class="small-text">Byron Kaye, <a target="_blank" href="https://www.reuters.com/article/ushealth-coronavirus-australia-idUSKCN2253UA">“Australia Will Make It a Crime to Use Coronavirus Tracing Data for Non-Health Purposes”</a>, <em>Reuters</em>, April 24, 2020, accessed March 31, 2021.
    </li>
</ol>



</div>





<p>Singapore’s experience suggests that there is, realistically, a need to consider alternatives to the two extremes of either opaque and liberal use of data or strictly limiting its use. The World Economic Forum’s White Paper on Authorised Public Purpose Access (APPA)<sup><a href="#notes">24</a></sup> provides a middle way forward based on public consent. APPA would move data governance away from a model that over-emphasises individual consent (which could harm individuals) to one that balances the needs of individuals, public purpose, and data holders. Masako Okamoto and Takanori Fujita explain that “under APPA, personal data can sometimes be accessed and used without explicit individual consent, provided this is done for a specific, widely agreed-upon public purpose”.<sup><a href="#notes">25</a></sup> An APPA process would include checking a White List to determine if the data type has been approved for a specifically designated purpose. It would also include review by a third party such as an independent board. In this sense, Singapore’s legislation to limit the use of TraceTogether data to specific purposes is a step in the right direction.</p>

<p>More broadly, the use of digital contact tracing tools could be strengthened by better provisions for decision provenance (i.e., who makes what decisions, and how) for government technology. Jatinder Singh, Jennifer Cobbe and Chris Norval of Cambridge University’s Department of Computer Science and Technology<sup><a href="#notes">26</a></sup> note that complex technological systems raise accountability challenges as data flows across technical and organisational boundaries. Transparency about who makes what decisions, where in a system, and how, could facilitate compliance with requirements and regulations, offer recourse against harm, and give users agency to make more informed decisions about how their data is used. For this approach to work, engineers, data scientists and bureaucrats will have to make their work more legible to ordinary citizens. In turn, citizens must also become more competent at querying and critically analysing these decisions.</p>

<hr>



<p class="small-text text">How might authorities access data in a way that upholds trust?</p>




<div class="container">


<h3 class="title">Upholding Trust in Data Use</h3>
<p class="text">&nbsp;</p>
<p> Microsoft CEO Satya Nadella has offered suggestions for how authorities might access data in a way that upholds trust. These include:<sup>1</sup></p>
<ul>
<li>having an efficient mechanism to access data that is supported by “a clear legal framework that is subject to strong checks and balances”;</li>
<li>strengthening users’ privacy protections to prevent the erosion of these rights in the name of efficiency;</li>
<li>allowing technology companies, “except in highly limited cases”, to inform users that the authorities have sought their data;</li>
<li>having governments seek data from a source that is closest to the end user; and</li>
<li>ensuring that any attempt to access data does not undermine security, and therefore users’ trust in technology.</li>
</ul>
<hr>
<p style="font-weight: bold; letter-spacing: 1px;" class="small-text">NOTE</p>
<ol>
<li class="small-text">Satya Nadella, <em>Hit Refresh: The Quest to Rediscover Microsoft’s Soul and Imagine a Better Future for Everyone</em> (London: William Collins, 2017), 190–193. </li>
</ol>



</div>





<p>Data governance via the APPA model and which incorporates decision provenance transparency would require a society to have robust deliberations over the robustly deliberate circumstances under which specific data can be shared with and used by specific entities for specific purposes. Indeed, if countries are to treat data as a resource as much as they do finance, then it should be similarly subjected to periodic, public deliberation as to its best use. Continuous public deliberation over data would also be a way for governments to keep abreast of changing societal attitudes towards data privacy, and to consistently replenish reservoirs of trust.</p>

<hr>

<h5><em>The use of digital contact tracing tools could be strengthened by better provisions for decision provenance for government technology.</em></h5>

<hr>

<h3>Archival or Destruction</h3>

<p>Decisions at the archival or destruction stage of the data life cycle could also influence the extent to which people participate in digital contact tracing. Archival involves removing data from further use (by, for example, storing it in a device that is not connected to networks). Destruction involves permanently deleting it. Deleting data is, in fact, a key aspect of Mozilla’s Lean Data Practices. Mozilla notes that the “value of data diminishes over time”, and that sensitive data should either be deleted when it is no longer relevant, or stripped of markers that identify the person to whom the data belongs, as much as possible.<sup><a href="#notes">27</a></sup></p>

<p>The best practice in COVID-19 contact tracing systems is to delete information after some time—usually, the time it takes for the virus to incubate. The Apple-Google ENS deletes information after 14 days. TraceTogether deletes information after 25 days on account of studies which show cases of the virus having a longer incubation period than the two weeks it was previously thought to have.<sup><a href="#notes">28</a></sup> In systems that store data on servers, information could be anonymised and aggregated to diminish its value should it be leaked. This would reduce the harm caused to any individual in case the data is compromised.</p>

<h3>Operational Realities and Considerations</h3>

<p>A key ethical question with contact tracing tools is whether participation in tracing is voluntary or mandatory. A high take-up rate of apps is necessary to make digital contact tracing effective: between 56% and 95% of the population, according to a study in <em>The Lancet</em>.<sup><a href="#notes">29</a></sup> This might tempt governments to make the use of contact tracing apps mandatory.</p>

<p>Indeed, depending on voluntary participation might not work. In Canada, 95% of Canadians who tested positive for COVID-19 failed to voluntarily report their diagnosis using the country’s COVID Alert app. In Ontario, where the app first launched, only 4% of people who had COVID-19 logged their positive diagnoses in the app between 31 July 2020, when the app launched, and 28 September 2020.<sup><a href="#notes">30</a></sup></p>

<p>At the same time, people care about whether contact tracing apps could be used to perpetually monitor them. In Singapore, 45% of respondents in a study by Blackbox Research said that they did not download the TraceTogether app mainly because they “did not want the government tracing their movements”.<sup><a href="#notes">31</a></sup> When Singapore introduced a TraceTogether token, over 54,000 people signed a Change.org petition, “Singapore Says ‘No’ To Wearable Devices for Covid-19 Contact Tracing”.<sup><a href="#notes">32</a></sup> In India, citizens pushed back against an attempt by a district administration to make the use of Aarogya Setu compulsory.<sup><a href="#notes">33</a></sup></p>

<p>Dr Vivian Balakrishnan, Singapore’s Minister for Foreign Affairs and Minister-in-charge of the Smart Nation initiative, affirmed in an interview that “maintaining trust, respecting privacy and getting voluntary participation is absolutely essential” for contact tracing.<sup><a href="#notes">34</a></sup> Indeed, nurturing public trust in institutions is vital to governments’ ability to fight COVID-19. Actions that sacrifice trust for compliance with mandated use of apps could end up backfiring on overall public health efforts.</p>

<h3>Moving Forward: Strengthening Governance and Trust</h3>

<p>As COVID-19 restrictions ease, the case for using contact tracing tools to mitigate risk becomes stronger. More will need to be done to assure citizens that contact tracing technology—indeed, all sorts of civic technology—is doing things for them rather than to them. In this vein, Singapore’s Ministry of Health and Smart Nation and Digital Government Office promoted the use of TraceTogether as an effort by Singaporeans to “protect themselves, their loved ones and their community”<sup><a href="#notes">35</a></sup> from COVID-19. This was an appeal to both self-interest and altruism. In Singapore, SafeEntry has long been functionally mandatory, its use required in a wide array of venues. There have latterly been moves to make the use of TraceTogether mandatory at certain venues. This is an opportunity to strengthen public engagement on when, where, and why contact tracing is used, in order to encourage enthusiastic participation.</p>

<p>Better data governance could also foster participation. Compromises on voluntary participation should be accompanied by stronger protections for privacy trade-offs. For example, SafeEntry could adopt some of TraceTogether’s privacy safeguards, such as limiting the data’s use to explicitly stated public purposes. Governments could also strengthen public assurances by stiffening sanctions on public servants who use contact tracing data for reasons other than those that have been authorised.</p>

<p>Ultimately, people’s willingness to work with COVID-19 public health measures depends on the extent to which they trust the governance system as a whole. In this sense, citizens’ enthusiastic compliance with public health measures—including digital contact tracing—is a daily poll of the authorities’ ability to both protect their health and keep their data safe.</p>

<hr>

<h5><em>Better data governance could foster participation. Compromises on voluntary participation should be accompanied by stronger protections for privacy trade-offs.</em></h5>

<hr>

<p style="font-weight: bold; letter-spacing: 1px;" class="small-text">ABOUT THE AUTHOR</p>

<table style="border: none; background-color: transparent;">
<tbody>
<tr style="border: none;">
<td style="padding: 0; padding-right: 32px; border: none;">
<p class="small-text"><strong>Vernie Oliveiro</strong> is Principal Researcher at the Institute of
            Governance and Policy, Civil Service College. Her research interests include governance and digital government.</p>
</td>
<td style="width: 120px; border: none;" class="desktop-only"></td>
</tr>
</tbody>
</table>

<hr>

<p style="font-weight: bold; letter-spacing: 1px;" class="small-text"> <a name="notes"></a>NOTES</p>

<ol>
<li class="small-text">Sharon Begley, <a target="_blank" href="https://www.statnews.com/2020/04/02/coronavirus-spreads-too-fast-for-contact-tracing-digital-tools-could-help/">“Covid-19 Spreads Too Fast for Traditional Contact Tracing. New Digital ToolsCould Help”</a>, <em>Stat+</em>, April 2, 2020, accessed March 31, 2021.
    </li>
<li class="small-text">Cara Wong, <a target="_blank" href="https://www.straitstimes.com/singapore/digital-tools-help-speed-up-contact-tracing-efforts-to-ring-fence-cases">“Digital Tools Help Speed Up Contact Tracing Efforts to Ring-Fence Covid-19 Cases” </a>, <em>The Straits Times</em>, July 8, 2020, accessed March 31, 2021. </li>
<li class="small-text">Muge Cevik, Matthew Tate, Ollie Lloyd, Alberto Enrico Maraolo, Jenna Schafers, and Antonia Ho, <a target="_blank" href="https://www.thelancet.com/journals/lanmic/article/PIIS2666-5247(20)30172-5/fulltext"> “SARS-CoV-2, SARS-CoV, and MERS-CoV Viral Load Dynamics, Duration of Viral Shedding, and Infectiousness: A Systematic Review and Meta-Analysis”</a>, <em>The Lancet Microbe 2</em>, no. 1 (November 2020), accessed March 31, 2021. </li>
<li class="small-text">Jessica Morley, Josh Cowls, Mariarosaria Taddeo, and Luciano Floridi, <a target="_blank" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3582550">“Ethical Guidelines for SARS-Cov-2 Digital Tracking and Tracing Systems”</a>, <em>SSRN</em>, April 22, 2020, accessed March 31, 2021. </li>
<li class="small-text">Paul Mozur, Raymond Zhong, and Aaron Krolik, <a target="_blank" href="https://www.nytimes.com/2020/03/01/business/china-coronavirus-surveillance.html">“In Coronavirus Fight, China Gives Citizens a Colour Code, with Red Flags”</a>, <em>New York Times</em>, March 1, 2020, accessed March 31, 2021. </li>
<li class="small-text"> <a target="_blank" href="https://support.safeentry.gov.sg/hc/en-us/articles/900000861343--Updated-Dec-2020-Places-where-SafeEntry-must-be-deployed">SafeEntry FAQs</a>, accessed March 31, 2021. </li>
<li class="small-text">Rachel Collier, <a target="_blank" href="https://www.thestar.com/news/canada/2021/03/10/more-than-6-million-canadians-download-covid-alert-app.html">“More than 6 Million Canadians Download COVID Alert App”</a>, <em>The Star</em>, March 10, 2021, accessed March 31, 2021. </li>
<li class="small-text">Andrea Waisgluss, <a target="_blank" href="https://www.forbes.com/sites/sap/2021/01/25/with-over-24-million-downloads-germanys-covid-19-app-helps-break-the-infection-chain/?sh=5746884771cf">“With Over 24 Million Downloads, Germany’s COVID-19 App Helps Break the Infection Chain”</a>, <em>Forbes</em>, January 25, 2021, accessed March 31, 2021. </li>
<li class="small-text">Jeannette M. Wing, <a target="_blank" href="https://hdsr.mitpress.mit.edu/pub/577rq08d/release/3">“The Data Life Cycle”</a>, <em>Harvard Data Science Review</em> 1, no. 1 (Summer 2019), July 2, 2019, accessed March 31, 2021. </li>
<li class="small-text">Brian Foster, <a target="_blank" href="https://threatpost.com/qrcodes-sneaky-security-threat/159757/">“QR Codes: A Sneaky Security Threat”</a>, <em>threatpost</em>, October 1, 2020, accessed March 31, 2021. </li>
<li class="small-text">For more information, see <a target="_blank" href="https://covid19-static.cdn-apple.com/applications/covid19/current/static/contact-tracing/pdf/ExposureNotification-FAQv1.2.pdf">“Exposure Notifications: Frequently Asked Questions”</a>, September 1, 2020, accessed March 31, 2021. </li>
<li class="small-text"> <a target="_blank" href="https://www.esat.kuleuven.be/cosic/sites/contact-tracing-joint-statement/">“Contact Tracing Joint Statement”</a>, April 19, 2020, accessed March 31, 2021. As of July 3, 2020, the letter had 650 signatories. </li>
<li class="small-text">For more information, see Jason Bay, Joel Kek, Alvin Tan, Chai Sheng Hau, Lai Yongquan, Janice Tan, and Tang Anh Quy, <a target="_blank" href="https://bluetrace.io/static/bluetrace_whitepaper-938063656596c104632def383eb33b3c.pdf">“BlueTrace: A Privacy-Preserving Protocol for Community-Driven Contact Tracing Across Borders”</a>, Government Technology Agency Singapore, April 9, 2020, accessed March 31, 2021. </li>
<li class="small-text">Shen Xinmei, <a target="_blank" href="https://www.scmp.com/abacus/tech/article/3084064/personal-information-collected-fight-covid-19-being-spread-online-china">“Personal Information Collected to Fight Covid-19 Is Being Spread Online in China”</a>, <em>South China Morning Post</em>, May 12, 2020, accessed March 31, 2021. </li>
<li class="small-text">Jack Cassell, <a target="_blank" href="https://theconversation.com/coronavirus-why-did-england-ignore-an-army-of-existing-contact-tracers-140825">“Coronavirus: Why Did England Ignore an Army of Existing Contact Tracers?”</a> <em>The Conversation</em>, June 18, 2020, accessed March 31, 2021. </li>
<li class="small-text">See, for example, Department of Health Australia, <a target="_blank" href="https://www1.health.gov.au/internet/main/publishing.nsf/Content/cdna-song-tuberculosis"> “Communicable Diseases Network Australia Guidelines for Public Health Units–Management of TB”</a>, last updated May 12, 2015, accessed March 31, 2021. </li>
<li class="small-text">World Health Organization: Regional Office for Africa, <a target="_blank" href="http://www.who.int/csr/resources/publications/ebola/contact-tracing-during-outbreak-of-ebola.pdf">“Contact Tracing During an Outbreak of Ebola Virus Disease”</a>, September 2014, accessed March 31, 2021. </li>
<li class="small-text">Reed Albergotti and Drew Harwell, <a target="_blank" href="https://www.washingtonpost.com/technology/2020/05/15/app-apple-google-virus/">“Apple and Google Are Building a Virus-Tracking System. Health Officials Say It Will Be Practically Useless”</a>, <em>Washington Post</em>, May 16, 2020, accessed March 31, 2021. </li>
<li class="small-text">Mark Scott, Elisa Braun, Janosch Delicker, and Vincent Manancourt, <a target="_blank" href="https://www.politico.eu/article/google-apple-coronavirus-app-privacy-uk-france-germany/">“How Google and Apple Outflanked Governments in the Race to Build Coronavirus Apps”</a>, <em>Politico</em>, May 15, 2020, accessed March 31, 2021. </li>
<li class="small-text">See Note 9. </li>
<li class="small-text">Terence Sim Mong Cheng, <a target="_blank" href="https://www.straitstimes.com/opinion/forum/forum-tracetogether-data-may-not-be-that-useful-for-criminal-investigation">“Forum: TraceTogether Data May Not Be That Useful for Criminal Investigation”</a>, <em>The Straits Times</em>, January 5, 2021, accessed March 31, 2021. </li>
<li class="small-text">Ben Leong, <a target="_blank" href="https://benlwl.medium.com/another-year-another-fiasco-91dc38bc59c9">“Another Year, Another Fiasco”</a>, post published on <em>Medium</em>, January 6, 2021, accessed March 31, 2021. </li>
<li class="small-text">David Sun, <a target="_blank" href="https://www.straitstimes.com/singapore/politics/tracetogether-data-was-accessed-in-may-2020-for-punggol-fields-murder">“TraceTogether Data Was Accessed in May 2020 for Punggol Fields Murder Investigation”</a>, <em>The Straits Times</em>, February 2, 2021, accessed March 31, 2021. </li>
<li class="small-text">World Economic Forum White Paper, <a target="_blank" href="../www3.weforum.org/docs/WEF_APPA_Authorized_Public_Purpose_Access.html">“APPA—Authorised Public Purpose Access: Building Trust into Data Flows for Well-being and Innovation”</a>, December 2019, accessed March 31, 2021. </li>
<li class="small-text">Masako Okamoto and Takanori Fujita, <a target="_blank" href="https://www.weforum.org/agenda/2020/08/contact-tracing-apps-privacy-framework-appa-data-governance/">“A New Data Governance Model for Contact Tracing: Authorised Public Purpose Access”</a>, <em>World Economic Forum</em>, August 12, 2020, accessed March 31, 2021. </li>
<li class="small-text">Jatinder Singh, Jennifer Cobbe, and Chris Norval, <a target="_blank" href="https://arxiv.org/pdf/1804.05741.pdf"> “Decision Provenance: Harnessing Data Flow for Accountable Systems”</a>, <em>IEEE Access</em> 7 (November 2019): 6562–6574, accessed March 31, 2021, doi: 10.1109/ACCESS.2018.2887201. </li>
<li class="small-text">“Lean Data Practices”, Mozilla, accessed March 31, 2021, https://www.mozilla.org/en-US/about/policy/lean-data/stay-lean/. </li>
<li class="small-text"><a target="_blank" href="https://www.reuters.com/article/uk-china-health-incubation-idUKKCN20G072">“Coronavirus Incubation Could Be as Long as 27 Days, Chinese Provincial Government Says”</a>, <em>Reuters</em>, February 22, 2020, accessed March 31, 2021. </li>
<li class="small-text">Isobel Braithwaite, Thomas Callender, Miriam Bullock, and Robert W. Aldridge, <a target="_blank" href="https://www.thelancet.com/journals/landig/article/PIIS2589-7500(20)30184-9/fulltext"> “Automated and Partly Automated Contact Tracing: A Systematic Review to Inform the Control of Covid-19”</a>, <em>The Lancet Digital Health</em> 2, no. 11 (November 2020):E607–621, accessed March 31, 2021, https://www.doi.org/10.1016/S2589-7500(20)30184-9. </li>
<li class="small-text">Jasmine Pazzano and Brian Hill, <a target="_blank" href="https://globalnews.ca/news/7372173/covid-alert-app-canada-problem/">“The Covid Alert App Isn’t Working As Well As It Should Be, and Canadians Are Part of the Problem”</a>, <em>Global News</em>, October 2, 2020, accessed March 31, 2021. </li>
<li class="small-text">Dewey Sim and Kimberly Lim, <a target="_blank" href="https://www.scmp.com/weekasia/people/article/3084903/coronavirus-why-arent-singapore-residents-using-tracetogether">“Coronavirus: Why Aren’t Singapore Residents Using the TraceTogether Contact-Tracing App?”</a> <em>South China Morning Post</em>, May 18, 2020, accessed March 31, 2021. </li>
<li class="small-text">Petition retrieved from https://www.change.org/p/singapore-government-singapore-says-no-to-wearable-devices-for-covid-19-contact-tracing. </li>
<li class="small-text">Sushovan Sircar, <a target="_blank">“Noida Reverses Mandatory Aarogya Setu Order after Legal Challenge”</a>, <em>The Quint</em>, May 20, 2020, accessed March 31, 2021. </li>
<li class="small-text">Ministry of Foreign Affairs Singapore, <a target="_blank" href="https://www.mfa.gov.sg/Newsroom/Press-Statements-Transcripts-and-Photos/2020/05/20200522-Sky-News-Australia-FM">“Minister for Foreign Affairs Dr Vivian Balakrishnan’s Skype Interview with Sky News Australia”</a>, May 22, 2020, accessed March 31, 2021. </li>
<li class="small-text">Smart Nation Singapore and Ministry of Health Singapore, <a target="_blank" href="https://www.smartnation.gov.sg/docs/default-source/press-release-materials/sndgg_tracetogether---media-factsheet.pdf">“Launch of New App for Contact Tracing”</a>, accessed March 31, 2021. </li>
</ol>






<br>
<br>	
<div class="back">
<a href="/ethos/">Back to Ethos Page</a>	
</div>