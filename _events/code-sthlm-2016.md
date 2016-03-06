---
#permalink: /code-sthlm-2016.html
brand-suffix: STHLM
title: CODE-STHLM
color: '#660066'
price: Sold out!
subtitle: >
  *Co*ntinuous *De*livery and *DevOps* Conference

# events header

event_header:
  img: /images/code-sthlm-2016.jpg
  ribbon: Join us for...

# date & location

date_: 2016-08-18
time: 09—18:00
city: Stockholm
adress: Tordenskiolds gate 3, 0160 Oslo. Mesh

checkout:
  price: 200
  eventbriteid: 21382334137

speakers:
  allanebdrup:
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
  lakruzz:
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
  markcoleman:
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
---

{% include event-main.html  background-image=page.event_header.img dot-text=page.price brand-lead=page.event_header.ribbon brand-suffix=page.brand-suffix caption=page.subtitle color=page.color %}

{% include date-location.html color=page.color date=page.date_%}

{% include speakers.html %}
{% include keynote-speakers.html %}

{% include eventbrite-ticket-form.html  eventbriteid=page.checkout.eventbriteid %}
