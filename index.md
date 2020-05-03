
{% for member in site.stu %}
<h2>
  <figure>
  &nbsp&nbsp >> <img src="{{ member.image }}" size=50> @{{ member.user }}(member.name)
    </figure><br>
  &nbsp&nbsp&nbsp&nbsp>>{{ member.content ｜ markdownify }} 
   </h2>
{% endfor %}
