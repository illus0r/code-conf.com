---
#permalink: /code-sthlm-2016.html
branding: >
  *CO*DE*-*STHLM
title: CODE-STHLM
color: 660066
price: Sold out!
time: 09—18:00
subtitle: Continuous Delivery and DevOps Conference

# events header

event_header:
  img: /images/code-sthlm-2016.jpg
  ribbon: Join us for...

# date & location

date_: 25.06.2016
city: Oslo
adress: Tordenskiolds gate 3, 0160 Oslo. Mesh

checkout:
  price: 200
  eventbriteid: 21382334137

speakers:
  meekrosoft:
    text:  Mike will tell about all the things.
  lakruzz:
    text:  Lars will tell about all the things.
  andimann:
    text: >
      By enabling new approaches to service delivery, cloud and DevOps together are delivering even greater speed, agility, and efficiency. No wonder leading innovators are adopting DevOps and cloud together!
      This presentation will explore the synergies in these two approaches, with practical tips, techniques, research data, war stories, case studies, and recommendations.

      Whether you are a startup or an enterprise; using private cloud, public cloud, or no cloud; an Agile noob or a DevOps pro; struggling with core banking systems, or building a new social/local/mobile app that will change the world (!); this session will give you actionable ideas on using cloud and DevOps together to revolutionize your software and service delivery lifecycle.
---

{% include event-header.html %}
{% include date-location.html %}
{% include speakers.html %}

{% include eventbrite-ticket-form.html eventbriteid=page.checkout.eventbriteid %}
