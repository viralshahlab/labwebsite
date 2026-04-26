---
title: Science
nav:
  order: 2
  tooltip: See what Science we do
---

# {% include icon.html icon="fa-solid fa-flask" %}Science

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% capture text %}

We recently discovered the function of a new airway stem cell called the hillock. The hillock survives severe injury. The stem cells within the hillock then proliferate and regenerate the airway surface, differentiating into all the different airway epithelial cell types. Image shows a video of hillock cells in magenta, surviving severe injury, expanding, migrating and regenerating the airway surface. 

{% endcapture %}

{%
  include feature.html
  image="images/hillock expansion.gif"
  title="Hillocks Survive Injury and Expand"
  text=text
%}

{% capture text %}

The major question is that after hillock regeneration, is airway physiology restored? We investigate various physiologic outputs like mucociliary transport, ion transport, and bacterial killing to assess whether these critical physiology outputs function normally. As an example, you see mucociliary transport captured by particle transport moving in an abnormal "hurricane". Our lab assesses physiology and then deciphers the cell biology and molecular mechanism underlying this dysfunction. 

{% endcapture %}

{%
  include feature.html
  image="images/Hurricane_small.gif"
  title="Do Hillocks Regenerate Physiology?"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are building something here that is bigger than any single paper or discovery. We are training the next generation of scientists. This lab runs on genuine collaboration: we push each other's thinking, cover each other's blind spots, and celebrate each other's wins as our own. Mentorship flows in every direction because we believe that a team that invests in each other produces better science and better scientists than any individual working alone ever could. Everyone who leaves this lab will be ready to ask bold questions, do rigorous work, and make a difference.

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  title="Targeting the Hillock for Gene Therapy"
  text=text
%}
