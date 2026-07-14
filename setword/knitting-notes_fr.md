---
title: Aide des notes de tricot
---

Les notes de tricot permettent d’importer et de lire des modèles PDF, puis d’ajouter des règles, du texte, des images, des repères d’information, des tracés et des compteurs. L’ajout d’éléments ou de dessins ne modifie pas directement le PDF d’origine.

## Navigation rapide

- [Créer et ouvrir un projet](#créer-et-ouvrir-un-projet)
- [Interface de l’éditeur](#interface-de-léditeur)
- [Barre d’outils inférieure](#barre-doutils-inférieure)
- [Pages et étiquettes](#pages-et-étiquettes)
- [Ajouter des composants](#ajouter-des-composants)
- [Calibrage de la grille](#chart-grid-segmentation)
- [Modifier et verrouiller les composants](#modifier-les-composants)
- [Pinceaux et gomme](#pinceaux-et-gomme)
- [Compteurs](#compteurs)
- [Gestion des éléments](#gestion-des-éléments)
- [Enregistrement et appareils multiples](#enregistrement-annulation-et-restauration)
- [Questions fréquentes](#questions-fréquentes)

## Créer et ouvrir un projet

1. Ouvrez la page Outils et choisissez **Notes de tricot**.
2. Sélectionnez le fichier PDF à importer.
3. Une fois importé, le fichier apparaît dans la liste des projets.
4. Touchez le projet pour reprendre à la dernière page et retrouver l’état d’édition précédent.

Les utilisateurs gratuits peuvent créer un seul projet de notes de tricot. La suppression d’un projet est irréversible ; vérifiez qu’il n’est plus nécessaire avant de le supprimer.

## Interface de l’éditeur

### Barre d’outils supérieure

- **Fermer** : revient à la liste des projets et enregistre l’état de lecture.
- **Annuler** : annule la dernière opération compatible sur un tracé ou un composant.
- **Rétablir** : restaure l’opération qui vient d’être annulée.
- **Guide d’utilisation** : touchez `?` pour ouvrir cette aide à tout moment.
- **Plus** : permet de renommer, enregistrer ou supprimer le projet.

### Afficher ou masquer les barres d’outils

Touchez une zone vide du PDF pour masquer les barres supérieure et inférieure et agrandir la zone de lecture. Utilisez les petits boutons au bord de l’écran pour les afficher de nouveau.

### Gestes de lecture

- Glissement à un doigt : parcourt le PDF.
- Pincement à deux doigts : zoome sur la page.
- Toucher un composant : le sélectionne et affiche sa barre flottante.
- Faire défiler ou zoomer le PDF : retire le focus du composant sélectionné.

## Barre d’outils inférieure

| Outil | Fonction |
|---|---|
| Pages | Affiche les miniatures et les étiquettes pour naviguer rapidement |
| Composants | Ajoute des images, repères, liens de diagramme, textes, grilles ou règles |
| Déplacement | Revient au mode de lecture, de défilement et de zoom |
| Pinceau | Choisit un pinceau et dessine sur la page actuelle |
| Gomme | Efface les tracés du pinceau |
| Compteurs | Affiche ou masque les compteurs du projet |
| Plus | Ouvre les éléments, la couleur par défaut et la gestion des pinceaux ou des règles |

## Pages et étiquettes

Touchez **Pages** dans la barre inférieure pour afficher les miniatures :

- Touchez une miniature pour ouvrir la page correspondante.
- La liste des étiquettes permet d’accéder directement aux pages marquées.
- L’étiquette d’une page apparaît sous sa miniature.
- Touchez `...` sur la miniature sélectionnée pour ajouter, modifier ou supprimer son étiquette.
- Chaque page ne peut avoir qu’une seule étiquette.

Les utilisateurs gratuits peuvent créer jusqu’à deux étiquettes. Les étiquettes existantes restent modifiables et supprimables.

## Ajouter des composants

1. Touchez **Composants** dans la barre inférieure.
2. Choisissez le composant souhaité.
3. Son bouton apparaît sélectionné.
4. Touchez l’emplacement cible dans le PDF pour y placer le composant.
5. Après l’ajout, l’éditeur revient automatiquement au mode Déplacement.

L’ajout de nouveaux composants est réservé aux membres. Les composants existants restent consultables et modifiables.

### Composants disponibles

#### Règles

Les règles servent à suivre la ligne ou la colonne en cours de lecture. Des règles horizontales, verticales et à 45° sont fournies par défaut. Leurs préréglages se gèrent dans la bibliothèque des règles.

#### Texte

Le composant texte accepte plusieurs lignes. Agrandissez son cadre pour afficher davantage de contenu. Les réglages permettent de modifier la couleur, la taille, l’alignement, ainsi que de copier ou coller le texte.

#### Images

Une image peut provenir de l’appareil photo, d’un fichier ou de la photothèque. Elle conserve ses proportions et peut être redimensionnée uniformément ou tournée, mais ses côtés ne peuvent pas être étirés séparément.

#### Repère d’information

Le repère apparaît sous la forme d’une icône `i` de taille fixe. Touchez-le pour lire son contenu. Touchez deux fois la zone de texte de la fenêtre pour le modifier.

#### Lien de diagramme

Un lien associe le PDF à un diagramme de tricot existant dans l’App. Il peut afficher une miniature et ouvrir directement le diagramme associé.

<a id="chart-grid-segmentation"></a>
#### Calibrage de la grille

Le calibrage transforme un diagramme pixelisé ou un diagramme de tricot déjà présent dans le PDF en une source réutilisable contenant les informations de lignes et de colonnes.

1. Choisissez **Grille de diagramme** dans Composants, puis touchez la zone du diagramme pour placer le cadre.
2. Faites glisser une zone vide à l’intérieur du cadre pour le positionner. Utilisez les poignées extérieures pour le redimensionner ou le faire pivoter.
3. Le guide horizontal commence en haut et le guide vertical à gauche. Déplacez chaque guide et ajustez son épaisseur jusqu’à ce que ses deux bords coïncident avec deux lignes voisines de la grille.
4. Touchez **Aligner** pour ajuster les deux axes sur la période complète la plus proche. À proximité d’une position exacte, l’aimantation se déclenche automatiquement avec un retour haptique.
5. Le rouge indique qu’un réglage reste nécessaire. Une fois le cadre et la grille confirmés, l’état devient vert et affiche **Aligné**. Tout déplacement, redimensionnement ou rotation du cadre nécessite un nouvel alignement.
6. **Verrouiller le cadre** protège seulement le cadre extérieur et laisse les deux guides réglables. L’action **Verrouiller** située plus loin bloque tout le composant.
7. **Aperçu de la grille** vérifie le résultat extrait sans créer de projet de tricot.
8. **Créer un diagramme compteur** crée et associe un seul diagramme de tricot. Par la suite, la même entrée ouvre ou synchronise ce diagramme au lieu de créer une nouvelle copie.
9. **Plus** permet d’afficher les bandes de calibrage ou toute la grille et de régler le sens de lecture des lignes et colonnes. Un petit repère reste visible lorsque le composant n’est pas sélectionné ; touchez deux fois un composant associé pour ouvrir son diagramme.

La version actuelle génère les cellules et une image de référence à partir de la grille calibrée. Elle ne reconnaît pas encore automatiquement les symboles de points. Vérifiez dans l’aperçu les quatre bords, le nombre de lignes et de colonnes et les sens de lecture avant utilisation.

## Modifier les composants

Touchez un composant pour afficher son cadre de sélection, ses poignées et sa barre flottante. Les opérations disponibles dépendent du type :

- Faire glisser l’intérieur : déplace le composant.
- Faire glisser une poignée latérale : modifie la largeur ou la hauteur.
- Faire glisser la poignée en haut à droite : redimensionne en conservant les proportions.
- Faire glisser la poignée supérieure : fait pivoter le composant.
- Couleur : change sa couleur.
- Opacité : ajuste la transparence du fond.
- Transformation : règle rapidement l’angle ou l’échelle.
- Supprimer : supprime le composant.

Tous les composants ne prennent pas en charge toutes les opérations. Une image ne peut pas étirer ses côtés séparément ; les repères d’information et liens de diagramme ne peuvent pas être tournés ou redimensionnés.

### Verrouiller et déverrouiller

- Après un verrouillage complet, la barre flottante n’affiche plus que **Déverrouiller**.
- Une règle verrouillée peut encore être déplacée, mais pas redimensionnée, tournée ou restylée.
- **Verrouiller le cadre** sur une grille empêche seulement les modifications accidentelles du cadre extérieur ; les guides internes restent réglables. Utilisez **Verrouiller** pour figer tout le composant.
- Les textes, images, repères, liens et autres composants verrouillés ne peuvent plus être déplacés ni modifiés.
- Touchez **Déverrouiller** pour restaurer les commandes et poignées.

## Pinceaux et gomme

Choisissez un préréglage dans **Pinceau**, puis dessinez sur la page actuelle.

- Un préréglage contient la forme, l’épaisseur, la couleur et l’opacité.
- La bibliothèque permet d’ajouter, modifier, supprimer et trier les pinceaux.
- Les pinceaux placés en tête de liste sont affichés en priorité.
- La gomme efface uniquement les tracés, pas les composants.
- Supprimez un composant avec son bouton Supprimer ou dans la gestion des éléments.

La création de nouveaux pinceaux est réservée aux membres. Les pinceaux par défaut et existants restent utilisables.

## Compteurs

Chaque projet contient au moins un compteur.

- Touchez le nombre pour ajouter 1.
- Touchez `-` pour retirer 1.
- Utilisez Réinitialiser pour revenir à 0.
- Touchez `...` ou maintenez le compteur pour ouvrir son menu.
- Le menu permet de modifier, saisir rapidement une valeur, changer la couleur, renommer ou supprimer.
- Le nombre de lignes est la valeur maximale ; après cette valeur, le compteur revient à 0.
- Le premier compteur du projet ne peut pas être supprimé.

Une page horizontale affiche jusqu’à trois compteurs. Balayez horizontalement pour voir les suivants ; l’indicateur supérieur montre la page actuelle. Le bouton en haut à droite alterne entre hauteur complète et compacte.

Les utilisateurs gratuits peuvent utiliser jusqu’à trois compteurs.

## Gestion des éléments

Ouvrez **Plus > Éléments** pour gérer les composants et les notes dessinées :

- L’aperçu aide à reconnaître le contenu et sa forme.
- Touchez un élément pour atteindre sa page et sa position.
- Verrouillez ou déverrouillez les composants.
- Supprimez les éléments inutiles.
- Les tracés proches sont regroupés en un aperçu plus facile à reconnaître.

## Couleur, pinceaux et règles par défaut

Le menu inférieur **Plus** contient :

- **Couleur par défaut** : utilisée par les nouveaux composants.
- **Gestion des pinceaux** : préréglages communs à tous les projets.
- **Gestion des règles** : préréglages communs à tous les projets.

La modification d’un préréglage global ne change pas automatiquement les éléments déjà présents.

## Enregistrement, annulation et restauration

- La page de lecture, les étiquettes, les compteurs et la plupart des modifications sont enregistrés avec le projet.
- Pour forcer l’enregistrement, utilisez **Plus > Enregistrer** dans la barre supérieure.
- Annuler et Rétablir s’appliquent aux opérations compatibles de la session actuelle.
- Après avoir quitté puis rouvert le projet, l’historique d’annulation peut être perdu, mais le contenu enregistré est restauré.

## iCloud et appareils multiples

La sauvegarde comprend la base du projet, le PDF et les images associées. Terminez la synchronisation ou la restauration iCloud de l’App avant d’utiliser le projet sur un autre appareil.

À retenir :

- iCloud n’est pas un système de collaboration en temps réel.
- Les PDF volumineux peuvent demander davantage de temps.
- Ne supprimez pas le projet ou le PDF de l’ancien appareil avant la fin de la restauration.
- Certaines anciennes sauvegardes contenant seulement la base de données peuvent ne pas restaurer le PDF lui-même.

## Questions fréquentes

### Pourquoi le PDF ne défile-t-il plus après avoir sélectionné un composant ?

Les gestes du composant ont priorité dans sa zone. Touchez une zone vide, passez en mode Déplacement ou commencez à zoomer pour quitter le focus du composant.

### Pourquoi la gomme ne supprime-t-elle pas une règle ou un texte ?

La gomme traite uniquement les tracés. Utilisez le bouton Supprimer du composant ou la gestion des éléments pour les autres objets.

### Pourquoi une règle verrouillée peut-elle encore être déplacée ?

Une règle doit suivre la progression dans le diagramme. Le verrouillage fixe donc sa taille, son angle et son style, tout en laissant son déplacement possible. Les autres composants verrouillés restent entièrement fixes.

### Pourquoi faut-il toucher la page après avoir choisi un composant ?

Le fonctionnement « choisir puis placer » ajoute directement le composant à l’endroit voulu et évite de devoir le déplacer depuis le centre de la page.

### Pourquoi certaines fonctions affichent-elles une invitation à devenir membre ?

La version gratuite conserve l’importation, la lecture et des quotas limités. L’ajout de composants, de pinceaux et d’autres fonctions avancées nécessite un abonnement.
