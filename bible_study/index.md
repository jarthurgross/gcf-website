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
| Jan 25 | SUB Cherry/Silver                | James 1                   |
| Feb 1  | SUB Cherry/Silver                | James 2                   |
| Feb 8  | SUB Cherry/Silver                | James 3                   |
| Feb 15 | SUB Cherry/Silver                | James 3                   |
| Feb 22 | SUB Cherry/Silver                | James 4                   |
| Mar 1  | SUB Cherry/Silver                | James 5                   |
| Mar 8  | SUB Cherry/Silver                | Summary of James          |
| Mar 22 | SUB Cherry/Silver                | Esther 1                  |
| Mar 29 | SUB Cherry/Silver                | Esther 2                  |
| Apr 5  | SUB Cherry/Silver                | Esther 3                  |
| Apr 12 | SUB Cherry/Silver                | Esther 4                  |
| Apr 19 | SUB Cherry/Silver                |  |
| Apr 26 | SUB Cherry/Silver                |  |
| May 3  | SUB Cherry/Silver                |  |

Past semesters
--------------

* [Fall 2017]({{ relative }}bible_study/2017_fall.html)
* [Spring 2017]({{ relative }}bible_study/2017_spring.html)
* [Fall 2016]({{ relative }}bible_study/2016_fall.html)
* [Spring 2016]({{ relative }}bible_study/2016_spring.html)
