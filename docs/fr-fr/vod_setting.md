# Paramétrage VOD

> Introduction

![Video On Demand Menu](_images/program/program_6.png)

Le module `Video On Demand` permet de gérer les `VOD Category`, `VOD Program` et `VOD Upload`.

## VOD Category

> Introduction

![Video On Demand Menu](_images/program/program_7.png)

Créer/éditer/supprimer des catégories de films pour organiser la bibliothèque et faciliter la recherche côté abonné.

![VOD Category Detail](_images/program/program_8.png)

1. <font color="red">**ID**</font> : généré automatiquement, modifiable (unique). Ordre d'affichage des catégories (plus petit = plus haut).

2. <font color="red">**Name**</font> : nom de la catégorie affiché sur le set-top box.

## VOD Program

> Introduction

![VOD Program](_images/program/program_9.png)

Ajouter/éditer/supprimer les films et lier les fichiers vidéo. Visualiser le poster, les infos et le nombre de vues.

![VOD Program-add](_images/program/program_10.png)

1. <font color="red">**Poster**</font> : image d'affiche du film, affichée sur le terminal.

2. <font color="red">**Name**</font> : titre du film.

3. <font color="red">**Price**</font> : prix (0 = gratuit, >0 = paiement demandé).

4. <font color="red">**Director**</font> : affiché dans les détails du film.

5. <font color="red">**Actors**</font> : affiché dans les détails du film.

6. <font color="red">**Area**</font> : zone/région de sortie.

7. <font color="red">**Language**</font> : langue audio par défaut.

8. <font color="red">**Screen Time**</font> : durée du film.

9. <font color="red">**VOD Type**</font> : catégorie du film (pour le classement côté abonné).

10. <font color="red">**Tag**</font> : marquer comme Hot Movie pour l'afficher en tête de page VOD.

12. <font color="red">**Off Sale**</font> : retirer le film de la vente dans l'app.

12. <font color="red">**Introduction**</font> : résumé/détails du film.

## VOD Upload

> Introduction

![Vod Upload](_images/program/program_11.png)

Téléverser ou supprimer les fichiers vidéo. Le fichier doit respecter le standard Hooray : vidéo `HEVC/H.254/AV1`, audio `AAC/MP3/AC-3/E-AC-3/FLAC/DTS`, format <font color="red">OBLIGATOIREMENT</font> `.MP4`.

!> :warning: **Le nom du fichier téléversé doit être sans symboles spéciaux ni espaces.**

Cliquer sur `Choose File`, sélectionner la vidéo ; la page se rafraîchit et liste le fichier.

!> Après l'upload, aller dans `VOD Program`, choisir le film puis cliquer sur l'icône de liaison pour associer le fichier.

![Vod Upload](_images/program/program_12.png)

Cliquer sur `Add` pour ajouter une entrée.

![Vod Upload](_images/program/program_13.png)

1. <font color="red">**ID**</font> : généré automatiquement, sert à l'ordre d'affichage (plus petit = plus haut dans l'app).

2. <font color="red">**Source**</font> : choisir `URL` ou `Local File` (fichier téléversé via le système IPTV).

3. <font color="red">**URL**</font> : si `URL` est choisi, renseigner l'adresse du fichier distant.

