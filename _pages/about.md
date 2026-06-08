---
layout: about
title: about
permalink: /
subtitle: 'Postdoctoral Researcher · <a href="https://www.tudelft.nl/en/3me/about/departments/delft-center-for-systems-and-control">Delft Center for Systems and Control</a>, TU Delft'

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Delft Center for Systems and Control</p>
    <p>TU Delft, Building 34</p>
    <p>Mekelweg 2, 2628 CD Delft</p>
    <p>Netherlands</p>

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: false
  limit: 3
---

I am a Postdoctoral Researcher at the Delft Center for Systems and Control (DCSC), TU Delft, working under [Prof. Bart De Schutter](https://www.tudelft.nl/staff/b.deschutter/) on the ERC Advanced Grant project [CLariNet](https://www.tudelft.nl/en/innovatie-impact/project-cases/projects-2023/clarinet).

My research develops **provably safe controllers** for autonomous systems operating under real-world uncertainties. I specialize in **Control Barrier Functions (CBFs)**. A defining aspect of my work is experimental validation: [theoretical safety guarantees are tested in closed environment](https://youtu.be/QX1f45XKJgg?si=EN9DB9RhkdGKa8Lv), [integration with energy-optimal controllers are validated on highway](https://youtu.be/yBbQW2Bi_5g?si=dGRqKfbbaBgMCu6w) using a connected and automated heavy-duty truck in collaboration with Navistar, Inc.

I received my Ph.D. in Mechanical Engineering from the University of Michigan in 2024, advised by [Prof. Gábor Orosz](https://public.websites.umich.edu/~orosz/), and was recognized with the **Prof. Pierre T. Kabamba Award** (2025), a **Rackham Predoctoral Fellowship** (2023), and the **Best Student Paper Award** by ASME (Dynamic Systems and Controls Division) at ACC 2023. I hold an M.Sc. from Bilkent University (2017) and a B.Sc. from the Middle East Technical University (2013).

## Selected Projects

{% assign sorted_projects = site.projects | sort: "importance" %}
<div class="projects">
  <div class="container">
    <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects limit:3 %}
      {% include projects.liquid %}
    {% endfor %}
    </div>
  </div>
</div>
