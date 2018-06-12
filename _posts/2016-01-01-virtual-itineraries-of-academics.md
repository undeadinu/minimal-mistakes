---
title: "VIA - Virtual Itineraries of Academics"
categories:
  - 2016 COST Action
tags:
  - Travels
  - Early Modern
  - Republic of Letters
  - Academic Culture
  - Academia
  - Universities
  - Scholars
  - Intellectual Geography
  - Intellectual History
  - History of Science
---

*Exploring early modern academic travel culture.*

**Project leader:** Mikkel Munthe Jensen

**Scholars:** Mikkel Munthe Jensen, Joëlle Weis

**Design researchers:** Gabriele Colombo, Marco Quaggiotto

<video controls src="{{ site.url }}{{ site.baseurl }}/assets/images/2016-g1/2016_G1_low.mp4" poster="{{ site.url }}{{ site.baseurl }}/assets/images/2016-g1/image7.png" width="636" autoPlay loop> Sorry, your browser doesn't support embedded videos! </video>

## About the project

The project which was brought to the workshop had the initial aim of exploring the geo-academic reach of 18th-century Nordic scholars and to what extent this learned space changed during the century according to scholarly disciplines; i.e. combining geography and chronology with certain attributes. The project’s research question and the data was provided by and based on Mikkel Munthe Jensen’s research on academic travels of Nordic university professors in the Early Modern period.
We approached the project by asking: what would the ideal visualisation of the data, with no regards to time and resources, look like? This initiated a brainstorming process which allowed the two scholars of the group to express and discuss their needs as well as their wishes with the digital designers - a process that proved very fruitful for the development of the final output. By discussing the ideal scenario, we realised that instead of a ‘simple’ geographical visualisation of travels based on time and one attribute (scholarly discipline), a visualisation tool that helps to explore the many aspects of early modern travels, was in high demand.
Our aim with the workshop was therefore to create a visualisation tool that would allow you to explore data on early modern academic travels through several parameters; geography (space), chronology (time) and a variety of prosopographical and travel-related attributes. All of these parameters would be interconnected and thus change according to their selection. This would grant the scholar the possibility to explore his or her data in multifarious ways that normal statistical and geographical visualisation would not allow. Such a tool would thus allow scholars to explore, examine and analyse bigger datasets which would lead to new insights into early modern travel culture and beyond.

## Aim of the project

Explore and visualise the relationship between geography (space), chronology (time) and a variety of prosopographical attributes in the context of early modern academic travels.


## Case study

The data provided were:

#### Geography (Space)

- Cities visited
- Countries visited

#### Chronology (Time)

- Period of travel (start and end date)

#### Prosopographical attributes

- Institutional affiliation
- Scholarly division - subdivided in chairs
- Funding - subdivided in specific funding schemes (e.g. specific scholarship)
- Age at travelstart
- Before/After appointment
- Before/After doctoral degree
- Confession (IV)
- Language (IV)

## Design process

The design of the visualisation tool’s interface is based on the three main categories explained in the previous section, thus dividing the interface into three main blocks: 1) Geographical frame (Placement: main field), 2) Chronological frame (placement: bottom), and finally 3) the attribute frame (Placement: left side).

#### Geographical frame

The geographical frame shows the map view and travel destinations visited (cities). The map is zoomable and will appear as a heat (density) map when zoomed out and as a point map when zoomed in.
Design functionalities:

- Ideal Version: When a city is selected, it will open a small window listing the academic travellers, local learned institution and other local scholars
- Ideal Version: Selected travels, where only data on the country exist, would be shown in a separate box (e.g. France + the number of travels)
- Ideal Version: It should be able to add political, linguistic and confessional borders.
- Ideal Version: The possibility to select other views (visualisations) than only geographical views, e.g. such as cluster visualisations.

#### Chronological frame

The chronological frame shows a time axis divided in years, where certain time periods can be chosen. Ideal Version: Along the time axis important major events could be placed in the time frame above the  ‘worms’ (e.g. The Seven Year War 1756-1763).

First challenge: Time spans

