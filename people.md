# People

## President

{% for p in site.data.people %}
{% if p.position == "President" %}
{% include person.html name=p.name img=p.img email=p.email website=p.website about=p.about %}
{% endif %}
{% endfor %}

## Vice President

### and Selection Committee Chair

{% for p in site.data.people %}
{% if p.position == "Vice President" %}
{% include person.html name=p.name img=p.img email=p.email website=p.website about=p.about %}
{% endif %}
{% endfor %}

## Selection Committee

{% for p in site.data.people %}
{% if p.position == "Selection Committee" %}
{% include person.html name=p.name img=p.img email=p.email website=p.website topics=p.topics %}
{% endif %}
{% endfor %}

## Host Matching Committee

{% for p in site.data.people %}
{% if p.position == "Host Matching" %}
{% include person.html name=p.name img=p.img email=p.email website=p.website about=p.about %}
{% endif %}
{% endfor %}

## Treasurer

{% for p in site.data.people %}
{% if p.position == "Treasurer" %}
{% include person.html name=p.name img=p.img email=p.email website=p.website about=p.about %}
{% endif %}
{% endfor %}

## Volunteering

We are generally looking for trusted and reputable community members who are interested in the mission of the program, have diverse and relevant experiences, and are sensitive and receptive to student needs and concerns.
If you are interested in getting involved, please [contact us](contact).
