# H5 invité (Libre-service invité)

> Introduction

![H5 invité](_images/guest/guest_1.png ':size=80%')

<!-- 📷 Capture à compléter : entrée/page d'accueil du H5 invité -->

`H5 invité` est une application web mobile destinée aux clients de l'hôtel. Les clients ouvrent la page avec leur téléphone (via un code QR ou un lien) et peuvent utiliser les services IPTV de l'hôtel sans toucher à la télécommande : regarder la TV en direct et la VOD, commander de la nourriture, consulter la facture, demander des services hôteliers et parcourir les installations et les attractions à proximité.

## Accès et vérification

![H5 invité - Vérification](_images/guest/guest_2.png ':size=80%')

<!-- 📷 Capture à compléter : page de vérification invité -->

Le client saisit le **numéro de chambre** et le **nom de famille du client enregistré** sur la page de vérification. Le système vérifie la chambre et le nom de famille (correspondance par préfixe, insensible à la casse) et crée une session invité isolée. La session invité est complètement séparée de la session administrateur.

> **Remarque** : la session invité est propre au navigateur et expire après un délai d'inactivité. Le client doit se vérifier à nouveau après l'expiration de la session.

## TV en direct

![H5 invité - TV en direct](_images/guest/guest_3.png ':size=80%')

<!-- 📷 Capture à compléter : page TV en direct du H5 -->

Le client peut parcourir la liste des chaînes en direct et les lire avec le lecteur H5. Les bouquets de chaînes suivent les mêmes règles de filtrage que le décodeur : seules les chaînes incluses dans les bouquets achetés par la chambre sont affichées. L'achat se fait sur la TV ou à la réception ; le H5 ne fournit pas d'entrée d'achat.

## Vidéo à la demande

![H5 invité - VOD](_images/guest/guest_4.png ':size=80%')

<!-- 📷 Capture à compléter : page VOD du H5 -->

Le client peut parcourir les catégories et les films de la VOD, consulter les détails (affiche, introduction, année, région, taux de clics) et lire le film. Lorsqu'un film comporte plusieurs épisodes/lignes, le client peut sélectionner l'épisode à lire.

## Commande de nourriture

![H5 invité - Nourriture](_images/guest/guest_5.png ':size=80%')

<!-- 📷 Capture à compléter : page de commande de nourriture du H5 -->

Le client peut parcourir les catégories de nourriture et les articles (avec images, prix et descriptions), ajouter des articles au panier et soumettre la commande. La commande est envoyée à la console administrateur pour confirmation. Le client peut également consulter l'historique de ses commandes et leur statut.

## Facture

![H5 invité - Facture](_images/guest/guest_6.png ':size=80%')

<!-- 📷 Capture à compléter : page de facture du H5 -->

Le client peut consulter la facture de consommation actuelle, y compris les relevés de consommation et le montant total, groupés par date.

## Services hôteliers

![H5 invité - Service](_images/guest/guest_7.png ':size=80%')

<!-- 📷 Capture à compléter : page de services hôteliers du H5 -->

Le client peut parcourir les catégories de services hôteliers et les prestations, et soumettre des réservations de services (ex. nettoyage de chambre, blanchisserie, appel de réveil).

## Installations et environs

![H5 invité - Installations](_images/guest/guest_8.png ':size=80%')

<!-- 📷 Capture à compléter : page installations/environs du H5 -->

Le client peut consulter les installations de l'hôtel et les attractions à proximité :

- **Installations** : le contenu des installations (ex. piscine, salle de sport, restaurant) est affiché sous forme de pages intégrées.
- **Environs** : les sites d'intérêt autour de l'hôtel avec images et introductions.

## Langue

Le H5 est bilingue (chinois et anglais). Les clients peuvent changer la langue sur la page.
