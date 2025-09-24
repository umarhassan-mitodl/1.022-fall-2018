---
content_type: page
description: This section contains details for a final project of a student's own
  choosing.
draft: false
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Final Project
parent_type: CourseSection
parent_uid: dbecca52-01f3-8413-20b1-fda5e6c91ec5
title: Proposing Your Own Application of Interest
uid: bc823579-a0b2-aa50-9d9e-e51d494a569d
video_metadata:
  youtube_id: null
---
You have the option of proposing your own application of interest for the project. To do so, you will first need to write a short one-page proposal:

- Briefy describe the application in mind and the model you want to use (this could be a reference to a paper on the topic from which you want to use the model).
- Specify the dataset you want to work with (with the link to the dataset).
- Discuss what you want to do with the data.

You should email your proposal to both the Teaching Assistant and instructor by Lecture 18. Be sure to specify your research question (Part II) and your proposed approach (Part III). Don't worry about the bumps that you may face by going with your own project, we will help you get it done. If the findings are novel and interesting, it can result in some publication and you can continue working on it as a paid job at the {{% resource_link "ac21247d-c775-4184-b55f-6ee6f0624b57" "MIT Institute for Data, Systems, and Society (IDSS)" %}} over the summer.

Here are some papers (and ideas based on them) that may help you come up with an idea for your proposal:

- Battiston et al. (2012) {{% resource_link "41d096ff-0f06-428e-8861-8ba33303f785" "*DebtRank: Too Central to Fail? Financial Networks, the FED and Systemic Risk*" %}}.

Analyze inter-bank connection to understand how the network (for example, distribution of degrees, centralities, …) changes with the state of the economy (e.g., in a volatile economy like 2008 versus a more stable economy in the years before). Consider the systemic risk in the network such as how defaults would spread from bank to bank. Does it depend on the centrality of the defaulting banks or the underlying network structure? A good database for this idea is provided by the {{% resource_link "2a4a15c9-536b-440f-be22-40192d5faed7" "International Monetary Fund" %}} website.

- Akbarpour et al. (2018) {{% resource_link "21f9f765-d56a-4700-a2e2-a9191a3d7f24" "*Just a Few Seeds More: Value of Network Information for Diffusion (PDF)*" %}}. 

Given some novel information and a social network, which individuals would you inform in order to maximize its spread if you can only contact a few people? First define an underlying model of diffusion for a network and then compare several seeding strategies for different realistic networks. Compare their performance and its dependence on the underlying network structure and diffusion model. Does it make sense to use centrality-based measures, or exploit the friendship paradox? How do these strategies compare to random seeding?

- Shah and Zaman (2011) {{% resource_link "d1c0bb1f-78b5-488e-9528-7bbaa0f36ae1" "*Rumors in a Network: Who's the Culprit? (PDF - 1.2MB)*" %}}. 

Consider a rumor that originates at a single node and spreads through a network. If you only observe the end result of the spread (which nodes end up hearing the rumor), can you come up with an algorithm to determine which node initiated the rumor? This paper proposes an algorithm based on what they call rumor centrality. See if you can apply it to some realistic or simulated networks. Propose alternative algorithms and test their performance.

You can also look at the datasets available at the following databases to come up with an idea:

- {{% resource_link "8966ee8c-dfc7-4363-bcea-46907104c1dd" "The Colorado Index of Complex Networks (ICON)" %}}
- {{% resource_link "d20034ea-e6a3-4923-9444-b4981abde707" "The Koblenz Network Collection (KONECT)" %}}
- {{% resource_link "0f827ca1-ede6-4663-bfad-e0125c72ea02" "Stanford Large Network Dataset Collection" %}}

## Timeline

Each individual (or group if you are working with someone else) will have to write and submit a report along with their Python code.{{< sup "1" >}} The report should describe the motivation of your project, the network dataset, the descriptive information from Part I, the research question, model and thesis from Part II, and finally your approach and results from Part III. The Part I descriptive write-up will be due before the final report, in order to make sure everyone is on track. You will also have to give a 15 minute presentation on your project during the last week of class. There will be the following deadlines.

- Lecture 21: Part I descriptive write-up.
- Lecture 25: Oral Presentation (15 minutes).
- One week after Lecture 25: Final project report (including all code).

{{< sup "1" >}}You may use other programming languages, while Python is preferred.