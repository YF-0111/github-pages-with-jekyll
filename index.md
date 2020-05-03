
{% for member in site.stu %}
![pic]({{ member.image }})@{{ member.user }}({{member.name}})
 {{ member.content ｜ markdownify }} 

{% endfor %}
