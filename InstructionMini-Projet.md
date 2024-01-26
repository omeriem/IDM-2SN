# IDM-2SN - consignes et échéances Mini-Projet : 

--------------------------------------------------------------Format de livrables----------------------------------------------------------

Il faut déposer sur moodle un SEUL et UNIQUE dossier compressé par groupe et intitulé "2SN-R-2024-#.zip" (convention imposée) où # est le numéro de votre groupe dans lequel vous êtes inscrits.
N'attendez jamais le dernier moment pour déposer votre travail. Vous avez avez la possibilité de mettre à jours votre dépot sur moodle.
--------------------------------------------------------------Dates Limites----------------------------------------------------------------

Date limite pour s'inscrire dans un groupe mini-projet est 28/janvier/2024 mi-nuit. Un retard d'inscription impliquera un malus dans la notation finale!
Date limite pour remettre les méta-modèles : simplePDL.ecore PetriNet.ecore et les fichiers SimplePDL.ocl et PetriNet.ocl est 09/février/2023 minuit.
Date limite pour remettre la version finale du mini-projet est 26/févier/2024 mi-nuit.
-------------------------------------------------------------Détails Version Finale--------------------------------------------------------

La version finale à déposer le 26/février/2023 doit contenir un UNIQUE dossier appelé "2SN-T-2024-#.zip" doit contenir les fichiers suivants (tout est déjà demandé dans le pdf de votre MP précédé par la lettre D, voir votre sujet) :

Partie SimplePDL :
a- l'ensemble des fichiers générés pour SimplePDL : SimplePDL.ecore, SimplePDL.ocl, SimplePDL.aird, le format png suite à l'export de votre diagramme.

b- Exemples valides (sans erreurs) et autres non valides de modèles SimplePDL (pdl-sujet.xmi ou pdl-sujet.simplepdl correspondant au sujet est à fournir également).

c- La syntaxe textuelle de SimplePDL exprimée dans le fichier SimplePDL.xtext.

Partie Petri Net :
a- l'ensemble des fichiers générés pour PetriNet : PetriNet.ecore, PetriNet.ocl, PetriNet.aird, PetriNet.png.

b- Exemples valides (sans erreurs) et autres non valides de modèles Petri Net.

Partie Transformations :
a- Transformation modèle à texte (M2T) avec Acceleo: La transformation de PetriNet dans la syntaxe concrète de Tina. Le fichier à fournir doit s'appeler PetriNet2Tina.mtl

b- Transformation modèle à modèle (M2M) avec EMF/Java: code en java à fournir dans le fichier SimplePDL2PetriNet.java. le code permet de traduire un modèle de processus.xmi en un réseau de Petri.xmi.

c- pdl-sujet.net : le résultat de la transformation appliquée sur l’exemple du sujet du mini projet. Ce fichier devrait être une entrée valide de l'outil nd de la boit à outils Tina.

d- SimplePDL-finish.mtl : transformation M2T qui engendre les propriétés LTL qui vérifie la terminaison d’un processus.

e- SimplePDL-invariants.mtl (extension de l'item a- voir ci-dessus) : transformation M2T qui engendre les propriétés LTL pour valider la correction de la transformation (T10 du sujet) des modèles de processus vers les réseaux de Petri.

[Optionnel]: - rapport.pdf : c'est le compte rendu de votre mini-projet. Vous devriez expliquer la réalisation de votre travail : choix pris, difficultés, exemples d'illustration, etc. Le document doit être significatif, simple, et synthétique pour bien comprendre votre travail.

-------------------------------------------------------------Instructions pour la soutenance orale-----------------------------------------

L'oral aura lieu le 27/03/2024 à 14h en salles XXX et YYY.

Détails à venir plus tard ...

