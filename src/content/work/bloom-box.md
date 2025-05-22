---
title: Integration de données dans un datawerehouse
publishDate: 2019-12-01 00:00:00
img: /assets/stock-4.jpg
img_alt: A bright pink sheet of paper used to wrap flowers curves in front of rich blue background
description: |
  L’alimentation d’un entrepôt de données à partir de sources existantes.
tags:
  - Dev
  - Branding
  - Backend
---

#### <span style="color: #900C3F "><strong>1.Presentation de la SAE</strong> </span></br>

 <span style="color: #900C3F ">Le sujet de la SAE </span> <br/>
Le travail consistait à mettre en place les flux de données dans talend permettant d’alimenter l’entrepôt de données. L'objectif était d'améliorer la qualité des données venant de la base de données sources afin d'alimenter l'entropôt des données propres, sans valeurs abérantes.

 <span style="color: #900C3F "><strong>Livrables attendus </strong> </span></br>
Des captures d'écran du travail réalisé sur Talend et Oracle </br>

<span style="color: #900C3F "><strong>Nombre de participants:</strong> </span></br>
 2 personnes ont travaillé sur ce projet :</span> </br>   
   <span style="color:#030C4A"> <strong>BAKALA Sergina - Auxane BIKOUTA </strong></span> </br>

 <span style="color: #900C3F "><strong>Organisation de travail de cette SAÉ (Projet, série de TP, jeu d’entreprise, …):</strong> </span></br> 
La SAE était organisé en Serie de TD.


 <span style="color: #900C3F "><strong>Temps de travail sur la SAE</strong> </span></br>
  <table border="1">
        <tr>
            <th>Temps total pour l'équipe</th>
            <th>Temps que vous avez personnellement passé </th>
        </tr>
        <tr>
            <td>28h</td>
            <td>14h</td>
</table>

##### <span style="color: #900C3F "> 2. Presentation générale des travaux réalisés </span>

Pour commencer j'ai fait un travail de préparation, J'ai crée des sources de données dans Oracle, la zone de staging ou d'extraction de données, l’entrepôt et les connexions TALEND et 4 jobs ou interfaces de travail dans TALEND. Par suite, j'ai mis en œuvre des flux d’extraction de données à partir des sources pour alimenter les espaces de stockages correspondants aux schémas d’extraction (table par table). J'ai traité les données rejetées via un Tmap dans TALEND. J'ai utilisé un TAggregratepour que dans les tables de VentesW aucun doublon. Pour l'étape 2, J'ai mis en œuvre des flux d’intégration de données à partir de données extraites (donc à partir de tables dans EZVentesD et EZVentesW) pour alimenter l’espace de stockage correspondant au schéma intégré.

##### <span style="color: #900C3F ">3.	Preuves de l’acquisition de la compétence</span>
<table border="1">
        <tr>
            <th>N° de la preuve </th>
            <th>Lien hypertexte vers la page moodle </th>
            <th>Commentaires</th>
            <th>Extrait écran de la preuve </th>
        </tr>           
            <td>
                <select>
                    <option value="1">1</option>
                    <option value="2">2</option>
                    <option value="3">3</option>
                    <option value="4">4</option>
                    <option value="5">5</option>
                    <option value="6">6</option>
                    <option value="7">7</option>
                </select>
            </td>
            <td> </td>
</table>

#####  <span style="color: #900C3F ">4.Monter en compétence avec une SAÉ</span>
Le travail de préparation et d'implémentation dans le domaine de l'intégration de données avec Oracle et Talend a contribué significativement en ce qui concerne la montée en compétence. La création de sources de données dans Oracle, la conception d'une zone de staging, et la mise en œuvre de connexions et de jobs dans Talend m'ont permis d'avoir une bonne compréhension des outils utilisés dans le domaine de l'intégration de données (Talend,Oracle,Access,...).Aussi, La mise en œuvre de flux d'extraction depuis différentes sources pour alimenter des espaces de stockage correspondants montre que j'ai acquis la capacité à concevoir des solutions complexes dans le processus d'intégration de données. La manipulation des données rejetées à l'aide d'un TMap dans Talend m'a permis de comprendre que j'ai acquis la capacité de gérer les cas d'exception et d'assurer une qualité de données élevée en traitant les erreurs de manière appropriée. J'ai pu dans cette SAE garantir l'absence de doublons dans les tables de VentesW avec l'utilisation du composant TAggregate j'ai acquis la capacité à résoudre des problématiques spécifiques liées à la qualité des données.

