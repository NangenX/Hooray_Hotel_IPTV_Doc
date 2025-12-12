# Gestion des clients

> Introduction

![Client Menu](_images/client/client_1.png)

Dans le `Client Menu`, l'administrateur configure les informations d'équipement via `Room Category`, `Client Information` et `Client Status`, puis gère les arrivées/départs des clients.

## Room Category

> Introduction

![Room Category](_images/client/client_2.png)

Créer des catégories logiques (par étage ou usage). Exemple : équipements du 1er étage → catégorie `L1`.

Cliquez sur `Add` pour créer une catégorie.

![Room Category - Add](_images/client/client_3.png)

1. <font color="red">**Group Name**</font> : nom de la catégorie.

## Client Information

> Introduction

![Client Information](_images/client/client_4.png)

Page listant tous les terminaux en ligne/hors ligne. On peut gérer le nom du terminal et voir sa catégorie, le numéro de chambre et autres infos.

Cliquez sur `Add` pour créer une fiche terminal.

![Client Information - Add](_images/client/client_5.png ':size=40%') ![Client Information - Edit](_images/client/client_6.png ':size=40%')

<font color="red">**MAC Address**</font> : ajouter manuellement le MAC si le terminal n'est pas découvert automatiquement. Sinon, il est en lecture seule.

<font color="red">**IP**</font> : dernière IP vue en ligne.

<font color="red">**Room Name**</font> : nom de la chambre associée.

<font color="red">**Room Category**</font> : catégorie de chambre associée.

<font color="red">**WiFi**</font> : activation du hotspot et configuration SSID/mot de passe (fonction désormais indisponible sur Android).

## Client Status

> Introduction

![Client Status](_images/client/client_7.png)

Permet d'enregistrer les arrivées/départs. Pour un appareil non check-in, on voit l'historique client/consommation. Pour un appareil check-in, on peut gérer commandes en ligne, consommations, infos invité, historiques et check-out.

![Client Status Check-In Status](_images/client/client_8.png)

<font color="red">**Request**</font> : ouvre la page de réservation en cours pour valider ou supprimer la commande (retour d'état dans l'app hôtel).

<font color="red">**Consume**</font> : affiche les consommations déjà passées depuis l'app.

<font color="red">**Edit**</font> : modifier le nom de l'invité et le message de bienvenue.

<font color="red">**Records**</font> : voir l'historique check-in/out et les consommations.

<font color="red">**Check-Out**</font> : met l'appareil en état départ (services indisponibles).

![Client Status Check-In Status](_images/client/client_9.png)

<font color="red">**Check-In**</font> : enregistrer l'invité (nom et message de bienvenue affiché sur l'écran).