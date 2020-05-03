
{% for member in site.stu %}
  <figure>
  <img src="{{ member.image }}"> @{{ member.user }}({{member.name}})
    </figure>
  {{ member.content ｜ markdownify }} 

{% endfor %}
