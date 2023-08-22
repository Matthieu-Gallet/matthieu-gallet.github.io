---
layout: page
permalink: /repositories/
title: Repositories
# description: Edit the `_data/repositories.yml` and change the `github_users` and `github_repos` lists to include your own GitHub profile and repositories.
nav: true
nav_order: 6
---

Selection of repositories. The complete list of repositories is available on [GitHub](https://github.com/Matthieu-Gallet?tab=repositories)

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