##### <span style="color: #900C3F "> La SAÉ est adossée aux apprentissages critiques suivants :  </br> </span>
 <span style="color:#C70039"> <strong> Compétence : Traiter des données à des fins décisionnelles</strong> </span></br>
 <span style="color:#C70039"> Niveau 2 : Automatiser le traitement de données multidimensionnelles </span>

| Code_AC | Nom_AC                                                |
|---------|-------------------------------------------------------|
| AC1     | Comprendre l'organisation des données de l'entreprise |
| AC2     |Réaliser le rôle central et spécifique de l'entrepôt de données dans la chaine décisionnelle|
| AC3     | Identifier et résoudre les problèmes d’intégration de sources complémentaires et hétérogènes |
| AC4     | Comprendre la nécessité de tester, corriger et documenter un programme |
| AC5     | Apprécier l’intérêt de briques logicielles existantes et savoir les utiliser |


<!DOCTYPE html>
<html>
<head>
     <meta charset="utf-8" />
    <title>Tableau sur l'acquisition des compétences</title>
</head>
<body>
    <table border="1">
        <tr>
            <th>Apprentissages critiques de la compétence</th>
            <th>Auto-évaluation de la compétence</th>
        </tr>
        <tr>
            <td>AC1</td>
            <td>
                <select>
                    <option value="acquis">Acquis</option>
                    <option value="en_cours">En cours d'acquisition</option>
                    <option value="non_acquis">Non acquis</option>
                </select>
            </td>
          </tr>
        <tr>
            <td>AC2</td>
            <td>
                <select>
                    <option value="acquis">Acquis</option>
                    <option value="en_cours">En cours d'acquisition</option>
                    <option value="non_acquis">Non acquis</option>
                </select>
            </td>
          </tr>
        <tr>
            <td>AC3</td>
            <td>
                <select>
                    <option value="acquis">Acquis</option>
                    <option value="en_cours">En cours d'acquisition</option>
                    <option value="non_acquis">Non acquis</option>
                </select>
            </td>
             </tr>
        <tr>
            <td>AC4</td>
            <td>
                <select>
                    <option value="acquis">Acquis</option>
                    <option value="en_cours">En cours d'acquisition</option>
                    <option value="non_acquis">Non acquis</option>
                </select>
            </td>
        </tr>
        <tr>
            <td>AC5</td>
            <td>
                <select>
                    <option value="acquis">Acquis</option>
                    <option value="en_cours">En cours d'acquisition</option>
                    <option value="non_acquis">Non acquis</option>
                </select>
                </td>
        </tr>
    </table>
</body>
</html>

                  
<span style="color:#FFC300"><strong> Valoriser une production dans un contexte professionnel </strong> </span></br>
 <span style="color:#FFC300"> Niveau 2 : Restituer et argumenter ses résultats <span style="color:#5E1019">
 | Code_AC | Nom_AC                                                |
 |---------|-------------------------------------------------------|
 | AC3     | Saisir la nécessité de choisir des indicateurs pertinents pour communiquer sur les résultats|
 | AC4     |Prendre conscience de la rigueur requise dans ses productions et dans la communication à leur propos|

 <!DOCTYPE html>
<html>
<head>
     <meta charset="utf-8" />
    <title>Tableau sur l'acquisition des compétences</title>
