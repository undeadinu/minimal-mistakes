---
title: "Virtual Research Environment"
description: "What can the nearly 60,000 lives documented in the *Oxford Dictionary of National Biography (ODNB)* tell us -in aggregate and individually- about the development and character of internationalism over time?"
categories:
  - 2017 COST Action
tags:
  - content
  - css
  - edge case
  - lists
  - markup
---


### Project leader: Charles van den Heuvel

### Scholars: Charles van den Heuvel, Celine Frohn, Meliha Handzic, Stefan Trausan Matu

### Design researchers: Ángeles Briones, Michele Invernizzi


## About the project

Our goal was to create a virtual research environment (VRE) using the expansive data from the Republic of Letters. In this environment a researcher should be able to find and analyze the very diverse sources that make up the reassembled Republic of Letters, including primary texts, images, visualizations, and the connections between those. Our main issue was connecting all these different sources in a meaningful, non-reductive, and accessible manner. We wanted to go beyond the mainly text-based interfaces of current search tools, and create a cohesive interface based on visual exploration. We are trying to answer topical, spatial, network-related, and temporal questions. The anticipated output was a sketchbook, but in the future the interface should be implemented in such a way that all these dimensions can be explored and analysed in more detail.

As our project in itself is more of an exploration of what a VRE can look like and how it could work, this project report is not subdivided into methodology and findings, but rather provides a description of our process of designing conceptually in a collaborative way. There a several models describing the research practices in the analysis and visualization of data that can be taken as part of departure.(1) For the reason that the other four work groups were creating interfaces to real data, we decided in our group to concentrate on “exploration” rather than implementation. An important requirement for the development of our explorative interface was that it would allow for getting access to both unstructured and structured data. This distinction was necessary because in the four other workgroups the emphasis was on the development of structured (meta-)data which limits to great extent the analysis of full text of the Republic of Letters. Recurrent themes in Republic of Letters such as trust, confidentiality just cannot be found with simple keyword queries and require additional methods of text analyses and natural language processing techniques.

![](/Users/valentina/Google Drive/COST Packing-up sprints outcomes [2018-06]/01_Documentation/02_Images/2017_G5 Images/steps on the research journey.png)

This report describes the process of sketching out an interface to such a VRE in a team of humanities researchers and designers. It concludes with some future visions of the VRE and recommendations for the design sprint format for the humanities.



## **Aim of the project** 

To conceptualize a virtual research environment (VRE) that allows researchers to explore texts, images, metadata, and other types of information pertaining to the digitally Reassembled Republic of Letters.

### Research Question

In order to conceptualize a VRE that would be suitable for a wide research community to analyse the digitally Reassembled Republic of Letters (i.e. letters and contextual information) from various perspectives, we developed a group of very generic research questions:
How open is the Republic of Letters? (2)

- How open is the Republic of Letters?

- How reciprocal was the correspondence between two people?

- What is the geographical reach of exiles?

- What is a person’s network of ideas in relation to other people?

- What was the concept’s development over time/space?

- What are related concepts to a certain concept? (Word clouds, for example)

- How universal is knowledge within the ROL? 

  

In the end we focused on the first question in which we used the second one as an indication of the openness/closeness of the Republic of Letters.



## **Case study**

### Secrecy, confidentiality, and espionage in letter correspondences 

Taking the multiverse concept to a more abstract level, it become useful to think in terms of panes. After a planet in an universe was reached, one may need to have access in the same time to data from several universes, superposed in a pane. One person can be part of several networks at the same time. The Italian engineer Guerrini who was sent by Cosimo III dei Medici to Germany, the Netherlands and England figures differently in the context of espionage and in a religious context. (3) It can be said that Guerrini exists in different universes simultaneously, that have different gravitational forces, in the sent the exchanges between the people around him are different (for instant more or less reciprocal) in the different contexts.

Images of inventions of Guerrini stand close to other secret inventions for instance the patented torpedo-submarine designed by Cornelis Drebbel that was tested out on the River Thames in London between 1620-24. In a visual exploration based on gravitational forces it might be expected that will be closer to each other than images with a different content. Using this case, we have created several static mock-ups that illustrate how the VRE might work.

![](/Users/valentina/Google Drive/COST Packing-up sprints outcomes [2018-06]/01_Documentation/02_Images/2017_G5 Images/process-02.png)



