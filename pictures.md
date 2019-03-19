---
layout: default
---
## Foto del appartamento

{% for room in site.data.rooms %}
### {{ room.name }}
{% for link in room.img %}
![alt text]({{ link }} "{{ room.name }}")
{% endfor %}
{% endfor %}
