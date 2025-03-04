---
layout: page
permalink: /repositories/
title: Repositories
description: I'm a researcher and engineer passionate about Quantum Computing, Machine Learning, and Data Science. My GitHub repositories feature projects spanning AI, recommendation systems, and quantum algorithms. I enjoy exploring complex problems, optimizing solutions, and sharing insights through code. Feel free to check out my work and collaborate!
nav: true
nav_order: 3
---

{% if site.data.repositories.github_users %}

## GitHub User Profile

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

{% endif %}

---

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