-  A major challenge in the project was that the data only provides time span and not specific dates for each individual visit. For instance, we only have data that a academic traveller travelled in a certain period (e.g. 1713-1717) and visited a certain number of cities (e.g. Leiden, Utrecht, Halle, Jena etc.) but not when.
- To be able to use a chronological frame based on time spans, a new form of visualisation was created, in which each travel was represented by stacked lines resembling ‘worms’.
- In addition, this has the benefit of working as a graph by showing the development of travels.

Second challenge: Uncertain start and end dates

- A second challenge was uncertain or missing start and end dates. To combat this each uncertain ‘worm’ would fade in or fade out in the adjacent years, thereby indicating the uncertainty for the reader.

#### Attribute frame

The third and final frame consist of smaller filter visualisations; i.e. bars, boxes and minor maps.

First challenge: Simultaneous view of more filters

- As there are many filters it is difficult to view them all at the same time. The best option was to have a scroll down option, where the highest prioritised data would appear at the top.

Link to [demo version](https://drive.google.com/open?id=0B3X8CNVByqGvOGxvTC1WTFNmZXM)

#### Project Diagram
![application architecture]({{ site.url }}{{ site.baseurl }}/assets/images/2016-g3/2016_G3_arch.png)

## Conclusions

The result of our work is a model for a specialised tool that would help researchers to explore their data on many different levels and in any combination. This will allow the researcher both to conduct faster analysis and to be able to see otherwise unclear pattern in the data, all which would not have been possible in normal standardised tools.

The big advantage of this tool is the easy legibility as it uses well-known and intuitive functions. Especially the combination of many filters, which for themselves represent small innovations, allows the user to explore the data in new ways. This is a big additional benefit to existing tools for the researcher that works on a very specific kind of data. As an example for this, we might especially cite the timeline, which can capture time spans and their overlaps at first sight, thus also working as a graph showing the total development of travels through time. Moreover, the timeline will take into account the most important events in European history for the given time, which will facilitate a recognition of correlations with the travelers behaviour. Another innovative feature is the possibility to get further information on the cities that people traveled to. When clicking on a city, a window would pop up that includes information on institutions and local scholars.

Summing up, this tool meets the needs of the involved scholars in an extraordinary way as it contains so many features that would allow to gain another perspective on the given data.

The goal of the workshop was to bring together humanists and designers to see them working on a common task. Accordingly, the work that was done in five days is certainly the result of a fruitful collaboration between designers and scholars. Especially the first two days were extremely insightful and beneficial for both sides. On the one hand, the scholars were given time and were encouraged to really learn how to express their wishes and needs. On the other hand, it was an exercise for the designers to listen and understand. All in all, it was the mutual understanding that was in the focus of the week spent together and what made it a very eye opening experience.

Our final result can serve as input for further development of visual exploration tools of prosopographical data - not only travels, but all kinds of group related data. This way of data exploration has to be considered as a basic first step towards getting an overview on research data. Specific correlations can easily be identified which allows the researcher to do further investigations in this direction. In the long term, this would consequently result in more specific visualisation solutions, which could of course also be used to communicate findings to a broader public.

Further research would definitely focus on an underlying database and user friendliness. The final goal would be to create a tool that could be easily used by researchers without obstacles, primarily by lowering the inhibition threshold. What is more, the timeline view would have to be further developed in order to fit the requirements of showing parallel travels and uncertainties at the same time. Another idea that could be further pursued was showing total travel distances and approximate travel costs (cf. Orbis).

In regard to the general objectives of the COST Action `Reassembling the Republic of Letters`, we can assert that this project would collaborate to both the technical and the historiographical agenda. The realisation of this project would allow data navigation, analysis and visualisation of big amounts of prosopographical data not only concerning travels but even also other important events and stages in life. When further developed, this tool would be especially appropriate for much of the metadata that can be collected both from epistolary as well as prosopographical sources. It would be a big step for researchers to be able to infer how different people could have met at different places by being there at the same time, just by using the tool. In the end, this would mean that we could be able to visualise relationships between people and also institutions. This would be highly interesting for the historiographical agenda, as the newly found information would help us gain new perspectives, generate new research questions, as well as answer already existing questions concerning the Republic of Letters.
