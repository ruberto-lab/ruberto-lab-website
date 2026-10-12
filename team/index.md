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
