---
layout: page
title: Partnerships

---

List of partnerships; datatables to sort by title / PFA / area?


<table>
	<tr><th>ID</th><th>Partnership</th><th>Area</th><th>Chaired by</th><th>Coordinated by</th></tr>
{% for page in site.pages %}
{% if page.id %}
	<tr><td>{{ page.id }}</td><td>{{ page.title }}</td><td>{{ page.area }}</td><td>{{ page.chaired }}</td><td>{{ page.coordinated }}</td><tr>
{% endif %}
{% endfor %}
</table>