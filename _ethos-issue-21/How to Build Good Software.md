---
title: How to Build Good Software
permalink: /ethos-issue-21/how-to-build-good-software/
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

iframe {
	width: 100% !important;
	
	}	
	
</style>

<em><small>ETHOS Issue 21, July 2019</small></em>
<img src="/images/Cropped_images/Ethos_Issue_21/21_Banner_How_To_Build_Good_Software.jpg">



<h3>Why Bad Software Happens to Good People</h3>

<p>Bad software is one of the few things in the world you cannot solve with money. Billion dollar airlines have flight search apps that are often inferior to those built by groups of students. Established taxi
companies the world over have terrible booking apps despite the threat they face from ride-sharing services. And painful corporate IT systems are usually projects with massive budgets, built over the course of many years. Whatever the cause of bad software is, it does not seem to be a lack of funding.</p>

<p>Surprisingly, the root cause of bad software has less to do with specific engineering choices, and more to do with how development projects are managed. The worst software projects often proceed in a very particular way:</p>

<p>The project owners start out wanting to build a specific solution and never
explicitly identify the problem they are trying to solve. They then gather a long list of requirements from a large group of stakeholders. This list is then handed off to a correspondingly large external development team, who get to work building this highly customised piece of software from scratch. Once all the requirements are met, everyone celebrates as the system is launched and the project is declared complete.</p>

<div class="break">

<p class="break1">
The root cause of bad software has less to do with specific engineering choices, and more to do with how development projects are managed.
</p>

</div>

<p> However, though the system technically meets specifications, severe issues are
found when it is put in the hands of actual users. It is slow, confusing, and
filled with subtle bugs that make using it an exercise in frustration. Unfortunately,
by this time the external development team has been dismissed and there
are no resources left over to make the necessary fixes. By the time a new project
can be initiated years later, all knowledge of what caused these problems has left
the organisation and the cycle starts over again.</p>

<iframe src="https://player.vimeo.com/video/399806241?color=ffffff&amp;title=0&amp;byline=0" frameborder="0"></iframe>

<br>

<p style="text-align: center;" class="small-text">A Conversation with Li Hongyi (Part 1)<br>
<em>Scroll down for more videos</em></p>

<p>The right coding language, system architecture, or interface design will
vary wildly from project to project. But there are characteristics particular
to software that consistently cause traditional management practices to fail, while allowing small startups to succeed with a shoestring budget:</p>

<p>• Reusing good software is easy;
it is what allows you to build good
things quickly;<br>
• Software is limited not by the amount
of resources put into building it, but
by how complex it can get before it
breaks down; and<br>
• The main value in software is not the
code produced, but the knowledge
accumulated by the people who
produced it.</p>

<p>
</p>

<p>Understanding these characteristics may not guarantee good outcomes, but it
does help clarify why so many projects produce bad outcomes. Furthermore,
these lead to some core operating principles that can dramatically improve
the chances of success:</p>

<p>
</p>

<p>1. Start as simple as possible;<br>
2. Seek out problems and iterate; and<br>
3. Hire the best engineers you can.</p>

<p>While there are many subtler factors to consider, these principles form a foundation that lets you get started building good software.</p>

<h3>Reusing Software Lets You Build Good Things Quickly</h3>

<p>Software is easy to copy. At a mechanical level, lines of code can literally be copied and pasted onto another computer. More generally, the internet is full of tutorials on how to build different kinds of systems using ready-made code modules that are available online. Modern software is almost never developed from scratch. Even the most innovative applications are built using existing software that has been combined and modified to achieve a new result.</p>

<p>The biggest source of reusable code modules is the open source community. Open source software is software in which code is freely published for anyone to see and use. Many of the largest contributors to the open source community are giant tech companies. If you want to use a state-of-the-art planet scalable database as Facebook does, just download the code for Cassandra that they open sourced in 2008. If you want to try out Google’s cutting-edge machine learning for yourself, download the TensorFlow system published in 2015. Using open source code does not just make your application development faster, it gives you access to technology that is far more sophisticated than anything
you could have developed yourself. For the most popular open source code, it is even more secure as there are many more people paying attention and fixing vulnerabilities. This is the reason digital technology has made such rapid progress: even the newest engineers can build upon the most advanced tools our profession has to offer.</p>

