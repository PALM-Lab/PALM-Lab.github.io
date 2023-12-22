---
---

# Welcome!

This is the website for the **P**erception, **A**ttention, **L**earning and **M**emory Lab in the School of Psychology at the University of Adelaide. We are a cognitive psychology and neuroscience lab studying how humans store and hold visual information in mind, headed by Dr William Ngiam.

{% include section.html %}

## Highlights

{% capture text %}

Our research publications with the associated preprint, data and code here:

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Publications"
  text=text
%}

{% capture text %}

Current research projects in the lab here:

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Meet our team of researchers!

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
