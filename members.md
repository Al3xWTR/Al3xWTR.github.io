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
  ## {{ nota.nombre }} - {{ nota.notas }} - {{ nota.sexo }}
  <table>
    <tr>
      <th>nombre</th>
      <th>notas</th>
      <th>Sexo</th>
    </tr>
    {% for nota in notas %}
  
    <tr>
      <td>{{ nota.nombre }}</td>
      <td>{{ nota.notas }}</td>
      <td>{{ notaa.sexo }}</td>
    </tr>
  
    {% endfor %}
  </table>
{% endfor %}
