---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{: style="text-align: justify" }
Hi, I'm Mikhail Okunev, 4-th year PhD student in [Brown Visual Computing Lab](https://visual.cs.brown.edu/) advised by [James Tompkin](https://jamestompkin.com/). I'm broadly interested in 3d reconstruction, inverse rendering and dynamic scene representations, especially with a monocular camera.

{: style="text-align: justify" }
I joined academia pretty late in life. In the past I had a career as a research\machine learning engineer in Meta Reality Labs, Meta spam detection team, Microsoft Bing and a Silicon Valley startup. I've been working on a broad range of topics including lightning estimation, foveated rendering, video superresolution, automatic visual anomaly detection, spam & fraud detection, ranking, etc.

{: style="text-align: justify" }
In my free time I enjoy brewing coffee, lifting weights and playing piano.

# Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}