In this case there is a difference between the intellectual and technical knowledge networks. The networks do not fully overlap, and the non-overlapping parts have a different nature of confidentiality. Compare the case of the role of Huygens in between intellectual and technological networks.(4) The letter exchanges amongst aristocrats are reciprocal, while the aristocrats request materials from artisans, and they do not send any drawings back. A graphic representation of this situation can be found below.

![](/Users/valentina/Google Drive/COST Packing-up sprints outcomes [2018-06]/01_Documentation/02_Images/2017_G5 Images/intellectual and tech knowledge exchange.png)



Here we have a difference in reciprocity, an aspect of letter exchanges that should be able to be studied within the VRE. It therefore is important to visualize the movement of letters between correspondents, rather than simply place letters between correspondents (one way is the usage of the polyphonic model, see below).

## Design process

### Metaphor

Given the enormous amount of (contextual) data produced in various geographical locations over long periods of time, we decided to make use of a comprehensive metaphor suitable for exploration. At first we considered the metaphor of the universe of knowledge not unknown in the history of the organisation of knowledge such as in the historiography of library sciences. However, we soon realized that this metaphor would have an important disadvantage. This metaphor would imply that the Republic of Letters would be one continuous information space in which the parameters (in our case reciprocity in correspondence) with which we try to explain its specific features would be based on one common law. From earlier studies we learned that there are many differences between communities of the Republic of Letters. For that reason we decided for the metaphor of the multiverse of knowledge.

![](/Users/valentina/Google%20Drive/COST%20Packing-up%20sprints%20outcomes%20%5B2018-06%5D/01_Documentation/02_Images/2017_G5%20Images/schema%20galaxy.png)



We understand by a multiverse a hypothetical set of multiple universes that comprise all reality. Each universe had different dimensions and have a different nature i.e. differences in gravity, that we want to explore from various perspectives. The different universes are not alternative or disjunctive: they are complementing each other. This metaphor seemed very apt for the “construct” of the Republic of Letters of which one can claim that is did not exist and existed in multiple version simultaneously. Conceptualizing our model as a single universe would explain less and provide a reductive view of the relationships between elements. In order to explore and to keep track of our journey in the multiverse of the Republic of Letters we introduced a telescope, a space ship and a space ship log book.

![](/Users/valentina/Google%20Drive/COST%20Packing-up%20sprints%20outcomes%20%5B2018-06%5D/01_Documentation/02_Images/2017_G5%20Images/process-01.png)

In order to include and provide the best access to the various dimensions, our model must be flexible and interactive. Each search query may rearrange the configuration of all elements, instead of simply selecting a part of a single configuration. Additionally, it must be possible to jump to other configurations and elements while in the exploration environment.

### Understanding the knowledge management of the VRE

The VRE is based on this matrix adapted from the knowledge management (KM) literature.

![](/Users/valentina/Google Drive/COST Packing-up sprints outcomes [2018-06]/01_Documentation/02_Images/2017_G5 Images/generic framework schema.png)

Ethically, we are interested in the implications of the “Socialization & Sharing” square – we want to visualize the consequences of sharing, the open/closedness of data, and the quality of the data. In reference to the fourth square, “Ideation & Creation”, it should become possible for scholars to contribute to the entries in the VRE. Another possibility is using crowdsourcing. This would make visualizing or otherwise categorizing the quality of the data more pertinent.

![](/Users/valentina/Google Drive/COST Packing-up sprints outcomes [2018-06]/01_Documentation/02_Images/2017_G5 Images/schema explore analysis.png)

In the development we concentrated more on the left side, organizing and analyzing the very diverse content. These are forms of explicit knowledge. Under “Capture & Organization” we consider linking all different repositories, so letters and all the other material generated in reassembling the Republic of Letters can be combined.

The journey of the researcher through our program typically involves these three stages: interaction with the search interface, explore data (structured, unstructured, or metadata), and apply a concomitant analysis. The image illustrates where the tools developed by other groups of the 2017 Como Design Sprint can be incorporated within the VRE. It is important that at any point in this journey, the researcher can easily jump back to the search interface or previous explorations. To enable this, a log of previously visited elements and searches will be kept - the spaceship’s logbook if you will.

### Polyphony

