---
title       : Summary of Michael Ashworth's "Identifying Key Contributors to Performance in Organizations"
subtitle    : The case for knowledge-based measures
author      : C.W. Dillon
job         : CSS739 Computational Org Theory
framework   : revealjs     # {io2012, html5slides, shower, dzslides, ...}
revealjs    :
  theme: solarized    # {sky, beige, simple, serif, night, default, solarized, moon}
  transition: cube    # {none, page, concave, zoom, linear, fade, default}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      #  {tomorrow, zenburn, ... }
widgets     : [bootstrap,mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

### Summary of Michael Ashworth's "Identifying Key Contributors to Performance in Organizations"
   
</br>   
   
* * * * 

The Case for Knowledge-based Measures


* * * * 
  
</br>
</br>
   
<small> 
[CW Dillon](http://www.css.gmu.edu/?q=node/15) 

for _Computational Org. Theory_, CSS739

Spring 2014

George Mason University
</small>


*** =pnotes

I am a PhD student in the Department of Computational Social Sciences, at the Krasnow Institute for Advanced Studies. We focus primarily on neurosciences and applications of complexity theory from a behavioral perspective. This seminar, by Dr. Maksim Tsvetovat focuses on computational models of organization theory as a special kind of social network analysis.

--- .class #id 

### Results

>Traditional social network measures are generally correlated with employee criticality but they do not always identify critical employees when task assignment and knowledge are taken into account. (p.6)

--- &vertical

### Approach

* 16 people on a software dev team
* Calculate network metrics
* 1,700 simulations of _team_ performance
 - 100 runs each case
 - Base case
 - Each case where one member is missing
* Compare to ''typical'' measures alone and combined 
* Simulations validate the SNA metrics

***

### Team Network

* 16 people on a software dev team
 - Leader (1)
 - Manaagers (2)
 - Supervisors(4)
 - Engineers (9)
* Edgelist is 36 x 2, undirected

***

###

TODO {embed image of network or build one}

***

--- &vertical

### Metrics

* Rely on a model of sub-matrices 
* Degree Centrality Index
* Degree Betweenness Index
* Task Exclusivity Index
* Knowledge Exclusivity Index
* Knowledge Access Index

***

### Degree Centrality Index

$$
 X \in {0,1}
$$


***

### Degree Betweenness Index

$$
 X \in {0,1}
$$

***

### Task Exclusivity Index  (TEI)

$$
 X \in {0,1}
$$

***

### Knowledge Exclusivity Index (KEI)

$$
 X \in {0,1}
$$

***

### Knowledge Access Index (KAI)

$$
 X \in {0,1}
$$

***

---

### Results

* Traditional heuristic
 - Combine CId with CIb
 - 3 false negatives and 2 false positives
* Knowledge heuristic
 - Combine TEI, KEI and KAI
 - 1 false negative 