<p>The advent of cloud services has taken reusability even further, offering the full use of even proprietary systems for just a subscription fee. Need a simple website? Just configure one in a few clicks using a website building service like Squarespace or Wix. A database? Subscribe to a virtual one from Amazon Web Services or Microsoft Azure. Cloud services allow developers to benefit from specialisation; the service provider handles the setup, maintenance, and continued development of a reliable, high-quality piece of software that is used by all its subscribers. This allows software developers to stop wasting time on solved problems and instead focus on delivering actual value.</p>

<p>You cannot make technological progress if all your time is spent on rebuilding existing technology. Software engineering is about building automated systems, and one of the first things that gets automated away is routine software engineering work. The point is to understand what the right systems to reuse are, how to customise them to fit your unique requirements, and fixing novel problems
discovered along the way.</p>

<div class="break">

<p class="break1">
Software engineering is about building automated systems, and one of the first things that gets automated away is routine software engineering work.
</p>

</div>

<h3>Software Is Limited by Complexity</h3>

<p>How useful a piece of software can be is usually limited by its complexity rather than the amount of resources invested in building it.</p>

<p>IT systems are often full of features but are still hated by users because of how confusing they become. In contrast, highly ranked mobile apps tend to be lauded for their simplicity and
intuitiveness. Learning to use software is hard. Beyond a point, new features actually make things worse for users because the accumulated complexity starts to become overwhelming. For example, after serving as the hub of Apple’s media ecosystem for almost 20 years, iTunes was split into three
different apps (for music, podcasts, and TV shows) this year, as its features had grown too complex for one app to handle. From a usability perspective, the limit is not how many features can be implemented, but rather what can fit into a simple intuitive interface.</p>

<p>Even ignoring usability, engineering progress slows to a halt once a project becomes too complex. Each new line of code added to an application has a chance of interacting with every other
line. The bigger an application’s codebase, the more bugs are introduced whenever a new feature is built. Eventually, the rate of work created from new bugs cancels out the rate of work done from feature development. This is known as “technical debt” and is the main challenge in professional software development. It is the reason why many large IT systems have issues that go unfixed for years.
Adding more engineers to the project just adds to the chaos: they start running
faster in place as the codebase keels over from its own weight.</p>

<div class="break">

<p class="break1">
Building good software involves alternating cycles of expanding and reducing complexity.
</p>

</div>

<p>In such cases, the only way forward is to take a step back to rationalise and
simplify the codebase. The system architecture can be redesigned to limit
unexpected interactions. Non-critical features can be removed even if they
have already been built. Automated tools can be deployed to check for bugs and
badly written code. Bill Gates once said “Measuring programming progress by
lines of code is like measuring aircraft building progress by weight”. Human minds can only handle a finite amount of complexity, so how sophisticated a software system can get depends on
how efficiently this complexity budget is used.</p>

<p>Building good software involves alternating cycles of expanding and reducing complexity. As new features are developed, disorder naturally accumulates in the system. When this messiness
starts to cause problems, progress is suspended to spend time cleaning up. This two-step process is necessary because there is no such thing as platonically good engineering: it depends on your
needs and the practical problems you encounter. Even a simple user interface such as Google’s search bar contains a massive amount of complexity under the surface that cannot be perfected in a single iteration. The challenge is managing this cycle, letting it get messy enough to make meaningful progress,
but not letting it get so complicated that it becomes overwhelming.</p>

<div class="break">

<p class="break1">
There is no such thing as platonically good engineering: it depends on your needs and the
practical problems you encounter.
</p>

</div>

<h3>Software Is about Developing Knowledge More than Writing Code</h3>

<p>In software development, most ideas are bad; this is not anyone’s fault. It is just
that the number of possible ideas is so large that any particular idea is probably
not going to work, even if it was chosen very carefully and intelligently. To make
progress, you need to start with a bunch of bad ideas, discard the worst, and
evolve the most promising ones. Apple, a paragon of visionary design, goes
through dozens of prototypes before landing on a final product. The final
product may be deceptively simple; it is the intricate knowledge of why this
particular solution was chosen over its alternatives that allows it to be good.</p>

<p>This knowledge continues to be important even after the product is built. If a new
team takes over the code for an unfamiliar piece of software, the software will soon
start to degrade. Operating systems will update, business requirements
will change, and security problems will be discovered that need to be fixed. Handling these subtle errors is often harder than building the software in the first place, since it requires intimate
knowledge of the system’s architecture and design principles.</p>

