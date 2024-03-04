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
 
  <table>
    <tr>
      <th>nombre</th>
      <th>notas</th>
      <th>Sexo</th>
    </tr>
  ## {{ nota.nombre }} - {{ nota.notas }} - {{ nota.sexo }} 
  </table>
{% endfor %}
