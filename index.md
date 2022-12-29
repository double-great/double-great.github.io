---
layout: home
list_title: Projects
content_position: bottom
show_excerpts: true
contributors:
  - name: Jason Morris
    github: jsnmrs
  - name: Katy DeCorah
    github: katydecorah
---

<h2 class="post-list-heading">{% include icon/edit.svg %} Contributors</h2>

<div style="margin-top: 1rem;">
{% for contributor in page.contributors %}
<a href="https://github.com/{{contributor.github}}" style="display: inline-block; margin-right: 1rem"><img style="max-width: 5rem; border-radius: 100%; display: block;" width="150" height="150" src="https://github.com/{{contributor.github}}.png" alt="{{contributor.name}}"></a>
{% endfor %}
</div>