<iframe src="https://player.vimeo.com/video/399806767?color=ffffff&amp;title=0&amp;byline=0" frameborder="0"></iframe>

<br>

<p style="text-align: center;" class="small-text">A Conversation with Li Hongyi (Part 2)<br>
<em>Scroll down for more videos</em></p>

<p>In the short term, an unfamiliar development team can address these problems with
stopgap fixes. Over time though, new bugs accumulate due to the makeshift nature
of the additional code. User interfaces become confusing due to mismatched
design paradigms, and system complexity increases as a whole. Software should be
treated not as a static product, but as a living manifestation of the development
team’s collective understanding.</p>

<div class="break">

<p class="break1">
Software should be treated not as a static product, but as a
living manifestation of the development team’s collective understanding.
</p>

</div>

<p>This is why relying on external vendors for your core software development is
difficult. You may get a running system and its code, but the invaluable knowledge
of how it is built and what design choices were made leaves your organisation.
This is also why handing a system over to new vendors for “maintenance” often
causes problems. Even if the system is very well documented, some knowledge
is lost every time a new team takes over. Over the years, the system becomes a
patchwork of code from many different authors. It becomes harder and harder
to keep running; eventually, there is no one left who truly understands how
it works.</p>

<p>For your software to keep working well in the long term, it is important to
have your staff learning alongside the external help to retain critical engineering
knowledge in your organisation.</p>

<h3>3 Principles for Good Software Development</h3>


<br>
<h4>Start as Simple as Possible</h4>
<p>Projects that set out to be a “one-stop
shop” for a particular domain are often
doomed. The reasoning seems sensible
enough: What better way to ensure your
app solves people’s problems than by
having it address as many as possible?
After all, this works for physical stores
such as supermarkets. The difference is
that while it is relatively easy to add a
new item for sale once a physical store
is set up, an app with twice as many
features is more than twice as hard to
build and much harder to use.</p>

<p>Building good software requires focus:
starting with the simplest solution that
could solve the problem. A well-made
but simplistic app never has problems
adding necessary features. But a big IT
system that does a lot of things poorly
is usually impossible to simplify and
fix. Even successful “do it all” apps like
WeChat, Grab, and Facebook started
out with very specific functionality and
only expanded after they had secured
their place. Software projects rarely
fail because they are too small; they fail
because they get too big.</p>

<div class="break">

<p class="break1">
Software projects rarely fail because they
are too small; they fail because they get too big.
</p>

</div>

<p>Unfortunately, keeping a project focused
is very hard in practice: just gathering
the requirements from all stakeholders
already creates a huge list of features.</p>

<iframe src="https://player.vimeo.com/video/399807325?color=ffffff&amp;title=0&amp;byline=0" frameborder="0"></iframe>

<br>

<p style="text-align: center;" class="small-text">A Conversation with Li Hongyi (Part 3)<br>
<em>Scroll down for last video</em></p>

<p>One way to manage this bloat is by
using a priority list. Requirements are
all still gathered, but each are tagged
according to whether they are absolutely
critical features, high-value additions,
or nice-to-haves. This creates a much
lower-tension planning process because
features no longer need to be explicitly
excluded. Stakeholders can then more
sanely discuss which features are the
most important, without worrying about
something being left out of the project.
This approach also makes explicit the
trade-offs of having more features.
Stakeholders who want to increase
the priority for a feature have to also
consider what features they are willing
to deprioritise. Teams can start on the
most critical objectives, working their way
down the list as time and resources allow.</p>

<p>We followed a similar process for all
our most successful apps. Form.gov.sg
started out as a manual Outlook Macro
that took us six hours to set up for
our first user but today has processed
about a million public submissions.
Data.gov.sg started out as a direct copy
of an open source project and has since
grown to over 300,000 monthly visits.
Parking.sg had a massive list of almost
200 possible features that we never
got around to building but still has over
1.1 million users today. These systems
are well received not in spite of their
simplicity but because of it.</p>


<br>
<h4>Seek Out Problems and Iterate</h4>
<p>In truth, modern software is so complicated and changes so rapidly that no amount of
planning will eliminate all shortcomings. Like writing a good paper, awkward
early drafts are necessary to get a feel of what the final paper should be. To
build good software, you need to first build bad software, then actively seek out problems to improve on your solution.</p>

