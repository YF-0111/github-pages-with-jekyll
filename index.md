1
{% for member in site.stu %}
  <h2> [photo]({{member.image}}) - {{ member.name }}）</h2>
    <p> {{ member.content | markdownify }}</p>
{% endfor %}