</head>
<body>
    <table border="1">
        <tr>
            <th>Apprentissages critiques de la compétence</th>
            <th>Auto-évaluation de la compétence</th>
        </tr>
        <tr>
            <td>AC3</td>
            <td>
                <select>
                    <option value="acquis">Acquis</option>
                    <option value="en_cours">En cours d'acquisition</option>
                    <option value="non_acquis">Non acquis</option>
                </select>
                </td>
        </tr>
         <tr>
            <td>AC4</td>
            <td>
                <select>
                    <option value="acquis">Acquis</option>
                    <option value="en_cours">En cours d'acquisition</option>
                    <option value="non_acquis">Non acquis</option>
                </select>
                </td>
        </tr>
    </table>
</body>
</html>

##### <span style="color: #900C3F ">5. Les composantes essentielles</span>

La SAÉ aborde les compétences suivantes pour lesquelles sont rappelées les composantes essentielles : 

<span style="color:#C70039"><strong> Traiter des données à des fins décisionnelles </strong> </span></br>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Compétences CE1</title>
</head>
<body>

<ul>
  <li><span style="color:#C70039; font-weight:bold">CE1.01 | En intervenant à toutes les étapes du cycle de vie de la donnée (insertion, modification, extraction, suppression)</span></li>
  <li><span style="color:#C70039; font-weight:bold">CE1.02 | En utilisant le modèle de données adapté aux besoins</span></li>
  <li><span style="color:#C70039; font-weight:bold">CE1.03 | En s’inscrivant dans une démarche de documentation des réalisations adaptée au public visé</span></li>
  <li><span style="color:#C70039; font-weight:bold">CE1.04 | En traduisant correctement les demandes métier en programmes, avec le respect du cahier des charges s'il existe</span></li>
  <li><span style="color:#C70039; font-weight:bold">CE1.05 | En écrivant un programme correctement structuré et documenté, respectant les bonnes pratiques</span></li>
  <li><span style="color:#C70039; font-weight:bold">CE1.06 | En identifiant les librairies et langages dédiés</span></li>
</ul>
</body>
</html>


 Parmi les composantes essentielles adossées à cette compétence, lesquelles ont été mobilisées par la SAÉ ? Ai-je le sentiment que la SAÉ vous a permis de progresser sur ces composantes essentielles de la compétence.
<table border="1">
  <thead>
    <tr>
      <th>Code</th>
      <th>Compétence</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CE1.01</td>
      <td>Intervenir à toutes les étapes du cycle de vie de la donnée</td>
      <td>Nous avons opéré à toutes les phases du cycle de vie des données, de l'insertion à la mise à jour en passant parfois par la suppression des valeurs aberrantes et la création de nouvelles données telles que les identifiants des clients, afin d'alimenter l'entrepôt de données. La SAÉ a renforcé ma compréhension du cycle de vie des données.</td>
    </tr>
    <tr>
      <td>CE1.05</td>
      <td>Écrire un programme correctement structuré et documenté</td>
      <td>Cette SAÉ m'a permis d'améliorer ma capacité à produire des flux de données pour les processus ETL bien structurés, et conformes aux bonnes pratiques.</td>
    </tr>
    <tr>
      <td>CE1.06</td>
      <td>En identifiant les librairies et langages dédiés</td>
      <td>Durant cette SAE plusieurs composantes Talend ont été mobilisées. Pour traiter les données rejetées nous avons utilisé un <span style="color:red">TMAP</span> et pour la visualisation des résultats <span style="color:red">TLOGROW</span>; pour la suppression des doublons nous avons utilisé <span style="color:red">TAGGREGATE</span> qui joue à peu près le rôle d'un <span style="color:red">Group by</span> en SQL. Cette SAE m'a permis de progresser tout en apprenant les différentes composantes de TALEND.</td>
    </tr>
  </tbody>
</table>

</body>
</html>


 <span style="color:#FFC300"> <srtong> Valoriser une production dans un contexte professionnel </strong> </span></br>
