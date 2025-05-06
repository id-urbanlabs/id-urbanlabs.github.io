---
title: Contact
nav:
  order: 9
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Feel free to reach out to us for inquiries, collaborations, or further information about our work. Whether you're interested in urban research, data partnerships, or student opportunities, we're happy to connect.

{%
  include button.html
  type="email"
  text="id.urbanlabs@gmail.com"
  link="id.urbanlabs@gmail.com"
%}

{%
  include button.html
  type="Address"
  text="Gedung Bappenas - Menteng"
  link="https://maps.app.goo.gl/D2EL5JzcuSdmgEbPA"
%}

{%
  include button.html
  type="Address"
  text="Menara Bappenas - Kuningan"
  link="https://maps.app.goo.gl/VjHEKm3J2L9huYPT9"
%}

{%
  include button.html
  type="Address"
  tooltip="Wisma Kodel - Kuningan"
  link="https://maps.app.goo.gl/NYxrXFu5YGU1i3HA6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/menteng-pic.png"
  caption="Gedung Bappenas Menteng"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/bakrie-pic.png"
  caption="Menara Bappenas Kuningan"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/kodel-pic.png"
  caption="Wisma Kodel Kuningan"
%}

{% endcapture %}
{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% include section.html dark=true %}

<div style="text-align: left;">
  
  {% capture col1 %}
  **Gedung Bappenas - Menteng**  
  Jl. Taman Suropati No.2, Jakarta Pusat  
  Primarily used for high-level meetings and strategic coordination.
  {% endcapture %}

  {% capture col2 %}
  **Menara Bappenas - Kuningan**  
  Jl. H. R. Rasuna Said Kav. 2-4, Jakarta Selatan  
  Home to various technical teams, directorates, and co-working spaces.
  {% endcapture %}

  {% capture col3 %}
  **Wisma Kodel Working Space**  
  Jl. H. R. Rasuna Said Kav. B4, Jakarta Selatan  
  A flexible space for collaboration, innovation, and internships.
  {% endcapture %}

  {% include cols.html col1=col1 col2=col2 col3=col3 %}
  
</div>
