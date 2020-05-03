
{% for member in site.stu %}
<h2>
  <figure>
  <img src="{{ member.image }}">
  </figure>@{{ member.name }}
  </h2>
   {{ member.content ｜ markdownify }} 
{% endfor %}
