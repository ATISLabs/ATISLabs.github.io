---
layout: article
---

# Advanced Technology Laboratory in Intelligent Systems

This laboratory aims to promote and lead scientific advances in the field of Artificial Intelligence with a focus on complex domains that are still little explored. Some of our main themes are: behavior analysis on social media, high performance predictive models, recommender systems, predictive models without bias and AI for Healthcare.

[about](pages/about)

## Recent News

{% for post in site.posts offset: 0 limit:1 %}
  <article>
    <li>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    <a href="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
    <div class="item__image">
    <img class="image" src="{{ post.cover | prepend: site.baseurl }}">
    </div>
  </article>
{% endfor %}

{% for post in site.posts offset: 1 limit:5 %}
  <article>
    <li>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    <a href="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  </article>
{% endfor %}

## Research Groups

At the Laboratory, R&D begins with a difficult problem that we believe technology can solve. Our researchers work in cross-disciplinary teams that leverage the latest technical advances to develop innovative solutions.

- [High Performance Computing](pages/groups/hpc)
- [Intelligent Systems for Healthcare](pages/groups/healthcare)
