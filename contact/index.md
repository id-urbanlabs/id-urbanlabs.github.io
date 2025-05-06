---
title: Contact
nav:
  order: 9
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Feel free to reach out to us for inquiries, collaborations, or further information about our work. Whether you're interested in urban research, data partnerships, or student opportunities, we're happy to connect. 

- Main office: 8th Floor, Menara Bappenas, Jl. H. R. Rasuna Said Kav. 2–4, Jakarta Selatan
- Working space: 1st Floor, Wisma Kodel, Jl. H. R. Rasuna Said Kav. B4, Jakarta Selatan
- Meeting venue (as needed): Gedung Bappenas - Menteng, Jl. Taman Suropati No. 2, Jakarta Pusat


{%
  include button.html
  type="email"
  text="id.urbanlabs@gmail.com"
  link="id.urbanlabs@gmail.com"
%}

{%
  include button.html
  type="address"
  text="Menara Bappenas - Kuningan"
  link="https://maps.app.goo.gl/VjHEKm3J2L9huYPT9"
%}

{%
  include button.html
  type="address"
  text="Wisma Kodel - Kuningan"
  link="https://maps.app.goo.gl/NYxrXFu5YGU1i3HA6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/bakrie-pic.png"
  caption="Menara Bappenas Kuningan"
  link="https://maps.app.goo.gl/VjHEKm3J2L9huYPT9"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/kodel-pic.png"
  caption="Wisma Kodel Kuningan"
  link="https://maps.app.goo.gl/NYxrXFu5YGU1i3HA6"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
