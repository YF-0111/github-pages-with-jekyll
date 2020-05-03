
{% for member in site.stu %}
img[pic] {
  width: 1px;
  border: none;
  background: none;
}
![pic]({{ member.image }})@{{ member.user }}({{member.name}})
 {{ member.content ｜ markdownify }} 

{% endfor %}