<!DOCTYPE html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Compétences CE3</title>
</head>
<body>

<ul>
  <li><span style="color:#FFC300">CE3.01 | En s’adaptant au niveau d’expertise, à la culture et au statut du destinataire</span></li>
  <li><span style="color:#FFC300">CE3.02 | En s’exprimant correctement, aussi bien en français qu’en anglais, à l'oral comme à l'écrit</span></li>
  <li><span style="color:#FFC300">CE3.03 | En veillant aux aspects éthiques, déontologiques et réglementaires d’utilisation et de diffusion des données</span></li>
  <li><span style="color:#FFC300">CE3.04 | En interprétant et contextualisant les résultats (citations, vérification des sources, esprit critique)</span></li>
  <li><span style="color:#FFC300">CE3.05 | En utilisant la forme de restitution adaptée</span></li>
  <li><span style="color:#FFC300">CE3.06 | En tenant compte des réalités économiques et managériales des entreprises</span></li>
</ul>
</body>
</html>
Parmi les composantes essentielles adossées à cette compétence, lesquelles ont été mobilisées par la SAÉ ? Ai-je le sentiment que la SAÉ vous a permis de progresser sur ces composantes essentielles de la compétence. </br>

Par rapport au travail réalisé dans cette SAE,je pense qu'il y'a qu'un composante essentielle adossée à cette compétence mobilisée par cette SAE .
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Compétences en traitement des données</title>
</head>
<body>

<table border="1">
  <thead>
    <tr>
      <th>code</th>
      <th>Compétence</th>
      <th>Description</th>
    </tr>
  </thead>
    <tr>
      <td> CE3.05 </td>
      <td> | En utilisant la forme de restitution adaptée </td>
      <td> dans notre cas c'était la base de données ordonnée avec toutes les données bien saisies et mis à jour.</td>
    </tr>
</table>
</body>
</html>

#### <span style="color: #900C3F "> 6.Autres éléments d’appréciation</span>

<strong>A quelles difficultés/challenges j'ai été confrontés ? (Compréhension de la demande, tenue des délais, charge de travail trop importante par rapport aux heures attribuées, difficultés au sein d’une équipe, maîtrise d’un langage de programmation insuffisante ,…) ai-je réussi à les surmonter ? </strong></br>

  Nous avons principalement été confrontés à un probleme d'insuffisance dans la maîtrise de la méthodologie pour intégrer les données dans l'entropôt, pour gerer les valeurs aberantes dans Talend.

<strong>Cette SAÉ m'a-t-elle permis de comprendre et/ou atteindre personnellement les attentes professionnelles du domaine, vis-à-vis de chaque compétence visée ? </strong></br>
  Cette SAÉ n'a pas pleinement répondu à mes attentes en termes de compréhension et d'atteinte des compétences professionnelles spécifiques au domaine. Plusieurs facteurs ont contribué à cette situation :

Difficultés Techniques Non Résolues :
Les difficultés techniques rencontrées, notamment dans le domaine de la manipulation de talend et dans la recuperation des fichiers, n'ont pas été pleinement résolues malgré les efforts déployés.

<strong>Quels éléments de notre travail assurent de la qualité professionnelle des livrables rendus ? </strong> </br>
  L'alimentation des tables Clients et commandes dans l'entropôt.

<strong>Quelle contribution personnelle pourrai-je valoriser vis-à-vis de mon implication dans cette SAÉ ?</strong></br>

  La contribution personnelle que je pourrai valoriser vis-à-vis de mon implication dans cette SAÉ serait la génération des données dans la tables clients cibles et le nettoyage de la colonne date dans la table commande.

<strong>Autres éléments que je souhaite partager ?</strong></br>

  Cette SAÉ a été affectée par une lacune dans l'explication du fonctionnement de Talend. En effet, la compréhension de l'outil Talend était cruciale pour la réalisation de certaines tâches, mais la clarification et les explications nécessaires n'ont pas été fournies de manière adéquate.

