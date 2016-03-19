---
#permalink: /code-sthlm-2016.html
brand-txt: >
  *CO*DE-STHLM
title: CODE-STHLM
color: '#780068'
color-name: purple
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

keynote-speakers:
  markcoleman:
    title: lkjawldjsalj lkj
    abstract: >
      In this talk we will assume that continuous delivery is the solution to your problem and will discover through various stories which character traits should be present in your team members if they are to build and deliver cutting edge software. We will conclude with suggestions on how to build such a team.This is a non-technical talk for anyone who is managing, or is a member of, a team who are trying to implement continuous delivery.
  andimann:
    title: blaha
    abstract: >
      By enabling new approaches to service delivery, cloud and DevOps together are delivering even greater speed, agility, and efficiency. No wonder leading innovators are adopting DevOps and cloud together! This presentation will explore the synergies in these two approaches, with practical tips, techniques, research data, war stories, case studies, and recommendations.

speakers:
  allanebdrup:
    title: Continuous Delivery War stories - deploying 10 times per day
    abstract: >
      How to do Continuous Delivery and deploy to production 10 times a day or more. The techniques in the talk can be used no matter if you are on an Open Source technology stack or not.
  lakruzz:
    title: NoOps - beyond DevOps
    abstract: >
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
  meekrosoft:
    title: Continuous Delivery War stories - deploying 10 times per day
    abstract: >
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip

sponsors:
  - container_solutions
  - delphix
  - serena
  - xebia_labs

---

{% include event-main.html
background-image=page.event_header.img
dot-text=page.price
brand-lead=page.event_header.ribbon
brand-txt=page.brand-txt 
subtitle=page.subtitle
color=page.color %}

{% include date-location.html
color=page.color
date=page.date_
time=page.time
city=page.city %}

{% include speakers.html
speakers=page.speakers
color=page.color
css_classes="colored toprip botrip"
caption="The speakers" %}

{% include eventbrite-ticket-form.html
eventbriteid=page.checkout.eventbriteid
css_classes="black toprip botrip" %}

{% include sponsors.html
sponsors=page.sponsors
caption="Sponsors"
subcaption="Sell to be added here for sponsors etc."
css_classes="" %}
