---
layout: main.njk
title: Primer index
---

# {{ title }}

Pruebo el contenido de la carpeta con los post correspondiente. 
## tambien agrego contenido extra
Y en el segundo parrafo agrego lo que considero correspondiente. 

{% for post in collections.posts %}

-[{{post.data.title}}]({{post.url}})
-[{{post.data.description}}]

{% endfor %}