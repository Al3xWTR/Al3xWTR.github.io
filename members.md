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


{% for nota in site.data.notas %}
  ## {{ nota.nombre }} - {{ nota.edad }} - {{ nota.sexo }}
{% endfor %}
