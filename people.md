# People

**President:** [Talia Ringer](https://dependenttyp.es/) [tringer@illinois.edu](mailto:tringer@illinois.edu) (assistant professor at UIUC)

**Vice president:** [Caleb Stanford](https://www.cis.upenn.edu/~castan/) [castan@cis.upenn.edu](mailto:castan@cis.upenn.edu) (incoming assistant professor at UC Davis)

## Selection Committee

{% for p in site.data.people %}
{% if p.status == "current" %}
{% include person.html name=p.name img=p.img email=p.email website=p.website topics=p.topics %}
{% endif %}
{% endfor %}

## Volunteering

We are generally looking for trusted and reputable community members who are interested in the mission of the program, have diverse and relevant experiences, and are sensitive and receptive to student needs and concerns.
If you are interested in getting involved, please [contact us](contact).
