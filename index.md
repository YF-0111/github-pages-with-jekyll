
{% for member in site.stu %}
  <figure>
  <a><img src="{{ member.image }}"></a>
  </figure>@{{ member.name }}
   {{ member.content ｜ markdownify }} 
{% endfor %}