Another metaphor that we explored was the one of polyphony that in the Readbench project was used in the context of topic modeling. The visualization of the movement of letters between correspondents can be enhanced using text-mining tools. The exchange of ideas/concepts and the joint construction of knowledge may be visualised and analysed starting from the polyphonic model.(5) There are two ways in which this model may be used: first, each correspondent is a “voice” that interacts with the voices of the others correspondents. Second, a “voice”, in a generalized way may be an idea, a concept that enters in interaction with other ideas/concepts. In the polyphonic weaving, starting from a metaphor inspired from music, each voice has an important feature of individuality. It enters in inter-animations with other voices through dissonances and consonances (divergences and convergences), driving towards a coherent whole (6). Several visualizations for the polyphonic model may be used, as in the examples below (7).

The below visualizations should be seen as additional to the visualization of the links between sender and receiver (which is already done in the project *Intersecting correspondences*). The two visualizations below come in pairs, one of not so much collaboration (marian, madalin, delia, cristian) and the second with much more interaction (bogdan, Raluca, mares, florin). 

In the first pair of visualizations, the horizontal axis is the time and on the vertical one there are correspondents (marian, madalin, delia, etc). Letters are dots on the line of the sender. If there exist a conceptual link between two letters, a line is drawn between them. The colour of the line is green if there is an explicit link in the more recent letter to the referred one. A red colour indicates an implicit link: the letter does not explicitly mentions the other, but there is an implicit link, for example, when it refers to an idea, a concept of the other letter.

![](/Users/valentina/Google Drive/COST Packing-up sprints outcomes [2018-06]/01_Documentation/02_Images/2017_G5 Images/paper trausan 1.png)



A second example displays the facility of viewing the weaving of threads of ideas. For example, somebody wants to see how an idea or a concept evolved and entered in interaction with other idea/concepts. In this visualization, lines link letters with common topics (ideas/concepts). For each topic a colour is assigned:

![](/Users/valentina/Google Drive/COST Packing-up sprints outcomes [2018-06]/01_Documentation/02_Images/2017_G5 Images/paper trausan 2.png)





[**application-architecture.jpg**]



## **Conclusions**

### Concerns to be addressed

#### Ethics

Some people/institutes/universities might want to share their data in a limited manner. Additionally, it needs to be acknowledged where content originates from. From a scholarly perspective, it would be useful to have some sort of indication of the quality and trustworthiness of the data. Additionally, all parts of the VRE need to be citable and recreatable - taking into account the fact that every time data is added to the ROL, the configuration of the VRE changes accordingly.

#### Uncertainty

A common issue with historical scholarship is that it is not always easy or possible to provide metadata on letters. It bears thought to decide how to make users via the interface aware of faulty, undetermined, or incomplete metadata and data within the VRE.

### Future work

Key figures in the historiography of library and information sciences, such as Vannavar Bush or Joseph C.R. Licklider already more than half a century ago declared that indexing would be far too limited for the disclosure of the deluge of information and that search by association rather than keyword queries better reflect the cognitive processes needed for getting access to the desired knowledge. EMLO, as most databases of the projects that together make the COST-action, is based on structured metadata and will therefore provide only limited access to the textual contents of the future Reassembled Republic of Letters. Combinations with the ePistolarium and Readbench based on text analyses and NLP techniques are necessary to get access to much larger contents of the correspondences and their contextual information in unstructured data. The Linked Open Data paradigm that is explored in EMLO and in other projects such as the ePistolarium is a logical step in a further integration of structured historical data of the Republic of Letters. However, this paradigm has at least two serious flaws. The first one that we already mentioned is that the greater part of the contents of the Republic of Letters cannot be disclosed by structured metadata.

The second flaw is that *Linked Open Data* has notoriously bad user interfaces, i.e. most humanities scholars are not familiar with the complex *SPARQL* languages to query these data. For that reason we need both methods for the disclosure of large quantities of (un)structured textual data and the development of intuitive user interfaces. During the workshop we showed an experiment of an explorative interface based on deep learning, i.e. on the use of arteficial intelligence to reveal “hidden” information in large data sets. In this inspirational experiment deep learning technology was used to group all the paintings of the Rijksmuseum automatically. The result is an interface that allows exploring the paintings more or less on the basis of “genre’s” based on stylistic features.

> Explore by association
>
> Our ineptitude in getting at the record is largely caused by the artificiality of systems of indexing. [...] The human mind does not work that way. It operates by association. With one item in its grasp, it snaps instantly to the next that is suggested by the association of thoughts.
>
> Vannevar Bush –  As we may Think – The Atlantic. July 1945

