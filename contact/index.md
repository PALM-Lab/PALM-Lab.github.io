---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please feel free to reach out to us about anything regarding the PALM Lab using the buttons below.

{%
  include button.html
  type="email"
  text="william.ngiam@adelaide.edu.au"
  link="william.ngiam@adelaide.edu.au"
%}
<!-- {%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%} -->
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps"
  link="https://maps.app.goo.gl/kTkw41dMzQ6ExrKn9"
%}

{% include section.html background="images/background.jpg" dark=true %}

<!-- {% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
