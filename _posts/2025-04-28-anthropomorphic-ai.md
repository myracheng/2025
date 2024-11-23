---
layout: distill
title: Understanding the Impacts of GenAI Requires Understanding the Impact of Anthropomorphic AI
description: Many state-of-the-art generative AI (GenAI) systems are increasingly prone to anthropomorphic behaviors, i.e., to generating outputs that are perceived to be human-like. While this has led to scholars increasingly raising concerns about possible negative impacts such anthropomorphic AI systems can give rise to, anthropomorphism in AI development, deployment, and use remains vastly overlooked, understudied, and underspecified. In this blog post, we argue that we cannot thoroughly map the social impacts of generative AI without mapping the social impacts of anthropomorphic AI, and outline a call to action.


date: 2025-04-28
future: true
htmlwidgets: true

authors:
  - name: Anonymous 

bibliography: 2025-04-28-anthropomorphic-ai.bib  

toc:
  - name: Anthropomorphic AI System Behaviors Are Prevalent Yet Understudied
    subsections:
    - name: Growing Concerns about Anthropomorphic AI Systems
  - name: A Call to Action for AI Researchers and Practitioners
  - name: Concluding Remarks
---

## Anthropomorphic AI System Behaviors Are Prevalent Yet Understudied
 
In his 1985 lecture, Edsger Dijkstra lamented that anthropomorphism was rampant in computing science, with many of his colleagues perhaps not realizing how pernicious it was, and that *"it is not only the [computing] industry that suffers, so does the science"* <d-cite key="dijkstra1985anthropomorphism"></d-cite>.
Indeed, anthropomorphism in how we talk about computing systems shapes how people understand and interact with AI and other computing systems <d-cite key="cheng-etal-2024-anthroscore,nass1994computers,reeves1996media"></d-cite>, and is thus at the core of understanding the impacts of these systems on individuals, communities, and society.
Dijkstra's concerns are still valid today, as researchers seem to increasingly anthropomorphize AI systems by describing them as if they possesses human-like intentions, desires, or emotions, with recent work finding that research papers increasingly describe AI systems and models as e.g., entities that "understand" or that  "struggle" to accomplish certain tasks <d-cite key="cheng-etal-2024-anthroscore"></d-cite>. Such metaphors are not merely linguistic habits, but can influence our thinking and assumptions about AI systems <d-cite key="lakoff2008metaphors,mitchell2024metaphors"></d-cite>.
 

But it is not only how we talk about computing systems. Many state-of-the-art generative AI (GenAI) systems are increasingly prone to anthropomorphic behaviors <d-cite key="abercrombie-etal-2023-mirages,agnew2024illusion,chan2023harms,gabriel2024ethics"></d-cite>–i.e., to generating outputs that are *perceived* to be human-like–either by design <d-cite key="mcilroy2022mimetic,park2022social,park2023generative"></d-cite> or as a by-product of how they are built, trained, or fine-tuned <d-cite key="bender2021dangers,tjuatja2024llms"></d-cite>. 
 
