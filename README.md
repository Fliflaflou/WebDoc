# WebDoc

Webdocumentaire coopération décentralisée France Sénégal

					 ********************* A FAIRE ******************** 
		Etape 1 : création des pages html avec Bootstrap (skel) (Conf : NAVIGATION) (Git : Main)
		Etape 2 : création fichier css (style/main.css)	(Git : css)
		Etape 3 : //Vérification// 
				 bouton vol (leccture vidéo) & qualité vidéo (voir compatibilité), && fullscreen (F11)
		
		Etape 4 : ****plugins****, (piwic) (Git : extension)
		Etape 5 : intégration des contenus (Youhou, c'est trop beau, truc de ouf)


			******************************* SOLUTIONS TECHNIQUES ***************************************

2 choix possibles : 
site sous WP
avantage : interface backoffice facile pour ajouter de nouveaux portraits
inconvénient : plus lourd à personnaliser au niveau design?

site "sur mesure" (pas de CMS), avec 
BDD des portraits pour faire apparaitre les portraits en fonction de leur catégorie
possibilité de paramétrage d'une page PHP pour intégrer de nouveaux portraits
avantage : souplesse pour développer un design sur mesure
inconvenient: création de la BDD et des pages PHP pour appeler les données et insérer les nouveaux portraits (ne pas recréer un CMS !)


contour de formes cf https://www.w3schools.com/tags/tag_area.asp
<map...
<area ...

+ générateur de coordonnées, par ex http://imagemap-generator.dariodomi.de/



			**************************************NAVIGATION*********************************************

		///////////	1 page d'accueil avec ///////////////
    info sur la coopération décentralisée
    mode d'emploi (possible de garder accessible sur toutes les pages)
    bouton "démarrer"
lien vers tous les portraits ? ou passage obligé par la page des notions clés pour le parcours ?
    
(pas de vidéo d'intro ?)

		////////////	1 page avec toutes notions clés avec ////////////////

dessin de fond
nuages avec les différentes notions clés en pictogramme/dessin, cliquables
plusieurs "boutons" :
tous les portraits --> page "Portraits"
retour intro
crédits (modal)
partage vers les réseaux sociaux
pour les vidéos
réglage du volume (que pour les vidéos ou son ambiance sur la page ? )
choix de la qualité de l'image (normalement compris dans l'appel html) 

Son d'ambiance sur les pages ? Besoin d'une continuité pour le son quand on passe d'une page à l'autre ?

	////////////////////	Les pages Notions-Clefs (1par notion) 	//////////////////////

- affichage des portraits avec lecteur
- dessin de fond 
- liens vers les vidéos (chaque portrait) 


	///////////////////////	1 pages avec tous les portraits	/////////////////////////////
Quelle organisation ?
Ex. visuel des notions clés, avec les portraits de chaque notion organisés autour du dessin correspondant
- pictogramme de la notion clé ajouté sur chaque portrait

5 pages notion clé : 1 page par notion clé --> portraits associés 


Organisation des portraits
catégorie "portrait"
catégorie "notion clé" associée (plusieurs possibles)


    

