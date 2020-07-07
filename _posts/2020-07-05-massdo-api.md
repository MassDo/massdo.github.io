---
title: "Massdo-Api"
date: 2020-07-05
tags: [Django-Rest-Framework, Traefik, Docker]
---
Api simple réalisée à l'aide de Django-Rest-Framework, déployée avec AWS/Traefik/Docker/Postgres. et utilisation de letsencrypt pour les certificats.

[massdo.fr](https://massdo.fr/)


AWS instance EC2:
<img src="{{ site.url }}{{ site.baseurl }}/images/massdo-api/aws.png" alt="AWS EC2">


Conteneurs Docker:

<img src="{{ site.url }}{{ site.baseurl }}/images/massdo-api/container.png" alt="containers">


Chiffrement des mots de passe:

<img src="{{ site.url }}{{ site.baseurl }}/images/massdo-api/pass.png" alt="Chiffrement des mots de passe">

Voir le code sur [GitHub](https://github.com/MassDo/massdo-api)