---
layout: default
title: Déclaration sur le Réseau Centipede
parent: Fabriquer une base RTK
nav_order: 6
---

## Déclaration sur le Réseau Centipede

Enfin, envoyer un courriel à [**contact@centipede.fr**](mailto:contact@centipede.fr) pour activer votre base sur la [Carte](https://centipede.fr) :

* Nom Prénom
* Profession
* Courriel
* Nom du point de montage de votre base GNSS RTK (de 4 caractères en MAJUSCULES et/ou chiffres)
* Matériels utilisés: modèle de votre antenne et de votre récepteur.
* le rapport du calcul de positionnement envoyé par IGN (fichier.tar.gz)
* Plusieurs photos (minimum 2) de l'installation de votre antenne (proche et vue d'ensemble).

Une fois que votre base sera déclarée par un administrateur, elle sera visible sur la carte:
* tout d'abord en rouge 🔴 : 
  * la base est pré déclarée sur le caster mais en attente de vérification du positionnement géographique.
  * elle est non accessible dans la liste des bases mais utilisable en renseignant manuellement le Point de montage.
* ensuite en orange 🟠 : 
  * La base est disponible dans la liste des points de montage http://caster.centipede.fr:2101
  * ses informations (type d'antenne, rapport de positionnement,...) sont en vérification.
* Enfin en vert 🟢 : 
  * la base est accessible, valide et utilisable par la communautée.
  * Le statut de la base (allumée 🟢, éteinte 🔴) est disponible sur la carte https://centipede.fr avec une actualisation toute les 30 secondes, un mail automatique est envoyé au resposable de la base en cas de coupure supérieure à 5 minutes.
  * Les métadonnées (rapport de positionnement, position, état, messages diffusés, taçabilité des déconnexions,...) de la base sont disponibles en cliquant sur votre base via https://centipede.fr

> En fonction de la disponibilité des administrateurs, le traitement de votre courriel peut prendre plusieurs jours, mais votre base est utilisable tout de suite.

> Un test de fonctionnement est réalisé toutes les 15 secondes sur l'ensemble du Réseau, si votre base RTK ne renvoie pas de signal au caster (panne électrique, coupure réseau, problème matériel,...) un mail vous sera envoyé automatiquement pour prévenir du dysfonctionnement et elle apparaitra en rouge sur la carte. Vous recevrez un nouveau mail lors de sa reconnexion au caster.


<figure class="map">
  <iframe src="https://centipede.fr/index.php/view/map/?repository=cent&project=centipede" width="100%" height="700" allowfullscreen="true"> </iframe>
</figure>
