{% for member in _stu %}
  <h2> ![photo]({{ member.image }}) - {{ member.name }}）</h2>
    <p> {{ member.content | markdownify }}</p>
{% endfor %}
