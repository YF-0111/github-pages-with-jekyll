{% for member in site.stu %}
  <h2> ![photo]({{ member.image }}) - {{ member.name }}）</h2>
    <p> {{ member.content }}</p>
{% endfor %}
