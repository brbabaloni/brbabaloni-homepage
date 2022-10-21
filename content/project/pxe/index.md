---
title: Déploiement d'un serveur PXE FOG
summary: Fog Project est un logiciel sous Linux qui va vous permettre d’effectuer vos déploiements pour machines Windows, Linux, et Mac.
tags:
- pro
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

 - 1. Qu’est-ce que le déploiement
Le déploiement consiste à effectuer des installations automatisées de machines ou installer ou mettre à jour automatiquement des logiciels sur des machines en production.

Pour effectuer des installations automatisées de systèmes d’exploitation, il vous faudra préparer au préalable un « Master ». Ce master sera cloné sur les machines de destination, avec des possibilités de personnalisation automatisée.

À cette fin, la machine cliente devant recevoir le déploiement (l’application du master sur celui-ci) démarrera via le réseau, le serveur de déploiement lui envoyant les éléments nécessaires.

La réalisation d’un master nécessitera des compétences sur le fonctionnement des systèmes d’exploitation concernés ainsi que de leurs outils. Un minimum de compétences en programmation de script sera également nécessaire.