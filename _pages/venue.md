---
title: "Venue"
excerpt: "Where the conference is held, and how to get there."
# Optional photo gallery: drop images into this folder and uncomment the line below.
# gallery_dir: /assets/images/venue
---

{% assign venue = site.data.conference.venue %}
**{{ venue.name }}**<br>
{{ venue.address }}
{% if venue.map_url != "" %}<br>[View on a map]({{ venue.map_url }}){% endif %}

> TODO: A description of the venue and the surrounding area.

## Getting there

> TODO: Travel by train, plane, car and bus; parking; local taxis.

## Accommodation

> TODO: Recommended hotels / student accommodation, any discount codes, booking deadlines.

## Accessibility

> TODO: Step-free access, accessible toilets, quiet rooms, hearing loops, and who to contact
> about specific needs.