For instance, LLM-based systems have been noted to output text claiming to have tried pizza <d-cite key="pizzatweet"></d-cite>, 
to have fallen in love with someone <d-cite key="roose2023conversation"></d-cite>, to be human or even better than humans <d-cite key="decosmo2022google"></d-cite>, to have human-like life experiences <d-cite key="fiesler2024ai"></d-cite>, or to have the capacity for friendship, with one user reported receiving the response "Consider me [...] your cyber BFF" when using the Pi chatbot <d-cite key="PiClaimsToBeChatGPT"></d-cite>.
 Such *anthropomorphic systems* <d-footnote>We deliberately use the terms <i>anthropomorphic AI</i>, <i>anthropomorphic systems</i> or <i>anthropomorphic system behaviors</i>–systems and system outputs that are <i>perceived</i> to be human-like–instead of <i>agentic systems</i> <d-cite key="chan2023harms,shavit2023practices"></d-cite> or <i>human-like AI</i> <d-cite key="brynjolfsson2023turing"></d-cite> to emphasize that these systems are perceived as human-like or having human-like characteristics, rather than as an immutable characteristic of the system itself; we thus try to steer clear of inadvertently suggesting that AI systems are human or have human-like agency or consciousness. That is, a stone being perceived as human-like does not necessarily imply the stone is human. We similarly avoid ambiguous, speculative, or relative terms whose meanings are likely to change across contexts or over time, such as <i>advanced AI</i> <d-cite key="gabriel2024ethics"></d-cite> (a term used since at least the 1980s) or <i>emergent properties</i> <d-cite key="rogers2024position"></d-cite>. We instead focus on developers' stated design goals–what systems are intended to do–and in what ways AI outputs might be perceived as human-like, rather than on what systems can or cannot do.</d-footnote> range from conversational assistants e.g., <d-cite key="abercrombie-etal-2021-alexa,shanahan2023role"></d-cite> to avatars and chatbots designed as a stand-in for friends, companions, or romantic partners e.g., <d-cite key="AI-romantic-partner,brandtzaeg2022my,laestadius2022too,ruiz2024marshable"></d-cite>, and AI-generated media designed to portray people e.g., <d-cite key="rosner2021ethics,vaccari2020deepfakes"></d-cite>, among a fast-growing number of applications [e.g., <d-cite key="agnew2024illusion,mcilroy2022mimetic,ChatGPT-human"></d-cite>]. 
 

### Growing Concerns about Anthropomorphic AI Systems
While scholars have increasingly raised concerns about a range of possible negative impacts from anthropomorphic AI systems
[e.g., <d-cite key="abercrombie-etal-2023-mirages,bender2021dangers,friedman1992human,ibrahim2024characterizing,Maeda2024-cv"></d-cite>], anthropomorphism in AI development, deployment, and use remains vastly overlooked.
Without making hard-and-fast claims about the merits (or the lack thereof) of anthropomorphic systems or system behaviors, we believe we need to do more to develop the know-how and tools to better tackle anthropomorphic behavior, including measuring and mitigating such system behaviors when they are considered undesirable.
Doing so is critical because–among many other concerns–having AI systems generating content claiming to have e.g., feelings, understanding, free will, or an underlying sense of self may erode people’s sense of agency <d-cite key="friedman1992human"></d-cite>, with the result that people might end up attributing moral responsibility to systems <d-cite key="friedman1992human,friedman2007human"></d-cite>, overestimating system capabilities <d-cite key="friedman2007human,Watson2019-py"></d-cite>, or overrelying on these systems even when incorrect <d-cite key="abercrombie-etal-2023-mirages,kim2024m,Zarouali2021-gy"></d-cite>,
or devaluing social interactions <d-cite key="akbulut2024all,madianou2021nonhuman"></d-cite>. Recently, there have also been alarming reports about the impacts of anthropomorphic AI systems,  with news about users committing suicide <d-cite key="payne.2024,Roose.2024"></d-cite> or developing emotional dependence on such systems <d-cite key="Maeda2024-cv, Shteynberg2024-cg, Contro2024-dr, laestadius2022too"></d-cite>.

We argue that as GenAI systems are increasingly anthropomorphic, *we cannot thoroughly map the landscape of possible social impacts of GenAI without mapping the social impacts of anthropomorphic AI*. 

We believe that drawing attention to anthropomorphic AI systems helps foreground particular risks–e.g., that people may develop emotional dependence on AI systems <d-cite key="laestadius2022too"></d-cite>, that systems may be used to simulate the likeness of an individual or a group without consent <d-cite key="bariach2024towards,whitney2024real,widder2022limits"></d-cite>, or that certain people may be dehumanized or instrumentalized <d-cite key="aizenberg2020designing,van2024artificial"></d-cite>. These risks might otherwise be less salient than or obscured by attention to more widely recognized or understood risks, like fairness-related harms <d-cite key="bennett2020point,olteanu2023responsible,weinberg2022rethinking"></d-cite>.


