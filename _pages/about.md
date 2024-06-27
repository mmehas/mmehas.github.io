---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Mikhail Okunev, 4-th year PhD student in Brown Visual Computing Lab advised by James Tompkin. I'm broadly interested in 3d reconstruction. Most recently my research was about accurate reconstruction of motion with dynamic NeRFs and cToF cameras.

In the past I had a career as a research\machine learning engineer in Meta\Reality Labs, Microsoft and a Silicon Valley Startup. I've been working on a broad range of topics including lightning estimation, foveated rendering, video superresolution, automatic visual defect detection in electronics, spam\fraud detection, ranking, etc.

In my free time I enjoy brewing coffee, running\lifting and playing piano.


# Add a 'publications' page's content here

{% assign publications = site.pages
    | where:"permalink", "publications" 
    | first %}

{{publications.content}}