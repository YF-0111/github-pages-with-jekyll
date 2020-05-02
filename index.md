{% for member in site.stu %}
  <h2> {{ ![pic]({{"member.image"}}) }} @{{ member.name }}</h2>
   {{ member.content ｜ markdownify }} 
{% endfor %}