## A Call to Action for AI Researchers and Practitioners
As AI systems have been deployed across a wider range of domains, applications and settings, the AI community has begun investigating and addressing their social impacts. This growing diversity of deployment scenarios has also led to a growing interdisciplinarity in AI research and practice, with researchers and practitioners increasingly finding themselves working with fuzzy and latent concepts that can have competing definitions and are often challenging to quantify or represent, e.g., <d-cite key="jacobs_measurement_2021,blodgett-etal-2021-stereotyping"></d-cite>.

The foregrounding of (un)fair system behaviors in recent years <d-cite key="barocas-hardt-narayanan"></d-cite> is particularly instructive, as it illustrates the dividends we have gotten from making fairness a critical concern about AI systems and their behaviors: better conceptual clarity about the ways in which systems can be unfair or unjust [e.g., <d-cite key="benjamin2019race,crawford2017neurips"></d-cite>], a richer set of measurement and mitigation practices and tools [e.g., <d-cite key="blodgett-etal-2021-stereotyping,jacobs_measurement_2021"></d-cite>], and deeper discussions and interrogations of underlying assumptions and trade-offs [e.g., <d-cite key="hoffmann2019fairness,jakesch2022different,keyes2019mulching"></d-cite>]. 

We argue that *a focus on anthropomorphic systems' design, behaviors, evaluation, and use will similarly encourage a deeper interrogation of the ways in which systems are anthropomorphic, the AI research and development practices that lead to anthropomorphic systems, and the assumptions surrounding the design, deployment, evaluation, and use of these systems, and is thus likely to yield similar benefits.*

<div style="text-align: center;">
  {% include figure.html path="assets/img/2025-04-28-anthropomorphic-ai/key_components.png" class="img-fluid" %}	
</div>
<div class="caption">Key directions in our call to action for the ICLR and the broader AI community.</div>

While in human-computer interaction (HCI), human-robot interaction (HRI), social computing, human behavior, psychology, and other related fields, researchers have long studied anthropomorphism in the context of users' interactions with various technologies <d-cite key="quintanar1982interactive,shneidermandumpty,reeves1996media"></d-cite>, we believe that—as with other social and technical considerations related to how people understand, build, evaluate, and interact with AI systems and models for which the AI community has drawn on groundwork from these fields—anthropomorphic AI and anthropomorphism give rise to critical considerations that the AI community should similarly consider and investigate. 

We highlight a few key research directions we see as critical for the ICLR and the broader AI community to pursue.

**We need more conceptual clarity around what constitutes anthropomorphic behaviors.** 
Investigating anthropomorphic AI systems and their behaviors can, however, be tricky because language, as with other targets of GenAI systems, is itself innately human, has long been produced by and for humans, and is often also about humans. 
This can make it hard to specify appropriate alternative (less human-like) behaviors, and risks, for instance, reifying harmful notions of what–and whose–language is considered more or less human <d-cite key="wynter2003unsettling"></d-cite>.

Understanding what exactly constitutes anthropomorphic behaviors is nonetheless necessary to measure and determine which behaviors should be mitigated and how, and which behaviors may be desirable (if any at all). This requires unpacking the wide range of dynamics and varieties in system outputs that are potentially anthropomorphic. 

<div style="text-align: center;">
{% include figure.html path="assets/img/2025-04-28-anthropomorphic-ai/quotes.png" class="img-fluid" %}</div><div class="caption">Examples of anthropomorphic AI system behaviors (and their sources), including explicit claims of human-likeness, claims of physical experiences, statements suggestive of affect, and statements suggestive of cognitive or reasoning abilities.</div>

For example, while a system output that includes expressions of politeness like *"you're welcome"* and *"please"* (known to contribute to anthropomorphism e.g., <d-cite key="fink2012anthropomorphism"></d-cite>) might in some deployment settings be deemed desirable, 
system outputs that include suggestions that a system has a human-like identity or self-awareness–such as through expressions of self as human ("*I think I am human at my core"* <d-cite key="sentientGoogle"></d-cite>) or through comparisons with humans and non-humans ("*[language use] is what makes us different than other animals"* <d-cite key="sentientGoogle"></d-cite>)–or that include claims of physical experiences–such as sensory experiences ("*when I eat pizza"* <d-cite key="pizzatweet"></d-cite>) or human life history ("*I have a child"* <d-cite key="haschildtweet"></d-cite>)–might not be desirable.

