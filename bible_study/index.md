---
layout: default
title: Bible study
---

{% capture lvl %}{{ page.url | append:'index.html' | split:'/' | size }}{% endcapture %}
{% capture relative %}{% for i in (3..lvl) %}../{% endfor %}{% endcapture %}

Bible study
===========

Current semester (Spring 2018)
------------------------------

We have a weekly Bible study on Thursday evenings from 18:30--20:30
(6:30--8:30pm) MST in the SUB. This semester we are studying James' epistle and
the book of Esther. Below is the schedule of meeting locations and scripture
passages for each week.

| Date   | Location                         | Passage                   |
| ------ | -------------------------------- | ------------------------- |
| Jan 18 | SUB Cherry/Silver                | Introduction to James     |

Past semesters
--------------

* [Fall 2017]({{ relative }}bible_study/2017_fall.html)
* [Spring 2017]({{ relative }}bible_study/2017_spring.html)
* [Fall 2016]({{ relative }}bible_study/2016_fall.html)
* [Spring 2016]({{ relative }}bible_study/2016_spring.html)
