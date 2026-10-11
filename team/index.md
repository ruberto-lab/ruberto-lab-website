
---
title: Team
nav:
  order: 3
  tooltip: About our team
---

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %} Team

The Ruberto Lab is an interdisciplinary team dedicated to understanding the biology of eukaryotic parasites and developing new therapeutic strategies for parasitic infectious diseases. We foster a collaborative and supportive research environment that values scientific curiosity, rigorous research, and the professional development of every team member.

## Current Lab Members

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html dark=true %}

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Interested in joining us?"
  link="https://www.rubertolab.com/contact/"
  style="button"
%}

{% include section.html %}

## Alumni

<!--
This section is reserved for former lab members.
Add alumni profiles here when applicable.
-->

{% include section.html %}

## Funding

We gratefully acknowledge support from the National Institutes of Health (NIAID) and Florida State University.

{% capture content %}

[![National Institutes of Health](https://upload.wikimedia.org/wikipedia/commons/a/a6/NIH_2013_logo_vertical.svg?utm_source=en.wikipedia.org&utm_campaign=index&utm_content=original)](https://www.nih.gov/)

[![Florida State University](https://upload.wikimedia.org/wikipedia/en/6/6b/Florida_State_University_seal.svg)](https://www.fsu.edu/)

{% endcapture %}

{% include grid.html content=content %}
