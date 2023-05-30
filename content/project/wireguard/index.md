---
title: Mise en place d’une solution VPN Wireguard
summary: Pour permettre aux collaborateurs de se connecter à distance de façon sécurisé aux ressources de l'entreprise, la DSI d'ASSUR MER vous charge de mettre en place une solution de connexion distante.
tags:
- E5
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
url_code: ""
url_pdf: "project/wireguard/install_vpn.pdf"
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

Pour permettre aux collaborateurs de se connecter à distance de façon sécurisé aux ressources de l'entreprise, la DSI d'ASSUR MER vous charge de mettre en place une solution de connexion distante.

La crise sanitaire liée au COVID-19 à fortement changer les modes de production de biens et services, lors du confinement mis en place en raison de la pandémie, la DSI a dû mettre en place un accès extérieur aux ressources réseaux de l’entreprise pour permettre aux salariés de continuer à travailler. La DSI a retenu Wireguard comme solution VPN.
<br>
<br>
<h3>Environnement</h3>
<ul>- 1 routeur/pare-feu pfSense</ul>
<ul>- 1 poste client Windows 10</ul>
<ul>- 1 serveur de supervision CheckMK</ul>
<br>
<br>
<h3>Démarche</h3>
<ul>1)	Configuration du VPN Wireguard sur pfSense</ul>
<ul>2)	Création des clés utilisateurs</ul>
<ul>3)	Création des règles de pare-feu sur pfSense</ul>
<ul>4)	Test de connexion depuis un poste client</ul>
<ul>5)	Supervision de la connexion avec CheckMK</ul>
<br>
<br>
<h3>Résultats attendus</h3>
<ul>-	Mise à disposition des ressources réseaux de l’entreprise aux télétravailleurs</ul>
<ul>-	Sécuriser l’accès aux réseaux depuis l’extérieur</ul>
<ul>-	Supervision du bon fonctionnement de l’accès VPN avec l’outil de supervision CheckMK</ul>
<br>
<br>
<h3>Documents associés</h3>
<ul><a href="E5-Wireguard.pdf">Fiche descriptive de réalisation professionnelle</a></ul>
<ul><a href="topologie_assurmer.pdf">Topologie de l'infrastructure ASSUR MER</a></ul>
<ul><a href="doc_e5_wireguard.pdf">Documentation VPN</a></ul>
<ul><a href="install_checkmk.pdf">Documentation CheckMK</a></ul>