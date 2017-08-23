---
layout: default
title: Contact
---

{% capture lvl %}{{ page.url | append:'index.html' | split:'/' | size }}{% endcapture %}
{% capture relative %}{% for i in (3..lvl) %}../{% endfor %}{% endcapture %}

The GCF student officers for the 2017--2018 school year are Jonathan Gross and
Laura Steiner. They may be reached at the organization's official email address
[gcf@unm.edu][email].

You can also view our page on the UNM Student Activities Center website:
[Graduate Christian Fellowship][unmsac].

[email]: mailto:gcf@unm.edu
[unmsac]: https://unm-community.symplicity.com/?s=student_group&id=5f21cd765df59eafa192c082c175f1fd
