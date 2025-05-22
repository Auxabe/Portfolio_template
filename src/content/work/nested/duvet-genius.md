---
title: Développement d'un composant d'une solution décisionnelle
publishDate: 2020-03-04 00:00:00
img: /assets/stock-1.jpg
img_alt: Pearls of silky soft white cotton, bubble up under vibrant lighting
description: |
  SAE401
tags:
  - Dev
  - Branding
  - Backend
---

#### <span style="color: #900C3F "><strong>1.Presentation de la SAE</strong> </span></br>

 <span style="color: #900C3F "><strong>Le sujet de la SAE </strong></span> <br/>

 L’objectif du projet etait de mettre en place un système décisionnel permettant de piloter la fréquentation des stations de vélos et de mesurer l’impact de la météo sur cette fréquentation.Nous devions pour la  réalisation du projet, recueilli les données sur openData des 5 stations de vélo (Nantes, Marseille, Lyon, Rennes,La Rochelle)




<span style="color: #900C3F "><strong>Organisation de travail de cette SAÉ (Projet, série de TP, jeu d’entreprise, …):</strong> </span></br> 
C'etait un projet, nous avions plusieurs seances de TD.



##### <span style="color: #900C3F "> 2. Presentation générale des travaux réalisés </span>.


 <span style="color: #900C3F "><strong>Livrables attendus </strong> </span></br>
 - Flux d'extraction Talend  </br> 
  - Rapport Power BI </span> </br> 
 - La présentation Orale </span> </br> 
 



<span style="color: #900C3F "><strong>Organisation de travail de cette SAÉ (Projet, série de TP, jeu d’entreprise, …):</strong> </span></br> 
C'etait un projet, nous avions plusieurs seances de TD.


##### <span style="color: #900C3F "> 2. Presentation générale des travaux réalisés </span>
Au cours de cette SAE , nous avons procédé à l'extraction de données à partir de cinq stations de vélo (Nantes, La Rochelle, Lyon, Rennes, Marseille) ainsi que des données météorologiques depuis l'OpenData, en utilisant Talend comme outil d'intégration de données. L'extraction des données a été réalisée en conformité avec le Modèle Conceptuel de Données (MCD) initial, lequel était constitué de quatre tables. Parmi ces tables, trois étaient des dimensions : StationVelo, Temps, et Statut, et une quatrième table était une table de faits regroupant l'ensemble des mesures.

Les données extraites des différentes stations ont été fusionnées dans une unique table de dimension StationVelo, en utilisant une base de données Oracle. Cette base de données contenait également les données pour les dimensions Temps et Statut. Cette étape de fusion a permis de regrouper les informations spécifiques à chaque station dans une structure unifiée, facilitant ainsi leur manipulation et leur analyse ultérieure.

Ensuite, nous avons élaboré un rapport Power BI pour présenter la supervision des stations de vélos. Ce rapport fournissait une vue d'ensemble de la disponibilité des vélos dans chaque station, ainsi que des informations sur leur utilisation. Il permettait également de suivre l'évolution de la fréquentation des stations au fil du temps.

En parallèle, nous avons exploré la corrélation entre les données météorologiques et la fréquentation des stations de vélo. En analysant les variations de la météo (telles que la température, les précipitations, etc.) en relation avec l'utilisation des vélos dans les différentes stations, nous avons cherché à identifier des tendances ou des patterns qui pourraient influencer la demande de vélos.

#####  <span style="color: #900C3F ">4.Monter en compétence avec une SAÉ</span>
Cette SAE m'a permis de monter en compétences en ce qui concerne le développement d'outils décisionnels et à la manipulation de données à des fins décisionnelles :

En effet, cette SAE a impliqué l'extraction et le traitement de données provenant de différentes sources API, notamment des stations de vélos et des données météorologiques. Cela a nécessité la mise en œuvre de processus d'intégration de données des fichiers Json  à l'aide de Talend grace à l'utilisation de TresClients dans lequel il fallait mettre le lien de API, ainsi que la consolidation de ces données dans une base de données Oracle avec les données extraites dans Talend. En manipulant ces données, en les transformant et en les consolidant dans un format cohérent, J'ai acquis des compétences pratiques dans le traitement des données en vue de leur utilisation pour la prise de décision.

Aussi,en élaborant un rapport Power BI pour présenter la supervision des stations de vélos et analyser la corrélation entre les données météorologiques et la fréquentation des stations, j'ai appris à valoriser leurs résultats de manière professionnelle.Elle a permis de présenter efficacement des informations complexes de manière visuellement attrayante et facilement compréhensible.

Par suite ,en examinant les tendances de la fréquentation des stations de vélos en relation avec les conditions météorologiques, j'ai développé des compétences en analyse et interprétation des données. Comprendre comment les variables telles que la météo peuvent influencer le comportement des utilisateurs de vélos est crucial pour prendre des décisions éclairées en matière de gestion des ressources et d'optimisation des services.

portofolio_template



