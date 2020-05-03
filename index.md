
{% for member in site.stu %}
<h2>
  <figure>
  <img src="{{ member.image }}"> @{{ member.name }}
    </figure>
  </h2>
   {{ member.content ｜ markdownify }} 
{% endfor %}
