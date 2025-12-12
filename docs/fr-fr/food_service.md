# Service de restauration

> Introduction

![Food](_images/food/food_1.png)

Dans `Hotel Service`, l'administrateur configure les types de plats et le menu pour la commande IPTV en chambre, et suit les commandes en temps réel (acceptation, finalisation, annulation). Les invités commandent depuis la TV, l'administrateur gère le flux complet.

## Food Type

> Introduction

![Food Type](_images/food/food_2.png)

Créer, modifier, supprimer les catégories de plats.

![Food Type](_images/food/food_3.png)

<font color="red">**ID**</font> : généré automatiquement (plus petit = affiché plus haut).

<font color="red">**Name**</font> : nom de la catégorie.

## Food List

> Introduction

![Food List](_images/food/food_4.png)

Gérer les plats commandables (créer, éditer, supprimer).

![Food List](_images/food/food_5.png)

<font color="red">**Image**</font> : image du produit (1 image, PNG/JPG) affichée côté terminal.

<font color="red">**Backgroud picture**</font> : image d'arrière-plan lors de la sélection du plat sur le terminal.

<font color="red">**Name**</font> : nom affiché.

<font color="red">**Price**</font> : prix unitaire.

<font color="red">**Food Type**</font> : catégorie du plat (affichage dans la liste correspondante).

<font color="red">**Description**</font> : description détaillée.

## Order Status

> Introduction

![Order Status](_images/food/food_6.png ':size=40%')

Vue des commandes envoyées depuis les terminaux. Actions possibles : `receive` pour accepter, `delete` pour annuler, puis `finish` pour clôturer une fois préparé/livré.