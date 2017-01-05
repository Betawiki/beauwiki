---
layout: post
title: Utilisation de la découpeuse laser
author: Camille
categories: Découpe_laser
img: trotec.jpg
---
## Préparez votre fichier

réalisez votre dessin avec un logiciel de dessin vectoriel (nous utilisons [Inkscape](https://inkscape.org/fr/), un logiciel libre et gratuit)

* pour récupérer une image depuis Google Images (de préférence une image avec seulement des contours : Outils > Type > Dessin au trait)
    * clic droit sur l'image > Copier l'image
    * dans un nouveau document Inkscape : clic droit sur le document > Coller
    * sélectionnez l'image que vous venez d'insérer : Chemin > Vectoriser le bitmap > Valider
    * déplacez la nouvelle image que vous venez de générer et supprimez la première

**Vérifiez que votre fichier respecte les conditions suivantes :**

* les traits que vous souhaitez **découper** sont coloriés en <span style="color: red;">**rouge**</span> (*Objet > Remplissage et contour* : RGBA 255, 0, 0, 255)
* les traits que vous souhaitez **graver** sont coloriés en **noir** (*Objet > Remplissage et contour* : RGBA 0, 0, 0, 255)
	* vous pouvez aussi utiliser des niveaux de gris pour moduler la profondeur de gravure
* l'épaisseur des traits est de **0,01 mm** (*Objet > Remplissage et contour*)
* la page est redimensionnée à la **taille du dessin** (*Fichier > Propriétés du document > Redimensionner la page au contenu > Ajuster la page au dessin ou à la sélection*)
* tous vos objets ont été transformés en **chemins** (*sélectionnez vos objets > Chemin > Objets en chemins*)
* votre fichier est enregistré en **.SVG** (*Fichier > Enregistrer sous*)

## Préparer la découpeuse laser

* placer la planche
* allumer la découpeuse laser
* placer le faisceau sur la surface de découpe avec les boutons à droite
* placer le curseur en équilibre
* monter le plateau doucement jusqu'à ce que le curseur tombe

## Paramétrer le travail

* ouvrir le fichier .SVG dans Inkscape
* Fichier > Imprimer : sélectionner Trotec, puis Préférences
	* surface de découpe : 600mm x 300mm
    * matière : sélectionner le type et l'épaisseur
* lancer l'impression : le logiciel JC s'ouvre et demande un nom pour le nouveau "job"
* le fichier devrait apparaître dans le menu de droite : le placer sur la surface de découpe par cliquer-glisser
* sélectionner tous les "jobs" puis cliquer sur Mise à jour pour avoir une estimation du temps de coupe et de gravure
* connecter la découpeuse avec le bouton en bas à droite
* lancer le travail avec le bouton en bas à droite