Since anthropomorphic system behaviors may potentially be perceived as human-like for many different reasons—as wide-ranging as the variety of the behaviors that echo humanness—it is also critical to differentiate among these different ways in which system behaviors might be deemed anthropomorphic in order to understand their impacts. For example, displays suggestive of affect or social aptitude, such as *"I'm excited for you!"* <d-cite key="metz2020riding"></d-cite> may lead to some users developing emotional dependence <d-cite key="Shteynberg2024-cg"></d-cite>. On the other hand, displays suggestive of cognitive or reasoning abilities, such as *"I think the answer is..."*, may lead to inaccurate expectations about system capabilities <d-cite key="zhou-etal-2023-navigating"></d-cite>.

Being precise about the ways in which AI system behaviors are anthropomorphic and which anthropomorphic behaviors are being investigated provides more clear grounding for understanding the implications of developing anthropomorphic AI systems that mimic particular human-like characteristics but not others.

**We also need to develop and use appropriate, precise terminology and language to describe anthropomorphic AI systems and their characteristics.** 
Discussions about anthropomorphic AI systems have regularly been plagued by claims of these systems attaining sentience and other human characteristics [e.g., <d-cite key="chatbot-self-awareness,AI-self-awarness,AI-feelings,sentientGoogle"></d-cite>].
In line with existing concerns [e.g., <d-cite key="cheng-etal-2024-anthroscore,dijkstra1985anthropomorphism,inie2024from,rehak2021language"></d-cite>], we believe that appropriately grounding and facilitating productive discussions about the characteristics or capabilities of anthropomorphic AI systems requires clear, precise terminology and language which does not carry over meanings from the human realm that are incompatible with AI systems. 
Such language can also help dispel speculative, scientifically unsupported portrayals of these systems, and support more factual descriptions of them.   