<p>This starts with something as simple as talking to the actual people you are trying to help. The goal is to understand the root problem you want to solve and  avoid jumping to a solution based just on preconceived biases. When we first started on Parking.sg, our hypothesis was that enforcement officers found it frustrating  to have to keep doing the mental calculations regarding paper coupons. However, after spending just one afternoon with an experienced officer, we discovered that
doing these calculations was actually quite simple for someone doing it professionally. That single conversation saved us months of potentially wasted effort and let us refocus our project on helping drivers instead. </p>

<p>Beware of bureaucratic goals masquerading as problem statements. “Drivers feel frustrated when dealing with  parking coupons” is a problem. “We need to build an app for drivers as part of our Ministry Family Digitisation Plans” is not.  “Users are annoyed at how hard it is to find information on government websites” is a problem. “As part of the Digital Government Blueprint, we need to rebuild our websites to conform to the new design service standards” is not. If our end goal is to make citizens’ lives better, we need to explicitly acknowledge the things that are making their lives worse.</p>

<p>Having a clear problem statement lets you experimentally test the viability of different solutions that are too hard to determine theoretically.  Talking to a chatbot may not be any easier than navigating a website, and users may not want to install yet another app on their phones no matter how secure it makes the country. With software, apparently obvious solutions often have fatal flaws that do not show up until they are put to use.  The aim is not yet to build the final product, but to first identify these problems as quickly and as cheaply as possible. Non-functional mock-ups to test interface designs. Semi-functional mock-ups to try different features. Prototype code, written hastily, could help garner feedback more quickly. Anything created at this stage should be treated as disposable. The desired output
of this process is not the code written, but a clearer understanding of what the right thing to build is.</p>

<div class="break">

<p class="break1">
Beware of bureaucratic goals masquerading as problem statements. If our end goal is to make citizens’ lives better, we need to explicitly acknowledge the things that are making their lives worse.
</p>

</div>

<p>With a good understanding of the right solution, you can start work on building the actual product. You stop exploring new ideas and narrow down to identifying problems with your particular implementation. Begin with a small number of testers who will quickly spot the obvious bugs that need to be fixed. As problems are addressed, you can increasingly open up to a larger pool who will find more esoteric issues.</p>

<p>Most people only give feedback once. If you start by launching to a large audience, everyone will give you the same obvious feedback and you’ll have nowhere to go from there. Even the best product ideas built by the best engineers will start out with significant issues. The aim is to repeatedly refine the output,
sanding down rough edges until a good product emerges.</p>

<p>Even after all this iteration, after launch is when problems with a product matter
the most. A problem that happens only 0.1% of the time may not get noticed
during testing. But once you have a million users, every day the problem
goes unresolved is a thousand more angry people you have to deal with. You need to fix problems caused by new mobile devices, network outages, or security attacks before they cause
substantial harm to your users. With Parking.sg we built a series of secondary
systems that continuously check the main system for any discrepancies in
payments, duplicate parking sessions, and application crashes. Building up
an “immune system” over time lets you avoid being overwhelmed as new issues
inevitably come up.</p>

<p>Overall, the approach is to use these different feedback loops to efficiently
identify problems. Small feedback loops allow for quick and easy correction
but miss out on broader issues. Large feedback loops catch broader issues but
are slow and expensive. You want to use both, resolving as much as possible with
tight loops while still having wide loops to catch unexpected errors. Building
software is not about avoiding failure; it is about strategically failing as fast
as possible to get the information you need to build something good.</p>


<br>
<h4>Hire the Best Engineers You Can</h4>
<p>The key to having good engineering is having good engineers. Google,
Facebook, Amazon, Netflix, and Microsoft all run a dizzying number of the largest
technology systems in the world, yet, they famously have some of the most
selective interview processes while still competing fiercely to recruit the strongest
candidates. There is a reason that the salaries for even fresh graduates have
gone up so much as these companies have grown, and it is not because they
enjoy giving away money.</p>

<p>Both Steve Jobs and Mark Zuckerberg have said that the best engineers are at
least 10 times more productive than an average engineer. This is not because
good engineers write code 10 times faster. It is because they make better
decisions that save 10 times the work.</p>

