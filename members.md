---
title: members

---

# Members

aa
{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for persona in site.data.personas %}
  ## {{ notas.nombre }} - {{ notas.edad }} - {{ notas.sexo }}
{% endfor %}
