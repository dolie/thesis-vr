<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [La réalité virtuelle & la réalité augmentée comme outil de programmation informatique.](#la-r%C3%A9alit%C3%A9-virtuelle--la-r%C3%A9alit%C3%A9-augment%C3%A9e-comme-outil-de-programmation-informatique)
  - [Remerciements](#remerciements)
  - [Introduction](#introduction)
    - [Mes lectures : les idées qui m'interpellent.](#mes-lectures--les-id%C3%A9es-qui-minterpellent)
    - [Ma problématique préférée](#ma-probl%C3%A9matique-pr%C3%A9f%C3%A9r%C3%A9e)
    - [Mes hypothèses, réponses possibles, comment les vérifier.](#mes-hypoth%C3%A8ses-r%C3%A9ponses-possibles-comment-les-v%C3%A9rifier)
    - [Conception centrée utilisateur](#conception-centr%C3%A9e-utilisateur)
    - [Les outils](#les-outils)
  - [Phase d'Inspiration](#phase-dinspiration)
    - [Définission du cadre du problème](#d%C3%A9finission-du-cadre-du-probl%C3%A8me)
    - [Les entretiens](#les-entretiens)
    - [Immersion](#immersion)
  - [Phase d'idéation](#phase-did%C3%A9ation)
    - [Rétrospective des entretiens et de l'immersion](#r%C3%A9trospective-des-entretiens-et-de-limmersion)
    - [Formulation des problématique.](#formulation-des-probl%C3%A9matique)
    - [Atelier *Comment ferions-nous pour*](#atelier-comment-ferions-nous-pour)
    - [Reflexion sur les idées](#reflexion-sur-les-id%C3%A9es)
    - [Regroupement d'idées, recherches.](#regroupement-did%C3%A9es-recherches)
    - [D'autres méthodes de programmation.](#dautres-m%C3%A9thodes-de-programmation)
      - [Modélisation](#mod%C3%A9lisation)
      - [Paradigme de programmation](#paradigme-de-programmation)
      - [Divergence de la programmation VR et de la programmation logiciel.](#divergence-de-la-programmation-vr%C2%A0et-de-la-programmation-logiciel)
      - [La programmation logique, ce qui existe.](#la-programmation-logique-ce-qui-existe)
      - [Premier retour des tests](#premier-retour-des-tests)
      - [Méthode encore immature](#m%C3%A9thode-encore-immature)
    - [Développement dans la VR](#d%C3%A9veloppement-dans-la-vr)
      - [Problématique de visibilité.](#probl%C3%A9matique-de-visibilit%C3%A9)
      - [Voir son clavier au travers du casque.](#voir-son-clavier-au-travers-du-casque)
      - [Place du clavier dans l'espace de travail.](#place-du-clavier-dans-lespace-de-travail)
      - [Intégration aux outils existants, et ce qui existe.](#int%C3%A9gration-aux-outils-existants-et-ce-qui-existe)
      - [Design d'Interface de programmation VR](#design-dinterface-de-programmation-vr)
  - [Tester son design](#tester-son-design)
    - [StoryBoard](#storyboard)
    - [Retours utilisateurs](#retours-utilisateurs)
  - [Conclusion](#conclusion)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# La réalité virtuelle & la réalité augmentée comme outil de programmation informatique.

## Remerciements
Je voudrais remercier le corps enseignant de l'école des Gobelins, pour leur expertise, leur écoute, et leur accompagnement, mon tuteur Cyril Renaud pour m'avoir soutenu et fait confiance durant cette année d'apprentissage, ainsi que le Président Directeur Général et le Directeur Général de Zenika, Carl Azoury et Laurent Delvaux, pour l'encouragement qu'ils m'ont témoigné lorsque j'ai souhaité reprendre mes études. Merci.

## Introduction - Français

`Les outils informatiques actuels — écran, clavier, souris… — ont été conceptualisés pour un besoin spécifique. Leur usage était majoritairement destiné à un format plat : écriture, visionnage d'image, calculs… La conception de ces outils materiel et logiciel, n'avait pas vu l'arrivée d'un média de nouvelle génération. Le besoin a évolué et les technologies aussi. Des innovations sont apparues, et les casques de réalité virtuelle sont devenus de plus en plus performants. Leur usage s'inscrivent dorénavant dans notre quotidien. Mais les outils utilisés pour les créer, eux, n'ont pas changé. Il y a une réelle dichotomie entre l'utilisation du materiel de réalité virtuelle et ce qu'il peut nous offrir. Les casques sont utilisés pour visionner le travail accompli. Pourquoi ne pas l'utiliser comme outil de travail ?` 
`J'ai effectué au travers de ce mémoire des intretiens utilisateurs et des recherches documentaires en suivant une méthodologie UX. Le but fut de comprendre les besoins et désirs des développeur de réalité virtuelle. Cela m'a permis de comprendre les problèmes ergonomiques qui se posent actuellement dans la sphère réalité virtuelle. Je fut guidé par l'envie de rendre plus intuitif et productif, l'utilisation de ces outils de conception et de réalisation de ce nouveau média.`

## Introduction - English

`The current IT tools - screen, keyboard, mouse ... - have been designed for a specific need. Their use was mainly intended for a flat format: writing, image viewing, calculations ... The design of these hardware and software tools, had not seen the arrival of a new generation of media. The need has evolved and the technologies too. Innovations have emerged, and virtual reality headsets have become more and more efficient. Their use is now part of our daily lives. But the tools used to create them, they have not changed. There is a real dichotomy between the use of virtual reality equipment and what it can offer us. Virtual reality headsets are only used to view and experience. Why not use it as a design and development tool?`
`I carried out through this thesis users interviews and documentary researches following an UX methodology. The goal was to understand the needs and desires of VR developers. This allowed me to find out ergonomic issues that currently arise in the virtual reality sphere. I was guided by the desire to make the use of these tools more intuitive and productive.`

### Mes lectures : les idées qui m'interpellent.
  * [Recherches de Mike Alger sur le design des interfaces VR](https://www.youtube.com/watch?v=id86HeV-Vb8) 
  * [Mémoire de Mike Alger](https://drive.google.com/file/d/0B19l7cJ7tVJyRkpUM0hVYmxJQ0k/view)
  * [Les bonnes et les mauvaises choses du design d'outils en VR](http://blog.leapmotion.com/designing-vr-tools-good-bad-ugly/)
  * [Les interfaces de programmation visuelle, différentes formes pour différents types](https://medium.com/@stevekrouse/types-are-shapes-d6af1e83192f)

### Ma problématique préférée

Les interfaces de programmations en Réalité Virtuelle et Réalité Augmentée

_Qui_ ? Les développeurs
<br>_Quoi_ ? La développement de jeux, web & logiciel.
<br>_Où_ ? Dans la VR/AR, au bureau.
<br>_Quand_ ? Dans un futur proche.
<br>_Comment_ ? A l'aide de nouvelles interfaces, visuelles, 3D…
<br>_Pourquoi_ ? Les outiles utilisés sont inadaptés aux développement VR. Pourtant, le materiel VR possède de nombreux avantages pour la productivité et le confort.
<br>_Combien_ ? Gratuit.

### Mes hypothèses, réponses possibles, comment les vérifier.

Les outils utilisés aujourd'hui ne sont pas adaptés au développement d'expèrience en réalité virtuelle. La combinaison écran et clavier ne suffisent plus au développement d'expèrience virtuelle dans un espace en trois dimension. L'invention de ces outils ont été fait pour des usages plats : l'écriture, l'affichage d'images etc… 
Pour un usage différent, les outils se doivent d'être différent.

Selon Mike Alger, la VR ne serait pas adaptée à l'écriture et à la lecture de texte. Hors les progrès technologique ont permis une meilleure résolution des écrans et la lecture de textes en VR est devenu désormait possible et tout à fait accessible. Cependant, il vrai que la rédaction de texte est aujourd'hui difficile en réalité virtuelle. Lors de l'utilisation de casque VR, la vue est coupée de l'environnement extèrieur. Il est donc difficile, presque impossible, d'utiliser un clavier si l'on ne pratique pas la dactylographie (définition).

User de la réalité virtuelles n'a pas que des inconvénients. Bien au contraire. L'ajout d'une troisième dimension et l'immersion de l'utilisateur dans cet espace a de nombreux avantages.
Elle permet une meilleure visualisation et construction de systèmes complexes (ref cosmonautes visualisation du terrain de mars). Les jeux et programmes informatiques entrent dans la classe des systèmes complexes.
Elle permet une spatialisation de l'espace de travail. Cette spacialisation permet une répartition des taches sur un plus grand espace de travail qu'un écran de 15 pouces. Selon le design de Mike Alger, l'espace de travail «utile» — c'est à dire l'espace utilisable sans contraintes de vue et de mouvement — en réalité virtuelle permettrait d'utiliser une surface équivalente à 8 écrans 27 pouces (ref). Hors il a été prouvé que la multiplication des écrans permettait un gain de productivité jusqu'à 40%. 

Si nous voulons créer des expèriences en réalité virtuelle de manière efficace et de meilleure qualité, nous ne devons plus utiliser les appareils VR comme simple medium de visualisation. Nous devons les utiliser comme des outils à part entière, pour qu'ils soient partie intégrante de la phase de développement. Ceci signifie qu'il faut repenser l'utilisation des outils actuels : écrans, clavier, souris, casque VR, contrôleur VR… Cette analyse fonctionnelle et cette reflexion ergonomique doit se faire autant d'un poin de vue physique, que logiciel. 

---

https://www.youtube.com/watch?v=TCHoQAT5LK8 Michel Bigan maitre de conférence centrale lille.

## Contexte

### Motivation personnelle

### Question primaire

### Processus de recherche

### Conception centrée utilisateur
Afin de conceptualiser la meilleur solution possible, je vais utiliser la méthodologie de conception centré utilisateur décrite par IDEO. 
Une conception centrée sur l'humain c'est comprendre que la personne concernée par la problématique est la première personne à pouvoir nous aider. Elle informera précisément et révélera les problématiques les plus pertinentes.
Ce sont eux qui sont la clé de la solution.
Le processus se décrit en trois grande phases : 
  - Inspiration : ici, l'utilisateur est observé, étudié, questionné. Le but est d'accumuler un maximum d'information afin de comprende la problématique de manière optimale.
  - Idéation : cette phase permet l'emulsion d'idée. Elle est très fertile et créative. Toute les solutions sont imaginées sans limites, discutées, débatues, prototypées,testées, acceptée ou réfutées…
  - Inplémentation : enfin, on imagine comment intégrer notre solution dans son contexte initial.

Cette méthodologie permet d'avoir un inpact réel. Cela se traduit par la production d'une solution désirable, faisable technologiquement, et viable financièrement.

### Les outils
Les outils existants sont innombrables. Par exemple, IDEO en répertorie 57 dans son guide pratique. Chaque projet est unique. Ainsi certains sont plus pertinents que d'autres suivant le contexte. Les outils choisis pour cette étude sont les suivants :
  - Définition du cadre du défi conceptuel
  - Créer un plan de projet
  
  - Entretiens
  - Immersion

  - degager les thèmes
  - Formulation des problématiques
  - Comment ferions nous pour
  - Créer des représentations visuelles
  - brainstorming
  - Regroupements d'idées
  - Dégager un concept
  - Vérifier l'intuition
  - Choisir les idées à prototyper
  - Story board
  - Prototypage rapide

## Phase d'Inspiration
Dans cette phase d'inspiration, il s'agit de s'ouvrir aux autres, afin d'apprendre et de comprendre la vision et ce que ressente les utilisateurs, et déceler leur désirs. La première des qualité à avoir pendant cette phase est bien évidemment l'empathie.  

### Définission du cadre du problème
Quel est le problème que vous essayez de résoudre ?
  Le problème que j'essaie de résoudre concerne la réalité virtuelle. J'aimerais faciliter le travail des développeurs en réalité virtuelle.

  1. Exprimez-le sous la forme d’une question.
    Comment optimiser le développement de jeux vidéos, et expèrience VR ? Comment rendre le développement plus facile ? Comment le rendre plus intuitif ?

  2. Maintenant, énoncez l’impact optimal que vous espérez produire.
    Les développeur VR sentent un développement plus intuitif, et ressentent un gain en productivité. Il sentent les outils materiels et logiciels parfaitement adaptés au développement en VR. 

  3. Quelles sont les solutions possibles à votre problème ? Pensez large. C’est bien d’aborder un projet avec une ou deux idées sur la solution, mais assurez-vous qu’elles soient suffisamment ouvertes pour permettre des résultats surprenants.
    Revoir l'utilisation du casque, du clavier, de la souris, la manière de développer pour une utilisation plus appropriée.
  4. Enfin, notez le contexte et les contraintes auxquels vous êtes confronté. Il peut s’agir de contraintes géographiques, technologiques, chronologiques ou concernant la population que vous essayez d’atteindre.
    Les contraintes existantes sont, de par la naissance de la technologie, le peu de personnes développant des expèriences VR, et les outils peu nombreux.  
  5. Votre question initiale a-t-elle besoin d’être affinée ? Recommencez

### Les entretiens
Les entretiens se trouvent au cœur de la phase d'Inpiration de la conception centrée utilisateur. En effet, ils permettent de cerner et comprendre les besoins des utilisateurs ainsi que leur aspirations.
En annexe, le guide d'entretien.

**Questions générales**
Quel age as-tu ? 
Ou vis-tu ? 
Dans quelle branche de métier travail tu ? 
Quel poste occupes-tu ? 
Quel fais-tu au quotidien ?

**Questions plus précises à la VR**
Dans quel cadre utilises-tu la VR ?
Que fais-tu avec la VR ?
Dans quel but ? 
À quoi ressemble ton espace de travail ?
Quels outils materiel et logiciels utilises-tu ?
Peux-tu me décrire ton processus de travail ? Quelles sont les tâches que tu effectue le plus souvent ?

Qu'elles sont les choses que tu aimes le plus dans ton processus de création ?
Qu'elles sont les choses que tu aimes le moins dans ton processus de création ?

Es-tu satisfait de tes conditions de travail ? Détails ?
Quels sont les qualité et les faiblesses des outils que tu utilise ? 
Quelles problématiques rencontres-tu dans ton processus de création ?
Y-a-il des choses qui te rendent plus productives ? lesquelles ? 
Y-a-il des choses qui te rendent moins productives ? Si oui lesquelles ?
Penses-tu qu'il est possible d'améliorer tes conditions de travail ? Si oui, comment ?

---

Samy
23 ans
Ile de france
Je travaille dans l'informatique, le développement web
Je suis développeur web
Au quotidien je développe des sites internets

Occasionnelement les client me demandent créer des pages web qui intègre de la réalité virtuelle.
J'intègre des maquettes dans un scènes 3D, et j'y ajoute de la logique, des interactions. 
Cela permet soit de montrer l'expertise du client dans le domaine de l'IT en générale, de sa pluridisciplinarité, soit pour créer une expèrience originale pour le visiteur du site.
Je travaille dans un openspace, avec d'autres développeur. J'ai un espace de travail plutot spacieux
J'ai un Mac et un casque VR, je développe avec Visual Studio Code. J'utilise principalement Vue et A-frame pour la VR.
Je travaille en étroite collaboration avec les designer. Ils me fournisse des maquettes, des illustrations, des assets 3D, et beaucoup d'explication sur ce qu'ils veulent faire. Ensuite je développe afin d'intégrer les éléments dans la scène en 3D. Je passes aussi beaucoup de temps sur l'inspector d'A-frame à placer les éléments et à visualiser le rendu.
J'aime construire des choses qui sont visuellement belles, même si je ne voit pas tout de suite où les designer veulent en venir. Mais je leur fait confiance et en général ça rends super. 

Quand ça bug ahaha, plus sérieusement, placer les éléments étapes par étapes est assez long. De plus, A-frame n'est pas aussi que d'autre logiciels tels que Unity par exemple. Manipuler la scène 3D et ses éléments n'est pas facile et assez long. Pareil pour tester.
Oui je suis satisfait de mes conditions de travail.

Comme je le disais, A-frame n'est qu'à ses débuts et il lui manque beaucoup de fonctionnalités. Et pourtant c'est le meilleur que l'on trouve en ce moment pour le développement VR dans le Web. Le déplacement dans la scène n'est pas possible, ni la rotation. Du coups je suis obliger de bouger ou incliner les objets afin d'atteindre des endroit inaccessible. Passer de l'IDE à la visualisation est aussi quelque-chose de répétitif. C'est comme si je peignait dans une pièce et que je devait me rendre dans une autre pièce de la maison pour voir ce que ça donne.
Si je peux avoir un écran supplémentaire, ça me permet de visualiser la scène sur un écran, et développer sur l'autre.
Devoir mettre mon téléphone dans le casque VR pour voir ce que ça donne et que finalement ça ne donne pas du tout le rendu espéré, c'est assez fatiguant. Car je dois faire des allez-retour entre écran et casque jusqu'à ce que ce soit bon.
Je ne sais pas trop… Je penses qu'avoir plus de fonctionnalités dans A-frame, ou un meilleur casque, ou une synchronisation plus rapide entre outils de développement et visionneuse…

---

Nicolas
24 ans
Paris
Je travaille dans le développement web
Je suis développeur JavaScript
Je développe des site web et je fais du consulting. J'accompagne mes clients dans la recherche de solution à leur besoins.

Je suis développeur de jeux vidéos amateur, je fais ça chez moi pendant mon temps libre le soir. En ce moment j'essaie la VR.
Je fais ça pour mon plaisir personnel, mais aussi pour partager à mes potes ou sur des plateformes comme itch.io .
Je travaille dans ma chambre, j'ai un bureau, un ordinateur. Elle est assez spatieuse pour contenir mon HTC Vive.
En plus de mon ordinateur et de mon htc vive, j'utilise Unity, et depuis peu blender pour retoucher certains modèles 3D.
En général j'ai une idée de jeu que je veux faire. J'imagine le contexte, je vais chercher les assets sur le store unity, puis je commence à créer la scène dans Unity et à placer les assets. Une fois que la scène commence à ressembler à quelque chose, je commence à développer la mécanique et l'IA sur MonoDevelop. Ah oui j'utilise monodevelop aussi, c'est un outil pour développer qui vient avec Unity et qui s'intègre avec les fonctions de celui-ci.
Ce que je fais le plus souvent c'est placer les objets dans la scène, développer et tester le jeu.

Ce qui me passionne c'est donner vie à mes idées. Et voir le tout fonctionner.
Ce qui me plait le moins c'est de chercher des assets pendant des heures et ne pas trouver quelquechose qui correspond à mes attentes. C'est d'ailleurs pour ça que je me suis mis à Blender. J'adore développer, mais construire la scène est très long si je veux placer les éléments comme je veux. Concernant la VR, devoir mettre son casque, enlever son casque, mettre son casque etc, c'est carrément super c****t. Pareil pour les controleur : se lever de son bureau, prendre les contrôleurs, mettre son casque, essayer, voir que ça ne marche pas, se baisser pour poser ses contrôleurs sur le sol, enlever son casque, retourner s'asseoir pour corriger les problèmes, et recommencer. C'est très fatiguant !

Oui je suis satisfait de mes conditions de travail en général, j'ai d'excellents outils mais c'est vrai qu'il y a quelque chose qui cloche pour la VR. 
Unity est vraiment très puissant, voir un peu trop parfois. Mais le développement VR est pas du tout adapté avec l'écran et le clavier.
La séparation code / scène a ses qualitées, comme ses défaut. Cela permet de ne pas tout avoir au même endroit, même si passer de l'un à l'autre pour tester est fatiguant, et encore plus pour la VR.

Un bon café ou une boisson energisante pour ne pas citer de marques me rendent plus productif. J'aime travailler en musique aussi. J'ai trouvé une technique aussi récemment pour aller plus vite pour mon Jeu VR : Je garde le casque sur la tête et je pose mes contrôleurs sur le bureau. C'est vite le bazar et ça me fais un peu mal à la tête mais quand ça ne marche pas, ça me permet de ne pas faire mille aller/retour.

Mis à part la technique que j'utilise, non je ne vois rien d'autre…

---

Christophe
26 ans
Paris
En IT, Développement mobile
Développeur Javascript applications React Natives
Je créer des applications mobile dans une petite équipe, souvent pour faire des POC (proof of concept) pour des clients de toutes tailles souhaitant tester la viabilité de leur produit.

Je développe des jeux vidéos en VR chez moi, pour m'amuser.
Pour mon épanouissement personnel.
Je travaille dans mon salon / chambre, je vis en collocation.
J'utilise mon PC fixe avec Unity. Un HTC Vive dont les bornes sont dans les coins de la pièces, mais je les ranges quand il y a du monde.
Je trouves des projets Unity sur le store que je télécharge et que je modifie pour une utilisation VR.

J'aime regarder comment les développeurs s'y sont pris. Ensuite et je m'approprie le projet pour le transformer comme moi j'aimerais qu'il soit. Ça me permet de zapper toute une partie de création et d'aller à l'essentiel. 
Devoir lire du code mal écrit, c'est parfois incompréhensible.
Oui, mis à part quand je doit déplacer la table basse et mon canapé lit pour avoir de la place et tester sans crainte de me cogner.
Unity est bien même si les déplacement dans la scène ce n'est pas la panacée. Il faut constamment bouger la caméra et son type (orthogonale ou naturel), pour être sûr que les objets soient à la bonne place. 
Je me retrouve souvent à ne pas avoir le rendu que je veux en réalité virtuelle. Du coups je me retrouve à vêtir et dévétir le casque et les contrôleur. Je ne m'embête plus maintenant, je le laisse sur la tête. Ça me fait transpirer et j'ai une coupe pas possible mais bon…
Je suis plus productif quand il y a personne chez moi. Personne pour me déranger, et moi je ne dérange personne quand je joue au salon en VR ou quand je développe.
Du code que je ne comprends pas. 
Avoir ma propre pièce pour jouer / développer.

### Immersion
Afin de parfaitement comprendre comment les développeur VR travaillent, leur problématique, je suis allé chez Christophe pour l'observer. Il m'a acceuilli un jour où ses colocataires étaient absents afin d'être plus tranquilles. Je m'intalle et l'observer pendant sa conception. 
Le salon mesure environ trois mètres sur quatres. Son canapé lit contre le mur et son bureau dans le coin. Les contrôleurs et le casque sont posé par terre au centre de la pièce. 
Il commence son travaille devant son ordinateur. Il utilise unity et commence par placer ses objets dans la scène et à créer les scripts associés. Il développe un petit peu puis se lève de son siège pour aller vêtir le casque et les contrôleur afin d'essayer. Il repose le tout par terre en me disant qu'il s'est trompé et que ce n'est pas au bon endroit. Plus tard, au bout de quelques essais, je remarque qu'il ne prends plus la peine de se lever de sa chaise. 
Dorénavant, il roule avec sa chaise jusqu'au casque, puis se penche pour l'attraper. 
Plus tard, encore il ne prends plus la peine de se déplacer et lorsqu'il enlève le tout, il le pose sur ses genoux. 
Enfin, au bout de 45 minutes il ne prends plus la peine d'enlever le casque de sa tête mais le déplace seulement au dessus de ses yeux, sur son front, et place les contrôleurs sur le bord de son bureau, ou sur ses genoux. Parfois il enlève son casque et le met sur ses genoux, mais le casque est la majorité du temps sur son front à présent. Je remarque qu'il passe beaucoup de temps à manipuler les objets et sa caméra dans la scène, mais aussi à développer. D'ailleurs je remarque le comportement répétitif de passer de l'éditeur de code à Unity et inversement. Le développement s'achève au bout d'une heure et trents minutes.

## Phase d'idéation
Dans cette phase, je vais rassembler et analyser les données receuillies. Je vais alors produire une grande quantité d'idée et identifier des opportunitées de design. Tout ceci deviendra de plus en plus concret grâce à l'élaboration des premiers prototypes. Ces prototypes seront soumis à un regard critique pour collecter des avis précieux et ainsi affiner les prototypes.  

### Rétrospective des entretiens et de l'immersion
Au travers des entretiens et de l'immersion, des motifs et des thèmes conducteurs émergent : (graphiques patatoïde)
  - Répétition de mouvement
  - Outils materiels et logiciels
  - Visualiser & Manipuler
  - Développer

Évidemment ces thèmes peuvent changer au cours de la phase d'idéation.

### Formulation des problématique.
Une grande quantité d'informations ont été receuilli. Il s'agit à présent de les distiller afin d'en dégager des problématiques, des révélations, qui guiderons la recherche.
Il s'agit ici de copier les thèmes définis à la phase précédente et d'écrire les problématiques qui en découle sous la forme de phrase.

__Rappel de ma problématique :__
Rendre le développement en réalité virtuelle plus intuitif, facile à utiliser, et plus productif.

*Thème :* Répétition des mouvements
*Révélations :* 
  - Les développeurs se fatiguent à aller chercher leur casques et leurs contrôleurs pour tester
  - Les développeurs ne veulent pas perdre de temps ni d'energie
  - Les développeurs trouvent des astuces pour éviter les répétitions

*Thème :* Outils materiels et logiciels
*Révélations :*
  - Le materiel VR n'est pas utilisé pour le développement
  - Le clavier et la souris sont difficilement utilisable en même temps que le casque
  - Certains logiciels manque de fonctionnalités standart pour le développement VR
  - On ne peut pas tester et développer en même temps
  - Le clavier et la souris sont fait pour une utilisation 2D.
  - Détournements d'utilisations

*Thème :* Visualiser & Manipuler
*Révélations :*
  - La manipulation d'objet en 3D pourrait-être plus aisée.
  - Visualiser la scène 3D passe par une phase de manipulation de caméra difficile.
  - La visualisation est différente entre l'écran et en situation réele (en VR).

*Thème :* Développer
*Révélations :*
  - Les fonctions sont peu parlantes et peu représentative parfois (axe x, y, z)
  - Faire des va et viens entre l'IDE (MonoDevelop, Visual Studio Code) et l'inspecteur (Unity, A-Frame Inspector)

### Atelier *Comment ferions-nous pour*
  - Le casque se trouve au dessus de leur tête et pivote
  - Abaissement du casque automatique
  - Le développement se fait directement dans la VR
  - Développer autrement qu'avec un clavier
  - Souris 3D
  - Hologramme de la scène
  - On peut regarder et manipuler la scène depuis la VR directement
  - Intégrer l'IDE à l'inspecteur.

### Reflexion sur les idées
  - Le casque se trouverais à proximité de la tête, et se placerais automatiquement devant les yeux lors du lancement du test : contrainte matériel. Cela nécéssite une insatallation supplémentaire, ainsi qu'une automatisation.
  - Le développement s'effectue à l'aide d'un clavier. Développer directement dans la VR permettrais de ne plus avoir ce passage code -> test mais de pouvoir visionner directement le rendu en temps réel. La contrainte ici est l'utilisation d'un clavier. Elle est difficile car les casques sont souvent opaque. Heuresement, certains d'entres eux sont équipé de caméra à l'avant. Un solution serait de pouvoir voir le clavier à l'aide de cette caméra en portant casque.
  - Développer avec les contrôleur par exemple, placer, assembler des blocs. Peut-être existe-t-il d'autres méthodes de programmation sans clavier.
  - Une souris adaptée, à une 3ème dimension ? Les contrôleurs sont déjà suivis dans les trois dimensions de l'espace, il suffit de les utiliser. Un solution plus ergonomique encore serait la disparition des contrôleurs et l'utilisation des mains comme contrôleurs comme le fait leapmotion. Ainsi, le mouvement d'attraper le contrôleur pour essayer sera aboli. Le développeur lèverais les mains de son clavier pour editer ou tester le jeu. puis il lui suffirait de reposer les mains sur son clavier pour continuer de développer.
  - Un hologramme de la scène engendre une technologie encore mal maitrisée. Mais on peut considérer que la visualisation au travers du casque s'en rapproche beaucoup
  - La scène pourrait être visionable et éditable directement depuis le casque VR. Le casque de réalité virtuelle se transformerais donc de simple outil de visionnage / jeu, à un outil d'édition à part entière. 
  - Intégrer l'IDE à l'inspecteur éviterais les vas et viens. Mais sur un simple écran la visibilité s'en retrouve réduite. L'espace de travail se trouvant nettement augmenté en VR (ref mike alger), il est tout à fait possible d'associer les deux.

### Regroupement d'idées, recherches.
  - Le casque avec pivotage automatique au dessus de la tête
  - Autres méthodes de programmation en VR, en n'utilisant pas de clavier.
  - Développement dans la VR, et manipulation de la scène et de son contenu grâce aux contrôleurs ou aux mains. Temps réel.

### D'autres méthodes de programmation.

Il est difficile de rédiger du texte en utilisant un casque de réalité virtuelle. En effet, le clavier, comme tout ce qui nous entoure n'est plus visible lors de l'utilisation d'un casque . 

`Alors pouvons-nous nous passer du clavier pour développer ? Est-il possible de programmer sans utiliser de texte ?`
Le développement est une construction algorithmique avant tout. En ce sens, beaucoup d'éléments sont récurrents : Les variables, les opérateurs, les conditions, les boucles et enfin les fonctions. Ses éléments étant peu nombreux, ils pourraient être représentés sous formes de blocs et agencés entre eux pour construire les argorithmes. 

Ce genre de programmation existe et se retrouve dans plusieurs domaines. 
Le premier étant l'électronique, où des portes logiques sont agencées entre elles, pour transformer le signal qui les traverse, ou pour actionner d'autres composants, et réaliser d'autres fonctions. On parle alors de programmation logique, application dérivée et élaborée de l'algèbre de Boole, de Georges Boole, fondement de l'informatique moderne(ref ou exemple)
De manière plus générale, des fonctions informatiques représentées sous forme de blocs et agenceable entre eux se nomme la programmation visuelle. Il peut même être qualifié de programmation tangible si la programmation utilise des objets physique agencés entre eux(ref donner l'exemple de blocky scratch pad, UML, et les jouets de google, et le but/contexte de chacun).

`Pourquoi ces pratiques de programmation ne sont-elles pas plus utilisées`
Ces pratiques de programmation restent marginales quand à la rédaction de code. La raison est qu'il est plus rapide d'écrire le nom du bloc plutôt que de le chercher, et l'arranger avec les autres. (ref preuve ?) Surtout quand l'écriture peut atteinds 60 mots par minutes.
Les programmation visuelle actuelle ne se détache pas assez de la programmation écrite pour s'en démarquer. L'utilisation de système plus abstrait tels que la programmation logique pourrait peut-être faire la différence. La programmation comme en electronique, en assemblant des portes logique et autre composants fonctionnels, serait une bonne candidate.

#### Modélisation

La manipulation d'objet en réalité virtuelle est aisée. L'agencement d'objet 3D pourrait-il être utile pour développer ? Pour utiliser une telle forme de programmation, il faudrait modeliser chaque éléments de synthaxe sous une forme particulière. Ci-dessous un liste des éléments de synthaxe de la programmation informatique. Celle-ci est non-exaustive, mais elle représente la majorité des éléments de syntaxe que  l'on retrouve dans les languages informatique les plus courant:

| Variables |  Opérateurs   | Conditions  | Boucles  | Fonctions |
|:---------:|:-------------:|:-----------:|:--------:|:---------:|
| booléens  | affectation   | if/else     | for      | 
| nombres   | comparaison   | switch/case | do/while |
| tableaux  | arithmétiques | try/catch   | while    |
| textes    | binaires      |             | for/in   |
| objets    | logiques      |             | for/of   |
|           | chaînes       |
|           | ternaire      |

Au vu du faible nombre de composants, leur modélisation sous formes d'objets 3D parait faisable.

#### Paradigme de programmation
La méthode de programmation est très intimement lié au language utilisé. Nous appelons ça : un paradigme de programmation.
Le paradigme de programmation détermine la vue qu'a le développeur de l'execution de son programme. Le paradigme de programmation change bien souvent d'un language de programmation à un autre. Utiliser un paradigme de programmation d'un language existant pour une nouvelle approche de développer en réalité virtuelle serait érroné. En effet rien assure que le paradigme de programmation utilisé dans le code est le bon pour une programmation visuelle. Le bon paradigme existe-t-il déjà ? Quel paradigme pourrait être inspirant pour une utilisation en VR ? Un nouveau paradigme de programmation doit-il être créer ?

Une multitude de paradigmes existent déjà. Ceux-ci sont classés en trois grande famille :
  * Types de programmation impérative (et dérivés)
  * Types de programmation orientée objet (et dérivés)
  * Types de programmation déclarative (et dérivés)
  * Inclassables tels que : évènementielle, orienté flux, par contrat …

La programmation orienté objet s'inscrit particulièrement bien pour l'utilisation de blocs. La VR permet la visualisation et la manipulation d'objets 3D. 

La programmation fonctionnelle, quand à elle, est interressante. Elle s'abstient des noms de variables, pour n'utiliser que des fonctions. 

#### Divergence de la programmation VR et de la programmation logiciel.
La programmation VR est assez particulière. En effet la plupart de fonctions permettent la manipulation d'objets : position, rotation, déplacement, échelle, instantiation, destruction… En ce sens elle est assez différente du dévellopement logiciel. Le développement logiciel est principalement utilisé pour recevoir, traiter, présenter des données. De même que le développement web est principalement utilisé pour présenter du contenu.

Pour rappel, la réalité virtuelle possède la contrainte et l'avantage suivant : difficulté pour utiliser le clavier et donc écrire et l'avantage d'avoir un espace de travail relativement infini.

Un paradigme de programmation orienté objets conviendrait à une nouvelle méthode de programmation pour la réalité virtuelle où les interactions entre objets 3D sont utilisées, au sein même de la scene 3D. Ainsi, la programmation directe des objets permet de s'abstenir de créer et nommer les variables. Les propriétés des objets seraient visibles et disponible en lecture et écriture dans l'objet pour connecter directement les blocs fonctionnels. Cette méthode de programmation se rapproche de la programmation d'automate (ref cx-programmer).

#### La programmation logique, ce qui existe.
LogiX est un système de programmation logique qui permet aux utilisateurs de la simulation de monde NEOSVR de programmer à l'interieur même de la VR. Il suffit d'arranger des blocs fonctionnels entre eux. Le système permet d'effectuer la majorité des opérations courantes. Il est aussi possible de collaborer en directe. La programmation devient vite non maintenable et illisible de part la multitude d'éléments visible et de leur interconnections. Logix s'approche-t-elle encore trop de la programmation écrite ?

#### Premier retour des tests 
Le croquis d'essais que j'ai réalisés n'ont pas convaincu. Selon les utilisateurs, ce n'est pas assez clairs. « Cela fait brouillon, on y voit pas grands chose» « À première vu on ne comprends pas ce que le "code" veut dire. » « Qu'est-ce que ça donne quand il y a un milier d'instruction ? 
Le désavantage de cette solution est d'offusquer la fonction de l'algorithme, là où un code écrit, décrit clairement son rôle. Même à la vue d'un neophite.
Développer une nouvelle méthode de programmation demande beaucoup de temps et de nouveaux champs de problématiques à découvrir. Je ne le couvrerais pas dans cet ouvrage.

#### Méthode encore immature
Cette nouvelle méthode de programmation mérite d'être recherchée et affinée. Un fois mature, les développeurs devront sortir de leur zone de confort afin de changer leur manière de programmer.

### Développement dans la VR
Lors de la phase d'inspiration, j'ai pu cerner les besoins et désirs des développeurs VR. 
Comme vu dans les entretiens il est contraignant de changer entre Réalité et VR, pour passer du développement au test en condition réelle. Enlever et mettre à le casque VR dégage l'émotion de perte de temps et d'energie. Cela amène aussi un certain inconfort physique : gènes, transpiration, irritations… 
Cette partie traitera spécialement de l'intégration du développement et de l'utilisation du clavier dans la réalité virtuelle.

#### Problématique de visibilité.
Écrire le code dans la VR, aboli la contrainte de devoir mettre et retirer son casque à répétition.
Deux problématiques apparaissent ici : 
  - Comment voir ces touches de clavier ? En effet, 70 % des développeurs codent en regardant totalement ou partiellement leur clavier.
  - Comment retrouver son clavier après le test ? 80 % des appareils de VR/AR utilisent un controleur (hors visionneuses simple). Pour les tests, les développeurs retirent leurs mains du clavier pour saisir les contrôleurs. Après le test de l'application, il doivent retrouver le clavier pour continuer le développement.

#### Voir son clavier au travers du casque.
Comment voir son clavier tout en portant le casque ? Plusieurs solutions existent déjà :
  - Utiliser un casque transparent, ce qui est le cas pour certain casque AR (Magic Leap, Project North Star,…)
  - Utiliser un casque intégrant une caméra sur sa face avant. Cette caméra retransmet l'image dans le casque (HTC Vive, Vive Pro, Lenovo Explorer, Lenovo mirage )
Dans le premier cas, le clavier est directement visible, les objets 3D se superposent à là réalité à l'aide d'une lentille.
Dans le second cas, la caméra est désactivée par défaut pour permettre une immersion complète dans l'expérience. D'où le nom de Réalité Virtuelle et non de Réalité Augmentée.
Lorsque celle-ci est activée, l'expérience virtuelle s'arrête et la réalité est complètement visible. La réalité est visionnable au travers d'une petite fenêtre, ou en supperposition à l'experience VR en pause. L'image de la réalité est retransmise avec une opacité réduite ou stylisée. Le style appliqué peut être un filtre passe-haut par exemple.

#### Place du clavier dans l'espace de travail.
Comment s'articulerait l'utilisation du clavier au sein de l'AR et de la VR d'un point de vue materiel ?
Les casques d'AR utilisent principalement des lentilles transparente. Le clavier est remarquable naturellement dans l'environnement de l'utilisateur. 
Si l'expérience AR devient intense, le clavier n'est plus visible. La localisation du clavier peut se faire d'une seule action, à l'aide d'un mise en lumière, de contour etc… Pour les casque VR qui sont opaques il faut prendre en compte plusieurs paramètres.
Je me suis donc concentré sur les casques VR qui offrent le plus de défis ergonomiques.

Les informations de l'immersion et des entretions décrivent l'espace de travail moyen d'un développeur : un bureau de 1 mètre sur 1.5 mètre à une hauteur de 80 centimètres, sur lequel repose l'ordinateur et le clavier. Ce bureau se trouve à l'avant d'un espace libre d'environ 2 mètres sur 2 mètres dans lequel le développeur peut se déplacer librement pour utiliser son materiel VR.

Le développeur veut écrire sont code et tester aisément. Pour développer il doit voir son clavier de manière clair ou à minima l'emplacement du clavier et l'emplacement des touches. Il doit être en capacité de retrouver son clavier un fois le test lancé. Il doit être aussi retrouver sa chaise si il s'est levé pour tester l'application.
Voici différents prototypes d'agencement d'espace de travail :
  - Le mode chaperon est constamment activé sur la zone définie par l'utilisateur.
  - Le clavier est détecté par les stations et modélisé dans la VR (Système identique au système des contrôleur du HTC Vive). Le problème de la visiblité des main se pose. Cette problématique est importante car on ne sait pas ou sera posé exactement nos doigts. On peut imaginer le mode chaperon activé uniquement pour les mains.
  - Le clavier est détecté par la caméra (embarquée ou déportée) et retransmet une image réduite uniquement focalisée sur le clavier avec une opacité de l'image réglable. Comme une fenêtre dans la VR donnant sur la réalité.
  - Cette même fênetre pourrait être activée et désactivée, selon si l'utilisateur pose les manettes de chaques côté du clavier ou non. Lorsque les manettes sont prises en mains la fênetre se ferme. Pour réactiver la fenêtre, les manettes doivent être replacée à l'endroit indiqué par des tâches (de chaques côté du clavier, ou défini par l'utilisateur).
  - Le mode Chaperon est activé lors de la sortie de l'espace de jeu, afin de voir les obstacles, ou pour retrouver sa chaise par exemple.

#### Intégration aux outils existants, et ce qui existe.
Plusieurs outil permettent de créer des scènes VR. Unity3D, Unreal Engine permettent de créer du contenu VR avec beaucoup d'interactions, tels que des jeux vidéos; 3DS Max et Cinema 4D permettent de créer des scènes visionable avec peu d'interaction; tandis que A-frame, ReactVR et WebVR permettent de réaliser de la VR dans le Web. 

Chaques logiciels possèdent leurs propres fonctions, méthodes de manipulations et d'édition. C'est pourquoi le développement en VR est intimement lié avec le logiciel utilisé. Aujourd'hui, différentes solutions hybrides existent selon le logiciel pour utiliser la VR comme outil de code ou d'édition de scène :
  - RiftSquetch pour WebVR
  - Primrose pour WebVR
  - VR mode d'Unreal Engine
  - Autres prototypes inconnus
  
Pour RiftSquetch et Primrose, le développeur est dans la scène. Une fênetre est devant lui dans laquelle écrire le code associé à la scène. 
Les points négatifs sont :
  - Il n'y a pas de segmentation de code selon l'objet sélectionner. Le code défini l'entièreté de la scène.
  - Les objets de la scène ne peuvent pas être placés, manipulés, modifiés manuellement. Le développeur doit placer les objets dans la scène à l'aide du code. L'intervention d'un level designer est impossible.
  - Le déplacement dans la scène est impossible.
  - La position de la fenêtre de code n'est pas intelligente, celle-ci est fixe.

Le VR mode d'Unreal Engine a créer une nouvelle approche. Elle permet de se déplacer avec aisance dans une scène, et éditer son contenu : Instancier des objets, les déplacer, incliner, agrandir/réduire, copier, détruire… Cela présente une réelle avancée et conforte une partie de mes hypothèses. Malheuresement rien ne permet de développer en VR dans Unreal Engine.

#### Design d'Interface de programmation VR
Après avoir trouvé, analysé, et écarté une poignée de thèmes, quelques idées et des révélations sont à ma disposition. Je peux en tirer un concept. Celui-ci est plus complet et affiné qu'une idée. Ce concept sera amélioré et progressera au fur et à mesure des tests auprès des utilisateurs potentiels :

Le développeur aura constemment le casque porté devant ses yeux. Il sera immergé dans la scène. Celui-ci verra les contours de son clavier et ses mains à l'aide d'une caméra sur la face avant de son casque. Cette visualisation aura une opacité réduite afin de ne pas entraver la visibilité de la scène. Dans la scène le développeur pourra :

  - Se déplacer librement dans la scène, sans même avoir à bouger. Il pourra manipuler la scène de manière macroscopique : la réduire ou l'agrandir pour avoir une vision plus globale ou détaillée, la déplacer, la faire pivoter.
  - Sélectionner un élément/objet. Lors de la sélection, un afficheur tête haute (HUD) apparaitra à proximité. Le HUD affiche les propriétés de l'objet et en permet l'édition (taille, position, rotation, texture etc…)
  - Manipuler un objet manuellement sans avoir recours au HUD.
  - Voir et manipuler l'arborescence des objets dans la scène et dans le dossier des objets du projet. La fenêtre sera visible ou fermée, fixe ou mobile.
  - Accéder au code de l'objet sélectionné. Le code est affiché dans un HUD et peut être édité.
  - Lancer, mettre en pause, ou arrêter la simulation. 
  - Visualiser les messages systèmes, tels que les erreurs de compilations ou bugs.  

## Tester son design
J'ai décidé de créer un story board pour tester le design précédement décris. 
Celui-ci me permettra d'avoir une vision plus tangible de la solution que je veux mettre en place. Je pourrais alors identifier des problèmes potentiels, et receuiller des retours utilisateurs.

### StoryBoard
Le storyboard représente un dévellopeur souhaitant recevoir des gouttes de pluie dans un bol, attaché à son contrôleur.

### Retours utilisateurs

## Conclusion
Les ateliers menés durant la phase d'inspiration m'ont permis d'adopter le point de vue des développeur VR. J'ai pu comprendre leurs problématiques, et leurs besoins. Le résultat de cette étude prouvent que les logiciels utilisés pour la réalisation d'experience VR posent des problèmes d'utilisabilité. Pour résoudre ces problèmes, j'ai recherché des idées, je les aies rassemblées, rafinées, voir pour certaines, écartées. De cet émulsion d'idée est resorti deux solutions plausibles. Soit modifier la façon de développer, soit intégrer le clavier dans une utilisation VR. La première solution est interressante mais nécessite beaucoup de recherches techniques et ergonomique. La seconde, en revanche, est accessible techniquement et modifie peu les habitudes des développeurs. J'ai donc choisi cette dernière solution pour le prototypage sous forme de storyboard afin de la tester. Les retours ont été positif, ce qui me conforte dans le choix de cette solution. La prochaine étape sera d'avoir un prototype fonctionnel, pour tester des fonctionnalitées de bases et en vérifier l'utilisabilité auprès des utilisateurs. 
