---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I recently graduated with my Ph.D. from the Algorithms, Combinatorics & Optimization (ACO) program at Carnegie Mellon University, where I was fortunate to be advised by [Professor R. Ravi](https://www.contrib.andrew.cmu.edu/~ravi/). My interests lie in operations research and approximation algorithms for combinatorial optimization, especially for network design problems. I also like to think about algorithms to solve these problems under future uncertainty, such as in online resource allocation. In 2020, I received my B.S. in computer science from Georgia Institute of Techology. 

I am very grateful to have received 3 years of funding for my PhD from the NSF Graduate Research Fellowship Program (GRFP) under Grant No. DGE1745016 and DGE2140739. 

In my free time, I am passionate about rock climbing, mountaineering, and cooking/baking delicious food. 

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

{% if author.email %}
### Contact:

{{ author.email }}
{% endif %}
