---
layout: page
title: Leadborghini : Jim Sidler : Ruby on Rails Software Engineer
description: Ruby on Rails project built to digest education leads via a SOAP API.
group: project
---
{% include JB/setup %}

[Home](http://jimsidler.com) : [All Projects](http://jimsidler.com/projects.html)

Leadborghini is a private web service without a graphical interface other than the admin interface. This application opens one URL to the public where it accepts leads posted by contracted vendors. After going through a series of validations, Leadborghini sends an XML response stating if the lead was valid or not along with error explanations. If the lead is valid, it is stored and submitted asynchronously to the proprietary call center application via SOAP.

Built in Rails 3.0.3, this application replaced a lot of manual tedium. HTML5 (HAML), SCSS, JQuery, SOAP, XML and a RESTful API all hosted on [Heroku](http://heroku.com)