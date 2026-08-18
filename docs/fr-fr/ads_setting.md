# Paramétrage des publicités

> Introduction

![Advertisement](_images/ads/ads_1.png)

Dans le module Publicités, l'administrateur publie des informations et campagnes à destination des équipements en chambre.

## Sous-titres défilants

> Introduction

![Advertisement-Rolling Subtitle](_images/ads/ads_2.png)

L'administrateur peut envoyer des sous-titres défilants différents selon les groupes de terminaux, avec choix des couleurs de police et d'arrière-plan.

Cliquez sur `Add` pour créer un sous-titre défilant.

![Advertisement-Rolling Subtitle-Add](_images/ads/ads_3.png)

<font color="red">**Content**</font> : saisir le texte à diffuser.

<font color="red">**Client**</font> : sélectionner un groupe ou des terminaux cibles.

<font color="red">**Description**</font> : décrire ce sous-titre.

<font color="red">**Date**</font> : définir la date de début et de fin.

<font color="red">**Time**</font> : définir l'heure de début et de fin. L'heure prend en charge le passage de minuit (ex. `22:00` - `06:00`) et utilise le format 24 heures.

## Email

> Introduction

![Advertisement-Email-1 ](_images/ads/ads_4.png)

Le système peut pousser un message sous forme d'Email directement vers le client, qui l'ouvre sur le terminal pour en voir le détail.

Cliquez sur `Add` pour créer un message Email.

![Advertisement-Email-1 ](_images/ads/ads_5.png)

<font color="red">**Client**</font> : sélectionner un groupe ou un terminal.

<font color="red">**Title**</font> : objet affiché de l'email.

<font color="red">**Content**</font> : contenu du message.

## Arrière-plan vidéo

> Introduction

![Advertisement-Video Background-1 ](_images/ads/ads_6.png)

Dans `Video Background`, activez la fonction puis importez un fichier MP4 (vidéo H.264, audio AAC). Les terminaux téléchargent et lisent automatiquement la vidéo en fond.

Cliquez sur `Add` pour créer un nouvel arrière-plan vidéo.

![Advertisement-Video Background-1 ](_images/ads/ads_7.png)

<font color="red">**Video**</font> : choisir le fichier MP4 conforme (H.264/AAC).
<font color="red">**Clients**</font> : sélectionner le groupe ou le terminal concerné.

<font color="red">**Description**</font> : décrire l'opération ou le média.

## Matériels publicitaires

> Introduction

![Advertisement](_images/ads/ads_8.png)

`Ads Material` liste les médias importés. L'administrateur peut ajouter, éditer ou supprimer des éléments.

### Ajouter / Éditer

Cliquez sur `Add` pour téléverser un média.

![Advertisement-Ads Materia-Add ](_images/ads/ads_9.png)

<font color="red">**Upload**</font> : sélectionner l'image ou la vidéo à importer. Les fichiers volumineux sont téléchargés par fragments (téléchargement reprenable), de sorte qu'un téléchargement interrompu peut continuer au lieu de redémarrer.

<font color="red">**Material Name**</font> : nommer le média pour le retrouver ensuite.

<font color="red">**Material Type**</font> : choisir `image` ou `video`.

<font color="red">**Ads Type**</font> : associer le média au type de publicité cible (4 types disponibles).

### Supprimer

![Advertisement-Ads Materia-Del ](_images/ads/ads_10.png) Utiliser `Del` pour retirer un média. Si une campagne l'utilise encore, le terminal ne recevra plus ce média.

## Super Ads

> Introduction

![Advertisement-Super Ads ](_images/ads/ads_11.png)

Quatre types sont gérés : `boot ads`, `commercial ads`, `side ads` et `emergency ads`.

<font color="red">**Boot Ads**</font> : affichés au démarrage avant l'écran de connexion.

<font color="red">**Commercial Ads**</font> : diffusés avant la lecture live/VOD.

<font color="red">**Side Ads**</font> : images superposées sur le côté durant le live.

<font color="red">**Emergency Ads**</font> : images/vidéos poussées immédiatement à tous les terminaux ouverts.

### Créer / Modifier

![Advertisement-Super Ads ](_images/ads/ads_12.png)

Après `Add` ou `Edit`, renseignez les champs requis.

> Réglage des **Boot Ads**

<font color="red">**Ads Name**</font> : nom de la campagne.

<font color="red">**Clients**</font> : groupe d'appareils ciblé.

<font color="red">**Ads Type**</font> : choisir `Boot Ads`.

