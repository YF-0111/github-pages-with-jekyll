
{% for member in site.stu %}
<h2>
  <figure>
  <img src="{{ member.image }}" sizes=2px> @{{ member.user }}(member.name)
    </figure><br>
  {{ member.content ｜ markdownify }} 
   </h2>
{% endfor %}
