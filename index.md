
{% for member in site.stu %}
  <h2> <figure>
<a><img src="{{ member.image }}"></a>
</figure>@{{ member.name }}</h2>
   {{ member.content ｜ markdownify }} 
{% endfor %}
