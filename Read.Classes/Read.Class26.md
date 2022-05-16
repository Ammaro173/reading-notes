# Read: class 26 (Django )

---

> [Back to Home](../README.md)

---

> [references](https://wsvincent.com/how-django-works-behind-the-scenes/)

## How Django Works Behind the Scenes?

> What is it?

        Django is a Python-based web framework used by millions of developers and billions of consumers through popular apps like Instagram. It is open source, meaning the code is available for free on Github and can be downloaded onto any developer’s computer and used alongside the official documentation. However, I find that even professional Django developers have little insight into “how” Django is actually run, both technically and legally/financially, so this post is my attempt to provide a concise overview of it all.

> Django was originally developed at the Lawrence Journal-World newspaper by Adrian Holovaty, Simon Willison, and Jacob Kaplan-Moss. The code was open-sourced in 2005 and developers immediately started making contributions to the codebase. Fourteen years later, Django remains under active development, with new major releases every nine months, minor security releases almost monthly, an official issue tracker, and robust discussion on the django-developers Google group.

## Technical Organization

Technical Organization
The DSF handles legal, financial, and administrative matters for Django. But there is a separate organizational structure for the technical team.

Historically, Django followed Python’s model of having a Benevolent Dictator for Life, that is, a project founder who retained final say for disputes/arguments within the community. Adrian Holovaty and Jacob Kaplan-Moss functioned as Django’s dual-BDFLs from 2005 until their retirement in 2014.

Django has a small, core team of trusted volunteers who work alongside the Django Fellows to manage technical side of the Django Project. Django Core members are divided into teams that have authority over the Django Project infrastructure, including the Django Project website itself, the official issue tracker, official mailing lists, IRC channels, and more. There is currently ongoing discussion around potentially dissolving Django core or updating it in a meaningful way.

> [Back to Home](../README.md)
