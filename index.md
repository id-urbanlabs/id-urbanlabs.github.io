---
---

**UrbanLabs** focuses on urban systems and spatial analytics, with emphasis on data-driven planning, sustainability, and equitable development.

Our team collaborates with national ministries, research institutes, and international organizations, working at the intersection of policy, technology, and urban transformation.

{% include section.html %}

#### Our work
{% include project-carousel.html %}

{% include section.html %}

#### Our news

{% include news-list.html style="simple" limit=5 prefix="home-" hide_hidden=true %}

{%
  include button.html
  link="news"
  text="View all news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

#### Our priorities

{% include list.html component="card" data="themes" style="small" %}

{% include section.html %}


#### Our publications

{% include list.html data="citations" filters="group: featured" hideyear="true" component="citation" %}

{%
  include button.html
  link="research"
  text="All publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}


{% capture text_team %}

Our team collaborates closely with other research groups, government agencies, and development partners, creating a strong ecosystem for impactful urban research.

**Join us**: We welcome researchers, practitioners, and students interested in urban development, data, and policy. Opportunities for collaboration and internships are available.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{%
  include button.html
  link="apply"
  text="Join us"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{% include section.html %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our team"
  style="bare"
  text=text_team
%}




{% include section.html %}
