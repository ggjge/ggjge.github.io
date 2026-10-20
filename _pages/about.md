---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- ============ Biography ============ -->
## Biography
{: #biography}

Hi, I'm **Li Hehan**, currently an application researcher at **Baidu** Company

**Contact**
- 📧 Email: [lhhzkj@gmail.com](mailto:lhhzkj@gmail.com)
- 💬 WeChat: li44971

<!-- ============ Research ============ -->
## Research
{: #research}
My Major research direction:

- **NLP**
- **LLM Post Training**
- **Generative Retrieval**

<!-- ============ Publications ============ -->
## Publications
{: #publications}

{% for post in site.publications reversed %}
  <div class="list__item">
    <article class="archive__item">
      <p style="margin:0 0 .2em 0;">
        {% if post.paperurl %}<a href="{{ post.paperurl }}">{{ post.title }}</a>{% else %}{{ post.title }}{% endif %}{% if post.venue %}. {{ post.venue }}.{% endif %}
      </p>
      {% if post.authors %}<p style="margin:0 0 1.2em 0; color:#555;">{{ post.authors }}</p>{% endif %}
    </article>
  </div>
{% endfor %}


<!-- ============ Education ============ -->
## Education
{: #education}

- **Nankai University**，undergraduate degree in Mathematics
- **Renmin University of China**，master degree in Computer Application Technology

