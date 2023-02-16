---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a 3rd year PhD student in the Algorithms, Combinatorics & Optimization (ACO) program at Carnegie Mellon University, where I am grateful to be advised by [Professor R. Ravi](https://www.contrib.andrew.cmu.edu/~ravi/). My interests lie in approximation algorithms for combinatorial optimization, especially for network design problems. I also like to think about online versions of these problems. In 2020, I received my B.S. in computer science from Georgia Institute of Techology. 

I am very fortunate to be supported for 3 years of my PhD by the NSF Graduate Research Fellowship Program (GRFP) under Grant No. DGE1745016 and DGE2140739. 

In my free time, I am passionate about rock climbing and cooking. I also recently began fostering cats!

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

{% if author.email %}
### Contact:

{{ author.email }}
{% endif %}
