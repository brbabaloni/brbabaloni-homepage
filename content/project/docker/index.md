---
title: Déploiement de conteneurs applicatifs avec Docker et Portainer
summary: La DSI d'ASSUR MER souhaite déployer et maintenir en condition opérationnelle certains service comme les serveurs de web ou de bases de données tous en assurant le suivi du déploiement avec Portainer.
tags:
- E5
date: "2023-03-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
url_code: ""
url_pdf: "project/docker"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

<h3>Contexte</h3>
La DSI envisage le changement progressif de son système d’hébergement des applications afin des les migrer vers un cluster Docker pour ses facilités de déploiement et de supervision.

Cette solution permettra une meilleure disponibilité, la mise en place d’un équilibrage de charge en déployant dynamiquement des conteneurs applicatifs et la réplication de certaines applications.
<br>
<br>
<h3>Environnement</h3>
<ul>- 1 hyperviseur de type 1 « bare-metal » VMware ESXi 7.0 U3</ul>
<ul>- 1 machine virtuelle sous Debian 11</ul>
<ul>- 1 poste client Windows 10</ul>
<br>
<br>
<h3>Démarche</h3>
<ul>1)	Installation de la VM Docker V-ASSURMER-DOCKER01 - 172.16.0.6</ul>
<ul>2)	Création du cluster Docker</ul>
<ul>3)	Déploiement du conteneur Portainer</ul>
<ul>4)	Déploiement d’une application</ul>
<ul>5)	Test de mise en production</ul>
<ul>6)	Administration et suivi du déploiement avec Portainer</ul>
<br>
<br>
<h3>Résultats attendus</h3>
<ul>- Mise à disposition d’applications/services aux utilisateurs</ul>
<ul>- Administration et supervision du déploiement par Portainer</ul>
<br>
<br>
<h3>Documents associés</h3>
<ul><a href="E5-DOCKER.pdf">Fiche descriptive de réalisation professionnelle</a></ul>
<ul><a href="topologie_assurmer.pdf">Topologie de l'infrastructure ASSUR MER</a></ul>
<ul><a href="topologie_docker.pdf">Topologie de l'infrastructure DOCKER</a></ul>
<ul><a href="doc_e5_docker.pdf">Documentation Docker</a></ul>

