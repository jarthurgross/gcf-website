---
layout: default
title: Graduate Christian Fellowship
---

{% capture lvl %}{{ page.url | append:'index.html' | split:'/' | size }}{% endcapture %}
{% capture relative %}{% for i in (3..lvl) %}../{% endfor %}{% endcapture %}

GCF at UNM
==========

Welcome to the Graduate Christian Fellowship at the University of New Mexico!
We are a group of graduate students interested in helping each other follow
Jesus in the context of our graduate studies. We are informally associated with
[InterVarsity Christian Fellowship][ivcf] (IVCF) and regularly interact with
the [undergratuate chapter][unmiv] here on campus.

If you're looking for a community to support you in your faith during graduate
school or just interested in exploring the Christian faith alongside your
graduate studies we would love for you to join us! Our regular events include
a weekly [bible study][bible] and [lunchtime discussion][lunchbox].

[ivcf]: http://intervarsity.org/
[unmiv]: http://ivcf.unm.edu/
[bible]: {{ relative }}bible_study
[lunchbox]: {{ relative }}lunchbox_theology
