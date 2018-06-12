---
title: "Ideas for “EMLO 2.0”: Digital Critical Editions"
categories:
  - 2017 COST Action
tags:
  - EMLO
  - intuitive visualization of results
  - distant-close reading facility
  - digital scholarly editions
  - usability
  - visibility
  - cross-searchability
toc: true
classes: wide
sidebar:
  nav: "home"
---

*Transforming EMLO into a tool for scholars wishing to conduct research on correspondence from the early modern period*

**Project Leader:** Elena Spadini

**Design Researchers:** Andrea Benedetti, Glauco Mantegari

**Scholars:** Anna Skolimowska, Elena Spadini, Per Pippin Aspaas, Sinai Rusinek

<video controls src="{{ site.url }}{{ site.baseurl }}/assets/images/2016-g1/2016_G1_low.mp4" poster="{{ site.url }}{{ site.baseurl }}/assets/images/2016-g1/image7.png" width="636" autoPlay loop> Sorry, your browser doesn't support embedded videos! </video>

## About the project

The group, consisting of four scholars (Aspaas, Rusinek, Skolimowska, Spadini)
and two designers (Benedetti, Mantegari), has worked on the idea of transforming EMLO into a tool for scholars wishing to conduct research on correspondence from the early modern period, based on text corpora that are available in the most reliable format possible, namely, in digital-born, scholarly, annotated versions.

The outcome of the “sprint run” workshop is a conceptual draft (sketchbook, “mock-up”) for a user interface design to enhance the visibility and usability of such editions for the scholarly community.

## Aim of the project

Study of the early-modern Republic of Letters requires extensive use of correspondence as sources. Reliable editions are fundamental to such research, but are hard to find and to explore. A user interface that would facilitate the use of scholarly, digital editions in particular, is therefore highly needed.

## Case study

The group was assigned with the task of working on visualizations with relevance to digital, scholarly editions. The EMLO database includes, at the time of writing, the metadata for some 125,000 representations of early modern letters. Each letter is catalogued according to the basic metadata (corpus, sender, receiver, place, date, language, reference to archive/hardcopy book in which the letter is found, etc.). Some letters are actually also included in EMLO in the form of encoded, fulltext, scholarly digital editions. However, there is at present no means for the end user to get an overview of which letters are available in such format and which are not.

## Design process

Arguably, scholarly editions are the most solid, reliable foundations for scholarly work on any epoch. They are often invisible in library catalogues and are not likely to be promoted by search engines such as Google Books, either. It would therefore be a good service to the scholarly community if such editions of letters could be made easily visible, in a visualization which allows both *distant reading* and fulltext search across multiple reliable text editions at the same time, and *close reading* in the form of consultation of original texts. Moreover, it is vital for the end user to be provided with the means to move back and forth between the various degree of distant and close reading, without losing track of his or her position in the landscape.

The group has worked on a user interface that allows browsing through the numerous letter collections (*corpora*) that are included in EMLO so far. At a glance, the end user should be able to get an overview of the various corpora and what they actually contain: metadata only, metadata and scannings of original manuscript letters, metadata and scanning of hardcopy publication of letters, metadata and scanning of original plus transliteration of original letters, metadata and scannings plus *scholarly, digital born, TEI annotated* edition of original letters, etc. The various corpus types will be presented graphically with different colours and shapes that should be as intuitive and easy-to-learn as possible. Moreover, the nature of digital edition projects makes the availability of letters in various formats a constantly changing reality, and in order to cater for the needs of a broad scholarly audience it is important to give as much information also on in progress, or partial availability. This will not only better inform, but even facilitate better collaborative work in the community, as the lacunae and needs of the community at large can be assessed by the initiators of both digitization and scholarly editing projects.

The group therefore recommends that EMLO includes yet another category of corpus; namely, letter collections that are known to exist (either in an archive somewhere, or in a hard copy), but which have not yet been inserted into EMLO so far. In this way, the end user will be made aware of their existence, although they will not be possible to search through in the way that the other corpus types are.

The results of search should bring the user to the close reading window, the outline of which was developed as an extendible view. A basic view should contain the text of single document (letter), its main metadata and a navigation bar. Optionally images of the source, apparatus criticus, factual commentary, similia, translation or summary (linked to the paragraphs) and further metadata on the text (its manuscript sources, publications etc.) can appear. A user that chooses to register her- or himself can use a personalized user note-book, in which (s)he can easily copy parts of the text and make and store personal notes. The reader can also easily export his note-book as well as the results of the search.

### Project Diagram
![application architecture]({{ site.url }}{{ site.baseurl }}/assets/images/2017-g4/2017_G4_arch.png)

## Conclusions

- It looks promising, but we have not been able to test how it would actually work.
- Issue raised by Christoph about different IT programs used for each edition: can become difficult to show it on screen easily!
- Even though close reading can be tricky, the distant reading (i.e. new browsing and searching facility) appears possible to implement with a comparatively smaller amount of resources.