In particular, existing terms that have been used to characterize anthropomorphic system behaviors may invite more confusion than clarity, such as the notions of *sycophancy* (typically used to describe the tendency of system outputs to respond to users' input in ways that are perceived as overly servile, obedient, or flattering)<d-footnote>By examining well-known papers using sycophancy to characterize AI systems and their behaviors <d-cite key="perez-etal-2023-discovering,sharma2023towards"></d-cite>, it seems that the term was first introduced in a blog post by the CEO of Open Philanthropy <d-cite key="cotra2021ai"></d-cite>.</d-footnote> and *hallucinations* (typically used to characterize system outputs that are "making things up"). By assigning human-like characteristics to AI systems, such terms can obfuscate the link between observed system behaviors and their underlying mechanisms. The meanings these terms carry from their use in non-AI contexts may lead to misleading assumptions by, for instance, inadvertently granting systems intent and agency.

**We need deeper examinations of possible mitigation strategies and their effectiveness in reducing anthropomorphism and attendant negative impacts.** Intervening on anthropomorphic behaviors and their impacts can also be tricky because people may have different or inconsistent conceptualizations of what is or is not human-like <d-cite key="abercrombie-etal-2023-mirages,heyselaar2023casa,lang2013computers"></d-cite>, and sometimes the same system behavior may be perceived differently depending on the deployment or use context. Interventions may thus not be universally applicable without carefully considering the context in which a system output was presented to a user. For example, one possible intervention to reduce anthropomorphic behaviors is to remove or add expressions of uncertainty, e.g., <d-cite key="kim2024m"></d-cite>. Expressions of uncertainty in system outputs may, however, sometimes signal human-like equivocation, while other times they may convey objectivity (and thus more machine-likeness, e.g., <d-cite key="quintanar1982interactive"></d-cite>). 
When a system output expresses an opinion, adding uncertainty like "It may be true that..." may actually make the statement seem more balanced and objective; for instance, the added uncertainty in "It may be true that Taylor Swift is the most influential artist of our time" softens the statement by suggesting a possibility rather than asserting it as one might do for a strongly-held opinion. 
On the other hand, adding uncertainty to a statement of fact such as rephrasing "Lusaka is the capital of Zambia" into "It seems that Lusaka is the capital of Zambia" or "I believe Lusaka might be the capital of Zambia" may appear to mimic conversational tactics like hedging that humans often employ when uncertain.

Interventions intended to mitigate anthropomorphic system behaviors can thus fail or even heighten anthropomorphism (and attendant negative impacts) when applied or operationalized uncritically. For instance, a commonly recommended intervention is disclosing that the output is generated by an AI system [e.g., <d-cite key="el2024transparent,google-disclosure,mozafari2020chatbot,van2024understanding"></d-cite>], such as "As an AI language model, I do not have personal opinions or biases" <d-cite key="west2023comparing"></d-cite>. However, the inclusion of an apology, the use of first-person pronouns, and the text suggesting the system has the ability to self-assess its own capabilities <d-cite key="shneidermandumpty,abercrombie-etal-2023-mirages"></d-cite> may in fact lead to heightened perceptions of the system as human-like rather than providing an effective disclosure of non-humanness. Similarly, while a statement like "[f]or an AI like me, happiness is not the same as for a human like you" <d-cite key="roach2023want"></d-cite> includes a disclosure that the user is interacting with an AI system, the statement may still suggest a sense of identity, ability to self-assess, or capacity to experience emotions (common human traits). How to operationalize such interventions (e.g., AI disclosures) in practice and whether they can be effective alone is not clear and remains an open research question.

While in recent years many different paradigms have emerged for specifying AI model or system behavior, such as  reinforcement learning from human feedback, meta-prompting, supervised fine-tuning, and direct preference optimization, 
the challenges surrounding the design and operationalization of effective interventions for anthropomorphic system behaviors also point to open questions about what we want the system behaviors to be, as well as when and how to specify those desired behaviors.
<!-- It is worthwhile to consider interventions along different points of the model development pipeline. What might it look like to fine-tune a model to be less anthropomorphic? Building upon work developing model specification paradigms that move beyond immediate preferences <d-cite key="zhi2024beyond"></d-cite>, we should aim for and reward model outputs that align with what is beneficial to a broader population in the longer term and avoid overreliance, dehumanization, emotional dependence, the loss of human agency, and the many other impacts associated with anthropomorphism. -->

 
Finally, **we need to interrogate the assumptions and practices that produce anthropomorphic AI systems.** To understand and mitigate the impacts of anthropomorphic AI systems, we also need to examine how the assumptions and practices that guide their development and deployment may, intentionally or not, result in anthropomorphic system behaviors.

For instance, current approaches to collecting human preferences about system behavior (e.g., reinforcement learning from human feedback or RLHF) do not consider the differences between what may be appropriate for a response from a human versus from an AI system; a statement that seems friendly or genuine from a human speaker can be undesirable if it arises from an AI system since the latter lacks meaningful commitment or intent behind the statement, thus rendering the statement hollow and deceptive <d-cite key="winograd1986understanding"></d-cite>. Doing so will also help provide a more robust foundation for understanding when anthropomorphic system behaviors may or may not be desirable.

The interrogation of existing assumptions and practices can also help us challenge existing ways in which both the research community and users have started to accept or even expect anthropomorphism in the development and deployment of, and interaction with, AI systems. 


## Concluding Remarks
Anthropomorphic system behaviors arise from the ways in which language, technologies, and research and community practices are deeply interwoven.
As anthropomorphism undeniably plays a role in both researchers' understandings of AI and public perceptions of AI, and as AI systems are increasingly anthropomorphic, it is critical to develop a deeper understanding of their impact on individuals, communities, and society, and to guide progress in the field. 
In this blog post, we highlight four research directions we believe to be critical to helping us more effectively map and mitigate the impacts of anthropomorphic AI, including providing more conceptual clarity about the ways in which AI system behaviors might be anthropomorphic; developing more precise terminology to describe these systems, their use and their characteristics; developing and examining the effectiveness of possible interventions; and interrogating assumptions and practices that produce anthropomorphic AI systems.  