
{% for member in site.stu %}
<h2>
  <figure>
  <img src="{{ member.image }}"> @{{ member.user }}({{member.name}})
    </figure>
  {{ member.content ｜ markdownify }} 
   </h2>
{% endfor %}
