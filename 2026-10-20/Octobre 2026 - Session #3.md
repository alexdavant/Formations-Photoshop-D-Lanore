## 📑 Sommaire
- [1. Corriger l'expo sur une image](#1-corriger-l-expo-sur-une-image) 
- [2. Mode de fusion Lumière tamisée](#2-mode-de-fusion-lumière-tamisée)
- [3. Mode de fusion Eclaicir](#3-mode-de-fusion-eclaicir)
- [4. Mode de fusion Produit](#4-mode-de-fusion-produit)
- [5. Effet Orton + halo](#5-effet-orton--halo)


>[!NOTE]
>Réalisé avec Photoshop 27.11.0

## 1. Corriger l'expo sur une image

>[!IMPORTANT]
>À partir de la photo `Réchauffer HL refroidir ombre.jpg`

### 1.1 Soit rajouter un calque de Lumière
![[./assets/01.png|260]]

Puis régler les tons clairs et les tons foncés :
![[./assets/02.png|293]]


### 1.2. Ou utiliser un calque de Niveaux :
![[./assets/04.png|207]]

Puis (1) diminuer les hautes lumières et (2) éclaircir les tons moyens
![[./assets/05.png|214]]


### 1.3 Réchauffer certaines zones 

1. Ajouter un calque Filtre photo :
![[./assets/06.png|214]]

2. Choisir un filtre réchauffant 85 et pousser  la densité (80%) :
![[./assets/07.png|267]]

3. Double cliquer à droite du filtre :
![[./assets/08.png]]

4. Bouger le curseur de gauche et le dédoubler (touche <kbd>Alt</kbd> sur Windows ou <kbd>Opt</kbd> sur macOS):
![[./assets/09.png]]

### 1.4. Refroidir certaines zones

1. Même principe avec calque Filtre photo
2. Choisir un filtre bleu et bouger le curseur de droite


## 2. Mode de fusion Lumière tamisée

>[!IMPORTANT]
>Avec le fichier `sans titre-3180.dng`

### 2.1. Aplatir une image dans Camera Raw

Dans Camera Raw pour aplatir :
![[./assets/10.png|231]]



### 2.2. Remettre du contraste

Dans Photoshop

1. Créer un calque de Niveaux
2. Choisir le mode de fusion "Lumière tamisée"
3. Prendre le curseur noir et le tirer vers la droite
![[./assets/11.png|300]]


## 3. Mode de fusion Eclaicir

>[!IMPORTANT]
>Avec les fichiers `Manarolla heure bleue.dng` et `Manarolla Sunset.dng`

1. Ouvrir les 2 images dans Photoshop
2. Prendre le calque d'une image avec la souris (cliquer puis glisser)
3. Glisser vers l'autre onglet
4. Puis appuyer sur la touche <kbd>Shift</kbd> avant de relâcher sur l'image qui permettra de centrer les 2 images
5. Mettre le calque contenant les lumières dessus (en haut de la liste des calques)
6. Aligner les calques :
	- sélectionner les 2 calques dévérrouillés
	- Menu Edition > Alignement automatique des calques
7. Choisir le mode de fusion "Eclaircir" sur le calque du haut
8. Puis on veut récupérer le ciel du calque du dessous qui fera plus naturel :
	- sur n'importe quel calque : Sélection > Ciel
	- créer un masque sur le calque du dessus puis inverser le masque (<kbd>Ctrl</kbd> sur Windows ou <kbd>Cmd</kbd> + <kbd>I</kbd>)

## 4. Mode de fusion Produit

>[!IMPORTANT]
>A partir du fichier `sans titre-3180.dng`

1. Sélectionner le ciel (Sélection > Ciel) sur calque déverrouillé
2. Créer un calque Courbes
3. Le mettre en mode de fusion Produit et jouer sur l'Opacité

## 5. Effet Orton + halo

>[!IMPORTANT]
>À partir Copie de `_DL_4254.dng`

### 5.1. Effet Orton

1. Ouvrir le fichier dans Camera Raw
2. Afficher les zones bouchées (noires) en cliquant sur le curseur gauche en haut de l'histogramme :
![[./assets/12.png|314]]

3. Puis créer un masque radial sur le bas gauche de l'image :
![[./assets/14.png|36]]

4. Mettre les Noirs à +4 :
![[./assets/13.png]]

5. Puis l'ouvrir dans Photoshop
6. Dupliquer le calque :
![[./assets/15.png]]

7. Et transformer la copie du calque en objet dynamique (clic droit sur le calque puis choisir Convertir en objet dynamique) ce qui permettra d'enregistrer toutes les modifications successives :
![[./assets/16.png|285]]

8. Créer un flou gaussien :
![[./assets/17.png|388]]

9. Mettre le flou à 40% 
![[./assets/18.png|265]]

10. Modifier l'exposition de ce calque
![[./assets/19.png|428]]

11. Augmenter légèrement l'exposition :
![[./assets/20.png|383]]

12. Puis diminuer l'Opacité à 20% 

13. Double cliquer à droite du calque pour afficher le Style de calque et modifier la "**Comparaison sur : Gris**"
![[./assets/22.png]]


Voici ce qu'on observe à l'issue de toutes les manipulations sur le calque converti en objet dynamique :
![[./assets/23.png|433]]

### 5.2. Halo

1. Créer un nouveau calque de pixel et choisir le mode de fusion "Lumière tamisée"
2. Avec la pipette, choisir une couleur claire
3. Prendre le pinceau et choisir une épaisseur (<kbd>Ctrl</kbd> + <kbd>Opt</kbd> + clic gauche) et durée très faible
4. Et peindre avec parcimonie sur la zone à éclaircir
