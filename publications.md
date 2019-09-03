---   
title: Publications     
---   



{% for pubgroup in site.data.publications %}
  <h2 id="{{ pubgroup.id }}">{{ pubgroup.name }}</h2>

  {% if pubgroup.pubs %}
  {% for pub in pubgroup.pubs %} {% include publication.html pub = pub %}<br/><br/>{% endfor %}
  {% else %}
  No publications currently
  {% endif %}
{% endfor %}

