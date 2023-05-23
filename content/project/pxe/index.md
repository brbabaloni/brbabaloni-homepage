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
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

<p>Activités du référentiel pour l’épreuve E4 2023 :
<ul>- Gérer le patrimoine informatique</ul>
<ul>- Travailler en mode projet</ul>
</p>
<h3>Contexte</h3>

Dans le cadre du renouvellement partiel du matériel de nos utilisateurs, nous devons déployer une centaine de machine par an.
Auparavant les postes étaient masterisés manuellement à l'aide d'un disque dur et d'une installation MDT. Ce processus assez long (30min à 1h30 selon les postes) est chronofage pour l'activité du Service Informatique Zonal.

Pour accélerer le déploiement des nouvelles machine, j'ai proposé à mes chefs de service cette solution technique de déploiement de poste via le réseau. Elle permet de réduire le temps déploiement à 5 min par machine.

<h3>Solution</h3>

FOG (Free OpenSource Ghost) est une solution open-source de déploiement
d'images systèmes et d'applications sur des postes clients, qui se base sur
une architecture L.A.M.P : Linux / Apache / MySQL / PhP.
FOG permet entre de déployer un système d'exploitation préalablement
cloné, sur un parc de machines donné via le réseau en s'appuyant sur les
protocoles DHCP / PXE.

<h3>Livrables</h3>
<ul><a href="install_pxe.pdf">Doc 1 : Installation de FOG</a></ul>
<ul><a href="doc_util_pxe.pdf">Doc 1 : Documentation technique</a></ul>