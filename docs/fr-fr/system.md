# Paramètres système

> Introduction

![System](_images/setting/setting_1.png)

Dans `System`, l'administrateur gère les informations du système IPTV : import d'autorisations, sauvegardes de base de données, sécurité des API externes.

## Setting

> Introduction

![Setting - Setting ](_images/setting/setting_2.png)

Configurer les informations de base synchronisées vers les terminaux, les arrière-plans, le format d'heure et d'autres paramètres.

<font color="red">**Monetary Unit**</font> : symbole monétaire local affiché dans Shopping.

<font color="red">**Paid Days**</font> : durée de validité lors de l'achat d'un bouquet live ou d'un film.

<font color="red">**Consumption Mode**</font> : `Prepaid` (consommation possible seulement si le compte est crédité) ou `Advance Consumption` (crédit en compte client, facturé en fin de séjour).

<font color="red">**Home Page Show**</font> : choisir Image (fond statique) ou Video (fond vidéo) pour l'accueil.

<font color="red">**Time Format**</font> : format horaire affiché côté front.

<font color="red">**Favorite Operation**</font> : décider si la liste des favoris est effacée au check-out.

<font color="red">**Request ring**</font> : sonnerie de commande (fonction obsolète).

<font color="red">**Welcome Background**</font> : image de fond pour l'écran de bienvenue.

<font color="red">**Home Background**</font> : image de fond pour la page d'accueil.

<font color="red">**Secondary Menu Background**</font> : image de fond pour les sous-menus.

<font color="red">**LOGO**</font> : logo synchronisé sur TV et mobile.

<font color="red">**Live Player Watermark**</font> : fonction obsolète.

<font color="red">**Vod Player Watermark**</font> : fonction obsolète.

<font color="red">**City**</font> : ville utilisée pour récupérer la météo et la pousser aux terminaux.

<font color="red">**Enable Remote Assistance**</font> : fonction obsolète.

<font color="red">**Protocole**</font> : dans `Protocole`, sélectionnez le protocole de diffusion en direct utilisé par les terminaux (ex. `http`, `udp`, `rtsp`).

<font color="red">**Numéro d'opérateur**</font> : dans `Numéro d'opérateur`, saisissez le numéro d'opérateur unique requis pour la maintenance du système et l'assistance technique. **Une fois saisi, il ne peut plus être modifié.**

<font color="red">**PMS**</font> : dans `PMS`, sélectionnez le mode d'intégration du PMS (système de gestion de la propriété) :
- `Aucun` : l'intégration du PMS est désactivée.
- Lorsqu'un type de PMS est sélectionné, saisissez les `Informations du serveur PMS` (l'adresse du serveur PMS). Le système IPTV s'intégrera au PMS (ex. pour l'enregistrement/départ automatique des clients et la synchronisation des factures). L'interrupteur, l'adresse et le port du PMS sont configurés par l'administrateur.

## Version

> Introduction

![APK Version Management](_images/setting/setting_3.png)

Gérer les politiques de mise à jour APK (forcée ou non) selon les terminaux. Cliquer sur `APK Upgrade`, sélectionner l'APK : le système lit la version et l'affiche dans la liste pour vérification.

## Paramètres du média de diffusion

> Introduction

![Paramètres du média de diffusion](_images/setting/streaming_1.png ':size=80%')

<!-- 📷 Capture à compléter : page des paramètres du média de diffusion -->

Dans `Paramètres du média de diffusion`, l'administrateur configure les adresses du serveur de streaming et du serveur de timeshift (TV en différé), utilisées par les terminaux pour lire les flux en direct et les programmes en différé.

<font color="red">**IP du média de diffusion**</font> : Dans `IP du média de diffusion`, saisissez l'adresse IP du serveur de streaming.

<font color="red">**Port du média de diffusion**</font> : Dans `Port du média de diffusion`, saisissez le port du serveur de streaming.

<font color="red">**IP du serveur Timeshift**</font> : Dans `IP du serveur Timeshift`, saisissez l'adresse IP du serveur de timeshift.

<font color="red">**Port du serveur Timeshift**</font> : Dans `Port du serveur Timeshift`, saisissez le port du serveur de timeshift.

<font color="red">**Heures de Timeshift**</font> : Dans `Heures de Timeshift`, définissez combien d'heures de programmes le serveur de timeshift conserve, permettant aux clients de regarder des programmes antérieurs dans cette fenêtre.

## Graphiques de données

> Introduction

![Graphiques de données](_images/setting/charts_1.png ':size=80%')

<!-- 📷 Capture à compléter : page de statistiques de données -->

Dans `Graphiques de données`, les administrateurs peuvent consulter les statistiques de fonctionnement du système IPTV, notamment :

- **Statistiques de chiffre d'affaires** : les statistiques totales des revenus d'activité.
- **Statistiques VOD** : statistiques des lectures de vidéo à la demande.
- **Type de consommation** : statistiques groupées par type de consommation.
- Graphiques à barres mensuels et graphiques circulaires, filtrables par année.
