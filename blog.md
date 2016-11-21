---
layout: default
title: Blog
permalink: /blogddd/

---
<div>
    {% for post in site.posts %}
      <header class="post-header">
        <h1>{{ page.title }}</h1>
        <p>{{ page.subline }} | {{ page.friendly-date }}</p>
      </header>
      <section class="post-content">
        <article class="post-content">
          <p>{{ page.summary }}</p>
          <img src="/assets/img/blog/{{ main-image }}"
          <a href="{{ post.url }}">View more photos</a>
        </article>
      </section>
    {% endfor %}
</div>
