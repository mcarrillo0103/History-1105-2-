---
title: Essays
layout: base
header-title: Essays
---

# Essays

This section aims to givenformation about the Vietnamese experience in New Mexico and answer the main question of this website: What was life like for Vietnamese refugees in New Mexico? Read a quick overview on why Vietnamese people moved to New Mexico, their experience in New Mexico, and what work looks like for them. Gain some insight into why thousands of Vietnamese refugees chose to move somewhere that has little geographic similarities to their home country.

Some other questions that the reader should ask are: In what ways is Vietnamese refugee history similar to the history of Native Americans, or Mexican migrants? What similarities do Vietnamese refugees in New Mexico have with Asian American history as whole in the United States?

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-grid.html cards=cards %}
