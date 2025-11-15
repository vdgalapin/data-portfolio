---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<div class="project-grid">
    {% for project in site.pages %}
        {% if project.url contains "/project" %}
            <div class="project-card">
                <a href="{{ site.baseurl }}{{ project.url }}">
                    <h3>
                        {{ project.title }}
                    </h3>
                </a>
            </div>
        {% endif %}
    {% endfor %}
</div>