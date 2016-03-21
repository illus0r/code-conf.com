---

brand-txt: >
  *CO*DE-CPH
title: CODE-CPH
color: '#3c890f'
subtitle: >
  *Co*ntinuous *De*livery and *DevOps* Conference - Copenhagen

# events header

event_header:
  img: /images/code-cph-audience.png
  ribbon: 3rd year in CPH...

# date & location

date_: 2016-09-13
time: 09—17:00
city: Copenhagen
adress: Copenhagen Marriott Hotel, Kalvebod Brygge 5, 1560 Copenhagen V, Denmark

checkout:
  eventbriteid: 23441015709

keynote-speakers:
  januhagen:
    title: Continuous Delivery - Lessons from the Aviation Industry
    abstract: >
      Assuming that Continuous Delivery is the solution to your problems Jan will explore - through various stories - which character traits should be present in your team members if they are to build and deliver cutting edge software. He will touch on how to build such a team. A non-technical keynote for anyone who is managing, or is a member of, a team who are trying to implement continuous delivery.
  jejensen:
    title: Continuous Delivery and DevOps at Lego
    abstract: >
      For the past 4 years Jørn Erik has focused on implementing Continuous Delivery and DevOps processes and practices in development, quality and operations at Lego.

speakers:
  lakruzzmeekrosoft:
    title: CoDe - The Metaphors We Live By
    abstract: >
      Having our hands buried deep into DevOps and CoDe every single day, we tend to expand our vocabulary and lingo with metaphors, proverbs and anecdotes that enables us to understand and explain our domain. Mike and Lars will cover tales in the range from Tarantino's Pulp Fiction to Indonesia's stone age population.
  andrewjturner:
    title: Automation & Continuous Delivery – Lessons from the Front Line
    abstract: >
       Continuous Delivery is on the C-Level agenda and so it should be – it’s a game changer for IT change. But how do you prioritize what to do and align your stakeholders to get the most from the opportunity? Automation provides the foundation for continuous delivery, and learning from real life customer experiences across regulated industries is an excellent way to accelerate your adoption.
  ethomson:
    title: To Be Announced
    abstract: >
      To Be Announced

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
keynotes=page.keynote-speakers
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
subcaption="A heart felt thank goes to our friends"
css_classes="" %}
