---
layout: post
title:  "Mapping the 'Fiscal Policy Space'"
date:   2018-03-01 12:53:02
image: /assets/peer-cities.png
involvement: "design + development"
---

<p class="date" markdown="1">
March, 2018
</p>

This unpublished project was meant to be a simple view of stats for cities that share a similar [Fiscal Policy Space](http://fiscalpolicyspace.greatcities.uic.edu/). However, the team encountered some issues defining what it means to be a "peer city" through this novel set of statistical measures and we canned the approach.

For me the project was still a success because it marks the first time I created a fully responsive map inside an iframe.

H/t the great crew at NPR Visuals, I riffed on (stole) your table styles.

{% raw %}
  <div>
    <div id="iframe-here"></div>
  </div>
  <script src="https://pym.nprapps.org/pym.v1.js" type="text/javascript"></script>
  <script>
      var pymParent = new pym.Parent("iframe-here", "https://s3.amazonaws.com/peercities/index.html", {});
  </script>
{% endraw %}