<font color="red">**Material Type**</font> : image ou vidéo jouée à l'ouverture de l'app.

<font color="red">**Material List**</font> : sélectionner les médias à diffuser.

<font color="red">**Date**</font> / <font color="red">**Time**</font> : définir la fenêtre de diffusion. L'heure prend en charge le passage de minuit (ex. `22:00` - `06:00`) et utilise le format 24 heures.

<font color="red">**Publish**</font> : activer l'envoi selon les dates/horaires définis.

> Réglage des **Commercial Ads**

<font color="red">**Ads Name**</font> : nom de la campagne.

<font color="red">**Clients**</font> : groupe d'appareils ciblé.

<font color="red">**Ads Type**</font> : choisir `Commercial Ads`.

<font color="red">**Material Type**</font> : uniquement vidéo.

<font color="red">**Program Setting**</font> : sélectionner Live ou VOD.

<font color="red">**Play Setting**</font> : `Manual broadcast` (choisir le média) ou `Random broadcast` (choix aléatoire par le terminal).

<font color="red">**Material**</font> : cocher les médias utilisés.

<font color="red">**Date**</font> / <font color="red">**Time**</font> : fenêtre de diffusion. L'heure prend en charge le passage de minuit (ex. `22:00` - `06:00`) et utilise le format 24 heures.

<font color="red">**Publish**</font> : activer l'envoi avec la fenêtre définie.

<font color="red">**Turn on channel switching**</font> : si activé, la pub se joue au zapping live/VOD.

> Réglage des **Side Ads**

<font color="red">**Ads Name**</font> : nom de la campagne.

<font color="red">**Clients**</font> : groupe d'appareils ciblé.

<font color="red">**Ads Type**</font> : choisir `Side Ads`.

<font color="red">**Material Type**</font> : uniquement image.

<font color="red">**Program Setting**</font> : utiliser sur Live ou VOD.

<font color="red">**Show Position**</font> : position d'incrustation (gauche, droite, haut, bas).

![Advertisement-Super Ads-Side Ads-Left ](_images/ads/ads_14.png ':size=40%') ![Advertisement-Super Ads-Side Ads-Right ](_images/ads/ads_13.png ':size=40%')

![Advertisement-Super Ads-Side Ads-Top ](_images/ads/ads_15.png ':size=40%') ![Advertisement-Super Ads-Side Ads-Bottom ](_images/ads/ads_16.png ':size=40%')

<font color="red">**Interval**</font> : temps d'intervalle entre deux affichages.

<font color="red">**Material**</font> : médias à afficher.

<font color="red">**Images show time**</font> : durée d'affichage de chaque image (en secondes).

<font color="red">**Date**</font> / <font color="red">**Time**</font> : fenêtre de diffusion. L'heure prend en charge le passage de minuit (ex. `22:00` - `06:00`) et utilise le format 24 heures.

<font color="red">**Publish**</font> : activer l'envoi avec la fenêtre définie.

> Réglage des **Emergency Ads**

<font color="red">**Ads Name**</font> : nom de la campagne.

<font color="red">**Clients**</font> : groupe d'appareils ciblé.

<font color="red">**Ads Type**</font> : choisir `Emergency Ads`.

<font color="red">**Material Type**</font> : image ou vidéo.

<font color="red">**Program Setting**</font> : dans `Program Setting`, l'administrateur doit choisir si la publicité est destinée à la TV en direct ou à la VOD.

<font color="red">**Interval**</font> : dans `Play Setting`, l'administrateur peut choisir `Manual boardcast` ou `Random boardcast` ; en mode manuel, sélectionnez le matériel à diffuser dans la zone Matériel ; en mode aléatoire, le terminal sélectionne automatiquement le matériel à diffuser.

<font color="red">**Matériel**</font> : dans `Matériel`, cochez le matériel publicitaire correspondant.

<font color="red">**Images show time**</font> : dans `Image Show Time`, l'administrateur définit la durée d'affichage d'une image en secondes ; si plusieurs images sont sélectionnées, chacune est affichée pendant la même durée.

<font color="red">**Date**</font> : dans `Date`, l'administrateur peut préciser la date de début et de fin de la publicité.

<font color="red">**Time**</font> : dans `Time`, l'administrateur peut préciser l'heure de début et de fin de la publicité. L'heure prend en charge le passage de minuit (ex. `22:00` - `06:00`) et utilise le format 24 heures.
<font color="red">**Publish**</font> : après avoir coché `Publish`, la publicité commencera à être envoyée ; si `Date` et `Time` ont été définies, la publicité sera traitée selon celles-ci.
