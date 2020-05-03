
{% for member in site.stu %}
![pic]({{ member.image }}){:height="5px" width="5px"}@{{ member.user }}({{member.name}})
 {{ member.content ｜ markdownify }} 

{% endfor %}
