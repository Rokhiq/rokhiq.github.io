---
layout: default
title: Aharen-san wa Hakarenai
coverPhoto: https://cdn.discordapp.com/attachments/970663117057032232/1003664980295569478/mpv-shot0107.jpg
---

      <ul>
        {% for post in site.categories['Aharen-san-wa-Hakarenai'] %}
        <li><a class="post" href="{{ post.url }}">{{ post.title }}</a><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%m-%d-%Y" }}</time></li>
        {% endfor %}
      </ul>