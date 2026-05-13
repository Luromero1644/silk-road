---
author: Lucas Romero
title: Light on the Silk Road: Manichaeism Survivals in Medieval Art
layout: base
header-title: Essays
thumbnail: images/buddhajesus.png
summary: How a dead religion is still remembered, more for its art than for its ideas.

---
# Introduction

“Truth is your branch, joy is your leaves, love is your fruit, the eternal Living Self. Now, my God, I have seen you. I will not die! You are like the eternal light and living tree.” 
Manichaean-Turkic fragment (SI6621), near Turfan
In the late ancient and medieval world, during the rise of Christianity, but before and during the origins of Islam, rose a unique religion that spread far along the trading routes modern scholars would deem ‘The Silk Road’. This creed was called Manichaeism, after its founder Mani, a 3rd-century prophet hailing from Sassanid Mesopotamia. It presented itself as the final and most truthful religion, the true and ultimate answer from a long line of prophets of surprisingly different backgrounds: Zoroaster, the traditional founder of Zoroastrianism (and the state religion of Mani’s home), Siddhartha Gautama, the Buddha, the traditional founder of Buddhism, Jesus Christ, the central figure of Christianity, and Mani himself. Mani drew from these faiths, amongst others– he was raised in a sect known as the ‘Alchasaitics,’ also known as the Elcesaites, a Jewish-Christian sect with gnostic leanings, but influences from these other ‘prophets’ can also be found in the new religion’s central teachings.

# Thematic Essays


{% assign filtered = "" | split: "" %}
{% for p in site.pages %}
  {% if p.path contains 'essays/' %}
    {% unless p.path contains 'objects' %}
      {% assign filtered = filtered | push: p %}
    {% endunless %}
  {% endif %}
{% endfor %}
{% include nav/card-grid.html cards=filtered %}
