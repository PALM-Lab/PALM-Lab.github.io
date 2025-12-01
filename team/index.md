---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Current Lab Members

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include list.html data="members" component="portrait" filters="role: ^(?!pi|honours_graduate.*|collaborator$)" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Collaborators

{% include list.html data="members" component="portrait" filters="role: collaborator" %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include list.html data="members" component="portrait" filters="role: ^(honours_graduate.*)" %}
