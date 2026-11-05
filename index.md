---
layout: home
# No title: the header shows the conference name from _data/conference.yml instead.
subtitle: "An international conference series on visual ecology"

reaction:
  text: stripes
  background: spots
  text_alpha: 0.0      # default 0 (invisible)
  pattern_alpha: 1.0   # default 1 (opaque) — needs to drop below 1 for text_alpha to show through
  decay: 0.95          # default 0 (no smoothing) — try 0.7-0.95 for visible trails
  attraction: 0.4      # default 0 (free drift) — try 0.5-2, it needs to be much bigger than feed/kill values to matter
---

## About the series

> TODO: A short introduction to the Visual Ecology conference series — what visual ecology
> is, who the meetings are for, how often they run and how the series started.

> TODO: A paragraph about this year's meeting — the host, the themes, and why people should
> come. Link to the [keynote speakers]({{ '/keynote-speakers/' | relative_url }}),
> [venue]({{ '/venue/' | relative_url }}) and [registration]({{ '/register/' | relative_url }})
> pages as useful.

<!-- The hero (dates, register button, key dates) comes from _data/conference.yml, and the
     "Past conferences" and "Key groups" sections below this text from
     _data/past_conferences.yml and _data/groups.yml. -->
