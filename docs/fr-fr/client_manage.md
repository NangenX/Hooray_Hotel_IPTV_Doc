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

## Gestion des appareils

> Introduction

![Gestion des appareils](_images/client/client_10.png ':size=80%')

<!-- 📷 Capture à compléter : vue de gestion des appareils dans Informations client -->

Dans `Informations client`, la liste des appareils est enrichie de capacités de gestion à distance. Lorsqu'un décodeur signale son état, l'administrateur peut opérer l'appareil à distance sans entrer dans la chambre, ce qui réduit considérablement le coût de maintenance informatique.

### Télémétrie de l'appareil

La liste des appareils affiche la télémétrie en temps réel signalée par chaque décodeur, notamment l'**utilisation du CPU** et l'**utilisation de la mémoire**, ce qui permet à l'administrateur de repérer rapidement les appareils présentant des problèmes de performance (ex. blocages ou forte utilisation de la mémoire).

### Détail de l'appareil

![Détail de l'appareil](_images/client/client_11.png ':size=80%')

<!-- 📷 Capture à compléter : fenêtre de détail de l'appareil -->

Cliquez sur le bouton `Détail` de l'appareil pour ouvrir le dialogue de détail, où les informations sont regroupées pour une consultation facile :

- **Informations sur l'appareil** : adresse MAC, IP, nom de la chambre, catégorie de la chambre, modèle de l'appareil, etc.
- **Capacités** : les capacités de commande déclarées par l'appareil (ex. s'il prend en charge `clear_guest_data`, `get_logs`, `get_telemetry`).
- **Historique des commandes** : les dernières instructions de l'appareil (jusqu'à 10 enregistrements), avec leur état et leur résultat.
- **Voir le journal** : ouvrir le journal de l'appareil dans un dialogue indépendant.

### Commandes de l'appareil

L'administrateur peut envoyer à distance les commandes suivantes à un appareil :

| Commande | Description |
|---|---|
| **reboot** | Redémarrer le décodeur à distance. |
| **clear_guest_data** | Effacer les données client des applications tierces sur l'appareil (ex. état de connexion et cache de Netflix/YouTube). Les paquets à nettoyer sont contrôlés par la liste blanche de nettoyage au départ configurée dans la page `Informations client` (voir `Liste blanche de nettoyage au départ`). |
| **get_telemetry** | Demander à l'appareil de signaler immédiatement un cycle complet de télémétrie (CPU/mémoire), au lieu d'attendre le prochain rapport périodique. |
| **get_logs** | Demander à l'appareil de renvoyer son texte de journal (jusqu'à 100 Ko). Le contenu renvoyé peut être consulté dans l'historique des commandes. |

> **Remarque** : les commandes ne sont délivrées qu'aux appareils qui déclarent la capacité correspondante. Les appareils qui n'ont pas signalé de capacités ne recevront pas les commandes de nouvelle génération.

### Nettoyage manuel groupé

![Nettoyage manuel groupé](_images/client/client_12.png ':size=80%')

<!-- 📷 Capture à compléter : entrée de nettoyage manuel groupé -->

Sur la liste des appareils, l'administrateur peut sélectionner plusieurs appareils et effectuer un **nettoyage manuel groupé** (`clear_guest_data`), généralement utilisé avant l'arrivée d'un nouveau client pour protéger la confidentialité du client précédent.

### Liste blanche de nettoyage au départ

![Liste blanche de nettoyage au départ](_images/client/client_13.png ':size=80%')

<!-- 📷 Capture à compléter : fenêtre de liste blanche de nettoyage au départ -->

La liste blanche de nettoyage au départ est configurée dans la page `Informations client` : appuyez sur le bouton `Liste blanche` pour ouvrir le dialogue et saisissez les noms de paquets des applications tierces à nettoyer (séparés par des virgules, ex. `com.netflix.ninja,com.google.android.youtube`). Lorsqu'un client part (ou qu'une commande de nettoyage est déclenchée), le terminal efface localement les données de ces paquets. Laissez vide pour désactiver le nettoyage automatique au départ.
