---
title: members

---
<table>
    <tr>
      <th>nombre</th>
      <th>notas</th>
      <th>Sexo</th>
    </tr>
 
  </table>
# Members

 
{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}
## {{ nota.nombre }} - {{ nota.notas }} - {{ nota.sexo }} 

{% for nota in site.data.notas %}
 
 
{% endfor %}
