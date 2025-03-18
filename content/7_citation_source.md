---
title: Citation by Source Visualization
nav: Citation by Source
gallery: true
---

<br>

- Node (circle) size indicates number of times a work is cited
- Node color indicates keyword and subject similarity
- Links and clustering indicate shared citations

**Usage**: Through visualizing shared citations within the top publishers of CALS scholarly output, we can see not only the top producers but also see which publishers release a wider array of scientific focuses and which ones have a more specific lens.

{% capture modal1 %}

Beginning with the top right hand corner of the screen, select the __frame icon__ to enter full screen, the __sun icon__ if you prefer a light background, the __camera icon__ to download a screenshot and the last three to share, save a version and open the JSON file of the visualization.

<img src="https://objects.lib.uidaho.edu/twrs/how_to_a.gif"  class="img-fluid" alt="Instructional gif demonstrating functionalities of VOSviewer" >

Hover over (or select it to keep open) a node (circle) to highlight work that it's connected to either in citation, co-authorship or attribute depending on which of these you explore. This will also reveal an information panel on the bottom of the screen that will provide the __author(s), title, source, year__ and __total number of times that work was cited__ in subsequent research papers. If a copy of the research paper is available, select the blue URL on the right hand side of the information panel to open this up in a new window.

<img src="https://objects.lib.uidaho.edu/twrs/how_to_b.gif"  class="img-fluid" alt="Instructional gif demonstrating selecting nodes, reading instructional panes and exploring individual research papers" >

Data may be hidden by larger nodes, so use the control panel on the right hand side or your scroll wheel on a mouse to zoom in.

<img src="https://objects.lib.uidaho.edu/twrs/how_to_d.gif"  class="img-fluid" alt="Instructional gif demonstrating zooming in and out" >

{% endcapture %}

{% include feature/modal.html button="Need Help?" color="info" title="Configuration" size="xl" text=modal1 %}

<iframe
  allowfullscreen="true"
  src="https://app.vosviewer.com/?json=https://drive.google.com/uc?id=1QiFfEE1WuYZPkdWQcCfCop7n0jvqJdC_&dark_ui=true&scale=1.7&item_size=2"
  width="100%"
  height="100%"
  style="border: 1px solid #ddd; max-width: 1200px; min-height: 500px"
>
</iframe>
