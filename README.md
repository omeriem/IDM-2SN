# IDM-2SN - consignes Mini-Projet

Date limite pour remettre le mini-projet est le 8 novembre 19h. 

Le dépot se fera sur github dans le dossier depotMP. 


*) Note  : Format du dossier à déposer dans depotMP : attention le dossier compressé doit s'intituler "2SN-T-2022-G#.zip" où # sera remplacé par le numéro identifiant votre groupe (comme défini dqns le fichier drive) par exemple 2SN-T-2022-G1, etc. 


Détails : 
Rappel : Il faut déposer un seul et unique dossier compressé et intitulé "2SN-T-2022-G#.zip" (convention imposée) où # est le numéro de votre groupe dans lequel vous êtes inscrits. 


Le dossier "2SN-T-2022-G#.zip" doit contenir les fichiers suivants (tout est déjà demandé dans le pdf de votre MP précédé par la lettre D, voir votre sujet) :


1)  Partie SimplePDL :

a- l'ensemble des fichiers générés pour SimplePDL : SimplePDL.ecore, SimplePDL.ocl, SimplePDL.aird, le format png suite à l'export de votre diagramme. 

b- Exemples valides (sans erreurs) et autres non valides de modèles SimplePDL (pdl-sujet.xmi ou pdl-sujet.simplepdl correspondant au sujet est à fournir également).

c- La syntaxe textuelle de SimplePDL exprimée dans le fichier SimplePDL.xtext.


2) Partie Petri Net :

a- l'ensemble des fichiers générés pour PetriNet : PetriNet.ecore, PetriNet.ocl, PetriNet.aird, PetriNet.png. 

b- Exemples valides (sans erreurs) et autres non valides de modèles Petri Net. 


3) Partie Transformations : 

a- Transformation modèle à texte (M2T) avec Acceleo: La transformation de PetriNet dans la syntaxe concrète de Tina. Le fichier à fournir doit s'appeler PetriNet2Tina.mtl

b- Transformation modèle à modèle (M2M) avec EMF/Java: code en java à fournir dans le fichier  SimplePDL2PetriNet.java. le code permet de traduire un modèle de processus.xmi en un réseau de Petri.xmi.

c- pdl-sujet.net : le résultat de la transformation appliquée sur l’exemple du sujet du mini projet. Ce fichier devrait être une entrée valide de l'outil nd de la boit à outils Tina. 

d- SimplePDL-finish.mtl : transformation M2T qui engendre les propriétés LTL qui vérifie la terminaison d’un processus. 

e- SimplePDL-invariants.mtl (extension de l'item a- voir ci-dessus) : transformation M2T qui engendre les propriétés LTL pour valider la correction de la transformation (T10 du sujet) des modèles de processus vers les réseaux de Petri.


[Optionnel]: - rapport.pdf : c'est le compte rendu de votre mini-projet. Vous devriez expliquer la réalisation de votre travail : choix pris, difficultés, exemples d'illustration, etc. Le document doit être significatif, simple, et synthétique pour bien comprendre votre travail. 






---------------------------------------
Instructions pour la soutenance orale : 
---------------------------------------
L'oral aura lieu le 9/11/2022 à 8h en salles C203 et C206. 

Il y a 8 groupes déclarés. Chaque groupe doit faire une démo durant 10 min de son projet sur les machines de l'N7 ou machines perso respectant la même configuration des TPs. Il y aura ensuite une session de questions d'une durée de 5 min. Un tirage au sort identifiera le membre qui présente et celui qui répond. Chaque groupe doit arriver 5 à 10 min avant l'heure de la soutenance pour bien s'installer et préparer sa présentation à temps. 


Il faut bien tester vos machines avant d'arriver en oral. Tout temps perdu pour configurer sa machine et/ou eclipse sera sanctionné par des malus. 


Durant la présentation chaque groupe doit faire une demo sur Eclipse afin de montrer la réalisation de toutes les tâches démandées dans le sujet du mini-projet ainsi que tous les délivrables attendus. 


------------------
Ordre de passage : 
------------------
L'ordre de votre passage est le suivant : 

8h    : 2SN-T-2022-G1, en C203 (Besbasse H., El Marzouki O., El Mendili Y., Bougrea N.)

8h15  : 2SN-T-2022-G3, en C202

8h30  : 2SN-T-2022-G4, en C203

8h45  : 2SN-T-2022-G5, en C202

9h    : 2SN-T-2022-G6, en C203

9h15  : 2SN-T-2022-G7, en C202

9h30  : 2SN-T-2022-G8, en C203

9h45  : 2SN-T-2022-G9, en C202

Fin de soutenances prévue à 10h

