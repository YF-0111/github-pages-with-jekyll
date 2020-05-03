readme  
{% for member in site.stu %}
* ![pic]({{ member.image }}){:height="50px" width="50px"}@{{ member.user }}({{member.name}})  
  * {{ member.content ｜ markdownify }}  
{% endfor %}
