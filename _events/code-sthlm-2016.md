---
#permalink: /code-sthlm-2016.html
branding: >
  *CO*DE*-*STHLM
title: CODE-STHLM
color: 660066
price: Sold out!
time: 09—18:00
subtitle: >
  *Co*ntinuous *De*livery and *DevOps* Conference

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
  allanebdrup:
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
  lakruzz:
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
  markcoleman:
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
---

{% include event-main.html
  background-image=page.event_header.img
  dot-text=page.price
  brand-lead=page.event_header.ribbon
  brand-suffix="STHLM"
  caption=page.subtitle
%}

{% include date-location.html %}

{% include speakers.html %}
{% include keynote-speakers.html %}

{% include eventbrite-ticket-form.html
  eventbriteid=page.checkout.eventbriteid
%}
