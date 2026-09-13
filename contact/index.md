---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We welcome inquiries from researchers, students, and others interested in our work. Please contact us to discuss potential research collaborations, student opportunities, joining the lab, or general questions about our research.

Prospective students and researchers interested in available positions are encouraged to include a CV and a brief statement describing their background, research interests, relevant experience, and the type of opportunity they are seeking.

{%
  include button.html
  type="email"
  text="anthony.ruberto@med.fsu.edu"
  link="anthony.ruberto@med.fsu.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/bpQLC8XvyKm2aZ2r5"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/FSU-com.jpg"
  caption=" "
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption=" "
%}

{% endcapture %}

{% include cols.html col1=col1 %}

{% include section.html dark=true %}

{% capture col1 %}
Department of Biomedical Sciences |
College of Medicine
{% endcapture %}

{% capture col2 %}
Florida State University
{% endcapture %}

{% capture col3 %}
1115 West Call Street |
Tallahassee, FL 32306-4300
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
