---
title: Self-paced exercises
permalink: self-paced.html
layout: home
---

<!--
This is the SECOND, separate exercise list for self-paced learners.
It lists exercises stored under \Instructions\Self-Paced (a different folder from the
instructor-led exercises under \Instructions\Labs), so the two tracks never appear in the
same list.

To add a self-paced exercise, create a markdown file under \Instructions\Self-Paced with
"lab.title" metadata at the top (see the template in that folder) and it will show up below.
-->

This page lists the **self-paced exercises** associated with Microsoft skilling content on [Microsoft Learn](https://learn.microsoft.com). For the instructor-led version of these exercises, see the [Instructor-led exercises]({{ site.github.url }}/index.html) page.

**Exercise tracks:** [Instructor-led]({{ site.github.url }}/index.html) \| [**Self-paced**]({{ site.github.url }}/self-paced.html)

<hr>

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Self-Paced'" %}
{% for activity in labs  %}
{% if activity.lab.title %}
### [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }})


{% if activity.lab.level %}**Level**: {{activity.lab.level}} \| {% endif %}{% if activity.lab.duration %}**Duration**: {{activity.lab.duration}}{% endif %}

{% if activity.lab.description %}
*{{activity.lab.description}}*
{% endif %}
<hr>
{% endif %}
{% endfor %}
