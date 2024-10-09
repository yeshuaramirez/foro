---
layout: home
title: "Foro de Ciencias"
---
Bienvenidos al foro de ciencias. Aquí podrás discutir los temas más apasionantes sobre el cosmos. Revisa las categorías o únete a la discusión más reciente:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
