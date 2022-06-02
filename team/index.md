---
title: Team
nav:
  order: 3
  tooltip: About our team
redirect_from:
  - /lab-members
  - /alums
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>Team

We are an interdisciplinary team!

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: mphil, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{:.center}

{% include section.html %}

## Join

<span style="color:red">We are always looking for new team members! If you are interested in joining us or collaborating, please reach out to Dr. Yang Lu to inquire about available (Postdoc/Ph.D./RA/Intern) opportunities! </span>

{% include link.html type="external" link="https://docs.google.com/document/d/1Q06LiTatuG2nvpEceSAYIqQo-G9nKA5_JmNCcRSX1bU" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mphil, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{:.center}

{% include section.html %}

## Funding

Our work is supported by
{:.center}

{%
  include gallery.html
  style="square"

%}
