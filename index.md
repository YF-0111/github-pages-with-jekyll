
{% for member in site.stu %}
<h2>
  <img src="{{ member.image }}"> @{{ member.name }}
  </h2>
   {{ member.content ｜ markdownify }} 
{% endfor %}