It seems unlikely that the expected enormous amount of unstructured data of the future Reassembled Republic of Letters can be handled and structured by humans alone. Support by deep learning, similar to the experiment here above is in that sense promising, albeit that it also has the risk of creating a black box of information. However, when one clicks on one of the selected paintings a link is presented. This link can be connected to the structured metadata of the Semantic Web of linked open data, allowing this way to verify the representations of the deep learning orders of knowledge. This experiment demonstrates that the exploring and ordering of the future digitally Reassembled Republic of Letters is not just ‘science fiction” -a term used by one of the less imaginative participants to dismiss our sketch for a future interface-, but a potential solution in which unstructured data can be combined with structured data and in which computers and crowdsourcing can be combined to handle big data in the humanities and beyond.

### Experiences and Recommendations

The second design sprint in Como was once again a success. For the humanities researchers in our workgroup, it was a joy to work together with imaginative designers. Design sprints are developed to come in a step-by-step approach to a concrete result. Four of the five workgroups followed that briefing with convincing results. Our group deliberately choose to stick to our imaginative multiverse metaphor and to sketch a less concrete interface for exploring a future VRE around the Republic of Letters. Generally speaking, the humanities do not have a culture of experimenting, as in the natural sciences. Although the natural sciences can learn much from the humanities, humanities researchers could benefit from this natural-scientific culture to build on experiments of others. Imagination and risk-taking are necessary to take (digital) humanities research further. For that reason we recommend that humanities researchers, computer scientists and designers participating in design sprints do not focus on concrete targets, but leave sufficient space for imagination and experiment. Humanities scholars are hardly ever in the situation to make use of the imagination of designers. It is important to exploit that to full extent. Therefore the “concrete products” after these design sprint week should be sketches and outlines rather than designs and plans; open ideas rather than “solutions” that can be implemented but might miss the wide scope that the humanities need. 



## References

(1) See for instance, John Unsworth, Scholarly Primitives: What Methods do Humanities Researchers have in Common, and How Might our Tools Reflect this?, London 2000; Smiljana Antonijevic, Among Digital Humanists, An Etnographic Study in Knowledge Production, New York 2015 and Ben Fry, ‘The Seven Stages of Visualizing Data’ in Visualizing Data, Boston 2007.

(2) See, C van den Heuvel, Scott B. Weingart, Nils Spelt, Henk Nellen, “Circles of Confidence in Correspondences. Confidentiality in seventeenth-century knowledge exchange in networks of letters and drawings”, Nuncius 31 (2016) 78-106. DOI 10.1163/18253911-03101002 and C. van den Heuvel, ‘Mapping Knowledge Exchange in Early Modern Europe: Intellectual and Technological Geographies and Network Representations’, Internationa Journal of Humanities and Arts Computing 9.1 (2015): 95–114 DOI: 10.3366/ijhac.2015.0140.

(3) This case is based on: ‘Deep networks as associative interfaces to historical research’ Charles van den Heuvel, Ingeborg van Vugt, Pim van Bree en Geert Kessels. Future of Historical Networks Research (submitted, 2017, accepted in press).

(4) C van den Heuvel, Scott B. Weingart, Nils Spelt, Henk Nellen, “Circles of Confidence in Correspondences. Confidentiality in seventeenth-century knowledge exchange in networks of letters and drawings”, Nuncius 31 (2016) 78-106. DOI 10.1163/18253911-03101002.

(5) (Stefan Trausan-Matu, A Polyphonic Model, Analysis Method and Computer Support Tools for the Analysis of Socially-Built Discourse, Romanian Journal of Information Science and Technology 16(2-3), 2013, 144-154, https://www.researchgate.net/publication/259679123_A_Polyphonic_Model_Analysis_Method_and_Computer_Support_Tools_for_the_Analysis_of_Socially-Built_Discourse?ev=prf_pub

(6) 6 Bakhtin, M.M. (1984), Problems of Dostoevsky’s Poetics. Ed. and trans. Caryl Emerson. Minneapolis: University of Minnesota Press.

(7) Trausan-Matu, S., & Dascalu, M. (2015). Visualization of Polyphonic Voices Inter-animation in CSCL Chats. Revista Romana de Interactiune Om-Calculator, 8(4), 305–322. http://rochi.utcluj.ro/rrioc/articole/RRIOC-8-4-Trausan-Matu.pdf



