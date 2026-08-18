# Paramètres de licence

> Introduction

![Licence](_images/license/license_1.png ':size=80%')

<!-- 📷 Capture à compléter : page de gestion de la licence -->

Dans `Licence`, les administrateurs gèrent la licence du système IPTV. La licence contrôle le nombre de décodeurs pouvant se connecter au système et la période de validité. Lorsque la licence est invalide ou expirée, les nouveaux terminaux ne peuvent pas s'enregistrer sur le système.

## État de la licence

![État de la licence](_images/license/license_2.png ':size=80%')

<!-- 📷 Capture à compléter : informations sur l'état de la licence -->

La page de licence affiche les informations actuelles de la licence :

<font color="red">**État**</font> : L'état actuel de la licence (valide / invalide / expirée / non activée).

<font color="red">**Nom du client**</font> : Le nom du client lié à la licence.

<font color="red">**Connexions max.**</font> : Le nombre maximum de décodeurs autorisés à se connecter au système.

<font color="red">**Date d'expiration**</font> : La date d'expiration de la licence.

<font color="red">**Raison de l'échec**</font> : Si la licence est invalide, la raison de l'échec est affichée ici.

## Empreinte

![Empreinte](_images/license/license_3.png ':size=80%')

<!-- 📷 Capture à compléter : empreinte du serveur -->

Appuyez sur le bouton `Empreinte` pour générer l'empreinte du serveur actuel. L'empreinte est un identifiant unique du matériel du serveur ; elle doit être fournie à l'émetteur de la licence afin qu'une licence liée à ce serveur puisse être générée.

Appuyez sur le bouton `Télécharger` pour télécharger le fichier d'empreinte et l'envoyer à l'émetteur de la licence.

## Télécharger la licence

![Télécharger la licence](_images/license/license_4.png ':size=80%')

<!-- 📷 Capture à compléter : téléchargement du fichier de licence -->

Après avoir obtenu le fichier de licence auprès de l'émetteur :

1. Cliquez sur le bouton `Télécharger` sur la page de licence.
2. Dans la boîte de dialogue, sélectionnez le fichier de licence.
3. Appuyez sur `Soumettre`. Le système vérifie le fichier de licence (signature, liaison client, date d'expiration et défense contre le recul de l'horloge). Si la vérification réussit, la licence prend effet immédiatement ; sinon, la raison de l'échec est affichée sur la page.
