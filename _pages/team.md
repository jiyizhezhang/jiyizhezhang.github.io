---
title: "Zhang Group - Team"
layout: gridlay
excerpt: "Zhang Group: Team members"
sitemap: false
permalink: /team/
---

### Group Members

We always welcome motivated talents from all over the world to join our team!

<br>

#### Principal Investigator

<div class="clearfix" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/3_others/team_pic/Jiyizhe3.jpg" alt="Dr Jiyizhe Zhang" style="float: left; width: 30%; max-width: 110px; height: auto; margin-right: 35px; border-radius: 0;" />
<p style="margin: 0; overflow: hidden;">
<strong>Dr Jiyizhe Zhang</strong><br>
<i>Lecturer (Assistant Professor)</i><br>
<i>Department of Chemical Engineering</i><br>
<i>University of Manchester</i><br>
<a href="mailto:jiyizhe.zhang@manchester.ac.uk"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-top: 8px;" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414zM0 4.697v7.104l5.803-3.558zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586zm3.436-.586L16 11.801V4.697z"/></svg></a>
<a href="https://www.linkedin.com/in/jiyizhe-zhang-42786b198/"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 8px;" fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16"><path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"/></svg></a>
</p>
</div>

Dr. Jiyizhe Zhang studied chemical engineering in her undergraduate. 
Starting from 2017, she took a jointly awarded PhD programme between Tsinghua University and the University of Melbourne, working on modelling of continuous solvent extraction processes for pharmaceutical applications.
She received her PhD in 2022 and then joined University of Cambridge as a postdoc researcher, working with Prof. Alexei Lapkin, focusing on digital manufacturing by exploring artificial intelligence (AI) and robotic experimentation to accelerate chemical process development.
Since 01/2025, she became Senior Research Associate at Cambridge (Research Assistant Professor) prior to joining the University of Manchester.

<br>

[//]: # (#### Postdoctoral Researchers)

[//]: # ()
[//]: # (This could be you!)

<br>

#### PhD Students

{% assign phd_students = site.data.team_members | where: "category", "phd" %}
{%- for member in phd_students %}
{%- assign even_odd = forloop.index0 | modulo: 2 %}
{%- if even_odd == 0 %}
<div class="row" markdown="0">
{%- endif %}
<div class="col-sm-6 clearfix" style="margin-bottom: 25px;">
{%- assign photo_path = "/images/teampic/" | append: member.photo -%}
{%- assign photo_exists = site.static_files | where: "path", photo_path | size -%}
{%- if member.photo and photo_exists > 0 %}
<img src="{{ site.url }}{{ site.baseurl }}{{ photo_path }}" alt="{{ member.name }}" style="float: left; width: 25%; max-width: 110px; height: auto; margin-right: 15px;" />
{%- endif %}
<p style="margin: 0 0 4px 0;"><strong>{{ member.name }}</strong></p>
<i>{{ member.info }}</i>
{%- if member.email %} <a href="mailto:{{ member.email }}"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" style="margin-right: 4px; margin-left: 6px; vertical-align: -3px;" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414zM0 4.697v7.104l5.803-3.558zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586zm3.436-.586L16 11.801V4.697z"/></svg></a>{% endif %}
{%- if member.linkedin %} <a href="{{ member.linkedin }}"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" style="margin-right: 4px; margin-left: 4px; vertical-align: -3px;" fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16"><path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"/></svg></a>{% endif %}
{%- if member.education %}
<div style="overflow: hidden; margin-top: 8px;">{% for edu in member.education %}{{ edu }}{% unless forloop.last %}<br>{% endunless %}{% endfor %}</div>
{%- endif %}
</div>
{%- if even_odd == 1 or forloop.last %}
</div>
{%- endif %}
{%- endfor %}

<br>

#### Master and Undergraduate Students

{% assign master_students = site.data.team_members | where: "category", "master" %}
{%- for member in master_students %}
{%- assign even_odd = forloop.index0 | modulo: 2 %}
{%- if even_odd == 0 %}
<div class="row" markdown="0">
{%- endif %}
<div class="col-sm-6 clearfix" style="margin-bottom: 25px;">
{%- assign photo_path = "/images/teampic/" | append: member.photo -%}
{%- assign photo_exists = site.static_files | where: "path", photo_path | size -%}
{%- if member.photo and photo_exists > 0 %}
<img src="{{ site.url }}{{ site.baseurl }}{{ photo_path }}" alt="{{ member.name }}" style="float: left; width: 25%; max-width: 110px; height: auto; margin-right: 15px;" />
{%- endif %}
<p style="margin: 0 0 4px 0;"><strong>{{ member.name }}</strong></p>
<i>{{ member.info }}</i>
{%- if member.email %} <a href="mailto:{{ member.email }}"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" style="margin-right: 4px; margin-left: 6px; vertical-align: -3px;" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414zM0 4.697v7.104l5.803-3.558zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586zm3.436-.586L16 11.801V4.697z"/></svg></a>{% endif %}
{%- if member.linkedin %} <a href="{{ member.linkedin }}"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" style="margin-right: 4px; margin-left: 4px; vertical-align: -3px;" fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16"><path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"/></svg></a>{% endif %}
{%- if member.education %}
<div style="overflow: hidden; margin-top: 8px;">{% for edu in member.education %}{{ edu }}{% unless forloop.last %}<br>{% endunless %}{% endfor %}</div>
{%- endif %}
</div>
{%- if even_odd == 1 or forloop.last %}
</div>
{%- endif %}
{%- endfor %}

<br>

#### Former supervised students

**Miguel Chen**

MEng dissertation, 2025-2026 

Project: Automated process design for bio-downstream separation using multi agent systems

**Hendrik Scheulen**

2025.4-2025.11 @ University of Cambridge

**Jan Laub-Fridric**

2024.4-2024.11 @ University of Cambridge, now PhD student at ETH Zurich

**Mathis Heyer**

2023.4-2023.11 @ University of Cambridge, now PhD student at Stanford University


<br><br>
