# Paramétrage Live

> Introduction

![Program Menu](_images/program/program_1.png)

Le menu Program permet de créer, modifier et supprimer les réglages `Live` et `VOD`.

## Live Packages

> Introduction

![Live Package](_images/program/program_2.png)

Créer/éditer/supprimer les catégories de chaînes live pour organiser les sources par groupe. Chaque catégorie associe des chaînes live et peut avoir son poster.

![Live Package-Add](_images/program/program_3.png)

1. <font color="red">**ID**</font> : généré automatiquement (plus petit = affichage plus haut). Modifiable pour réordonner.

2. <font color="red">**Name**</font> : nom de la catégorie.

3. <font color="red">**Price**</font> : prix du bouquet (0 = gratuit, >0 = accès payant côté invité).

4. <font color="red">**Image**</font> : poster affiché dans le menu des catégories live.

!>  **Taille conseillée du poster : 300x210**

5. <font color="red">**Live Program Select**</font> : sélectionner les chaînes live rattachées à cette catégorie (affichage côté terminal).

6. <font color="red">**STB Select**</font> : choisir les terminaux qui verront cette catégorie.

## Live Program

> Introduction

![Live Program](_images/program/program_4.png)

Ajouter en manuel ou en lot des chaînes live, puis éditer/supprimer. Protocoles supportés : UDP/RTP unicast, HTTP-TS/FLV, RTMP/RTMPS, HLS, DASH, etc.

![Live Channel Add Detail](_images/program/program_5.png)

1. <font color="red"> **ID** </font> : généré automatiquement, modifiable sans dupliquer un autre ID (ordre d'affichage des chaînes).

2. <font color="red"> **Name** </font> : nom de la chaîne affiché côté set-top box.

4. <font color="red"> **URL** </font> : adresse du flux à lire.

5. <font color="red"> **Image** </font> : logo de la chaîne affiché dans la liste et les détails.

## Canal radio

> Introduction

![Canal radio](_images/program/radio_1.png ':size=80%')

<!-- 📷 Capture à compléter : page de liste des canaux radio -->

Dans `Canal radio`, les administrateurs peuvent ajouter, modifier et supprimer des informations sur les canaux radio. Les canaux radio sont diffusés comme programmes audio vers les terminaux, ce qui permet aux clients d'écouter des stations de radio dans leur chambre.

Appuyez sur le bouton `Ajouter` pour créer un nouveau canal radio.

![Canal radio - Ajouter](_images/program/radio_2.png ':size=80%')

<!-- 📷 Capture à compléter : fenêtre d'ajout/modification d'un canal radio -->

1. <font color="red">**ID**</font> : L'`ID` est généré automatiquement par le système. Plus l'`ID` est petit, plus le canal radio apparaît tôt dans la liste.

2. <font color="red">**Numéro**</font> : Dans `Numéro`, définissez l'ordre d'affichage du canal radio. Plus le numéro est petit, plus sa position est élevée dans la liste.

3. <font color="red">**Nom**</font> : Dans `Nom`, saisissez le nom du canal radio, ex. `BBC World Service`. Ce nom sera affiché sur le terminal.

4. <font color="red">**URL**</font> : Dans `URL`, saisissez l'adresse de lecture du canal radio. Le terminal utilisera cette adresse pour lire le programme radio.

5. <font color="red">**Image**</font> : En téléchargeant l'`image` du canal correspondant, celle-ci sera affichée dans la liste des canaux radio du terminal.

## Lecture en direct forcée

> Introduction

![Lecture en direct forcée](_images/program/forced_play_1.png ':size=80%')

<!-- 📷 Capture à compléter : page de gestion de la lecture en direct forcée -->

Dans `Lecture en direct forcée`, les administrateurs peuvent créer une tâche de lecture forcée : tous les décodeurs enregistrés (ou ceux spécifiés) seront forcés de passer à une source en direct désignée pendant une fenêtre temporelle, et la page de lecture sera verrouillée pendant la tâche. Si le client tente de sortir, le terminal revient automatiquement. Cette fonction est généralement utilisée pour les annonces de l'hôtel ou les diffusions obligatoires (ex. vidéos de sécurité incendie).

### Créer une tâche de lecture forcée

![Lecture en direct forcée - Créer](_images/program/forced_play_2.png ':size=80%')

<!-- 📷 Capture à compléter : fenêtre de création d'une tâche de lecture forcée -->

Appuyez sur le bouton `Ajouter` / `Créer une tâche` pour créer une nouvelle tâche de lecture forcée. Une seule tâche peut être active à la fois ; la création d'une nouvelle tâche annulera la précédente.

1. <font color="red">**Type de source de lecture**</font> : Sélectionnez la source de la lecture forcée :
   - `Chaîne TV en direct` : choisissez une chaîne existante dans la liste.
   - `URL personnalisée` : saisissez une adresse de flux personnalisée (doit être `http`/`https`, et ne peut pas être une adresse intranet).

2. <font color="red">**Heure de début**</font> : L'heure de début de la tâche, au format `yyyy-MM-dd HH:mm`. Vous pouvez aussi démarrer immédiatement avec une durée.

3. <font color="red">**Heure de fin**</font> : L'heure de fin de la tâche, au format `yyyy-MM-dd HH:mm`. L'heure de fin doit être postérieure à l'heure de début.

### Surveiller l'état de la tâche

![Lecture en direct forcée - Surveillance](_images/program/forced_play_3.png ':size=80%')

<!-- 📷 Capture à compléter : surveillance de la tâche/détails du dispositif -->

Après la création de la tâche, la page de gestion affiche en temps réel les statistiques d'exécution de tous les terminaux cibles :

- Compteurs **En attente / Envoyé / Exécuté / Échoué / Expiré** et le nombre total de terminaux.
- **Détails du dispositif** : l'état de la commande de chaque terminal (En attente / Envoyé / Exécuté / Échoué / Expiré), l'heure d'envoi, l'heure de confirmation et le motif de l'échec.
- **Tâches historiques** : voir toutes les tâches de lecture forcée passées.
- **Renvoyer** : renvoi groupé des commandes échouées d'une tâche.
- **Export CSV** : exporter les détails des commandes d'une tâche sous forme de fichier CSV pour archivage.

Appuyez sur le bouton `Annuler` pour annuler la tâche active à tout moment. Une fois annulée, les terminaux cesseront d'être forcés et reviendront à la normale.
