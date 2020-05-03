
{% for member in site.stu %}
img[alt=pic] {
  width: 5px;
  border: none;
  background: none;
}
![pic]({{ member.image }})@{{ member.user }}({{member.name}})
 {{ member.content ｜ markdownify }} 

{% endfor %}
