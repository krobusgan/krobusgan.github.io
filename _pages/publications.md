---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

A mini-literature review is focused on the topic of testing automation in continuous integration and continuous delivery (CI/CD)
* <p style="text-decoration:underline;"><a href="/files/Literature_Review.pdf">Link</a></p>

A research propose to study the correlation and potential improvement of GUI Testing in Continuous Integration / Continuous Delivery environment.
* <p style="text-decoration:underline;"><a href="/files/Research_Proposal.pdf">Link</a></p>
