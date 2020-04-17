---
layout: single
title:  "Thinking about graphs part I"
date:   2020-04-17 08:30:35 -0400
categories: [computer science]
bokeh: true
tags: [graphs, comp sci, educational]
---

There are a number of concepts every computer science student should have under their belt. Data structures such as maps, trees, lists, arrays, and what-have-you. I'd say that I have a pretty good understanding of these fundamentals. But there is one concept. A concept so sinister, vile, baneful, and all of the other nasty words to describe nasty things, that I have not dared to stare it in the face until now. That's right. I'm talking about 

## ***Graphs***

In an effort to stop being scared of the monster under my bed. This series aims to get under the bed and give that monster a mean noogy and maybe even become idk... best buds? :)

In other words, here's graph theory from the ground up. [^bookplug] 

[^bookplug]: As a reference, I'll using Nora Hartsfiled's amazing text ["Pearls in Graph Theory"](https://www.amazon.com/Pearls-Graph-Theory-Comprehensive-Introduction/dp/0486432327).

# **Know Thy Enemy**
So what is a graph anyway? Well a graph is simply a data structure consisting of __vertices__ and __edges__.
* __Vertices__ - These are the nodes of the graph.
* __Edges__ - The connections between vertices. These connections sometimes have a weight to them, but don't worry about that for now.
{% include 2020/04-17/simplegraph.html %}