<p>A good engineer has a better grasp of
existing software they can reuse, thus
minimising the parts of the system they
have to build from scratch. They have
a better grasp of engineering tools,
automating away most of the routine
aspects of their own job. Automation
also means freeing up humans to work
on solving unexpected errors, which the
best engineers are disproportionately
better at. Good engineers themselves
design systems that are more robust
and easier to understand by others.
This has a multiplier effect, letting their
colleagues build upon their work much
more quickly and reliably. Overall, good
engineers are so much more effective
not because they produce a lot more
code, but because the decisions they
make save you from work you did not
know could be avoided.</p>

<iframe src="https://player.vimeo.com/video/399807968?color=ffffff&amp;title=0&amp;byline=0" frameborder="0"></iframe>

<br>

<p style="text-align: center;" class="small-text">A Conversation with Li Hongyi (Part 4)</p>

<p>This also means that small teams of the
best engineers can often build things
faster than even very large teams of
average engineers. They make good
use of available open source code and
sophisticated cloud services, and offload
mundane tasks onto automated testing
and other tools, so they can focus on the creative problem-solving aspects of
the job. They rapidly test different ideas
with users by prioritising key features
and cutting out unimportant work. This
is the central thesis of the classic book
“The <em>Mythical Man-Month</em>”<a href="#notes"><sup>1</sup></a>: in general,
adding more software engineers does
not make a project go faster, it only
makes it grow bigger.</p>

<div class="break">

<p class="break1">
Building software is not about avoiding failure; it is about strategically failing as fast as possible to get the information you need to build something good.
</p>

</div>

<p>Smaller teams of good engineers will
also create fewer bugs and security
problems than larger teams of average
engineers. Similar to writing an essay, the
more authors there are, the more coding
styles, assumptions, and quirks there
are to reconcile in the final composite
product, exposing a greater surface area
for potential issues to arise. In contrast,
a system built by a smaller team of
good engineers will be more concise,
coherent, and better understood by
its creators. You cannot have security
without simplicity, and simplicity is rarely
the result of large-scale collaborations.</p>

<p>The more collaborative an engineering
effort, the better the engineers need
to be. Problems in an engineer’s code
affect not just his work but that of his
colleagues as well. In large projects,
bad engineers end up creating more
work for one another, as errors and
poor design choices snowball to create
massive issues. Big projects need to
be built on solid reliable code modules
in an efficient design with very clear
assumptions laid out. The better your
engineers, the bigger your system can
get before it collapses under its own
weight. This is why the most successful
tech companies insist on the best talent
despite their massive size. The hard limit
to system complexity is not the quantity
of engineering effort, but its quality.</p>

<h3>Conclusion</h3>

<p>Good software development starts
with building a clear understanding of
the problem you want to solve. This
lets you test many possible solutions
and converge on a good approach.
Development is accelerated by reusing
the right open source code and cloud
services, granting immediate access
to established software systems and
sophisticated new technology. The
development cycle alternates between
exploration and consolidation, quickly
and messily progressing on new ideas,
then focusing and simplifying to keep
the complexity manageable. As the
project moves forward, it gets tested
with successively larger groups of people
to eliminate increasingly uncommon
problems. Launching is when the real work
ramps up for a good development team:
layers of automated systems should be
built to handle issues quickly and prevent
harm to actual users. Ultimately, while
there are infinite intricacies to software
development, understanding this process
provides a basis to tackle the complexities
of how to build good software.</p>

<div class="author">

<h6>ABOUT THE AUTHOR</h6>


<p class="small-text"><strong>Li Hongyi&nbsp;</strong>leads a team of engineers, designers,
            and product managers who build technology for the public good. Projects they have
            worked on include Parking.sg—an app to replace parking coupons, Form.gov.sg—a web app for building online government forms in minutes, and Data.gov.sg—the government’s open data repository. Prior
            to joining the public sector, Hongyi worked at Google on the distributed databases and
            image search teams. In his free time, he works on personal projects like typographing.com
            and chatlet.com.</p>

</div>


<h6><a name="notes"></a>NOTE</h6>

<ol>
<li class="small-text">
    Frederick P. Brooks, Jr., <em>The Mythical Man-Month: Essays on Software Engineering, Anniversary Edition</em>,
    2nd ed. (Boston, MA: Addison-Wesley Longman, 1995).</li>
</ol>







<br>
<br>	
<div class="back">
<a href="/ethos/">Back to Ethos Page</a>	
</div>