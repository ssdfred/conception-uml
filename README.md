# conception

## Gestionnaire d'activités scolaires pour le collège "Les Sardines"

## Contexte

Ce projet vise à développer un logiciel pour gérer l'activité scolaire du collège "Les Sardines" de Kelville. Le logiciel remplacera les feuilles Excel actuellement utilisées et dématérialisera certaines activités.

## Fonctionnalités

Le logiciel permettra aux utilisateurs de :

- Saisir les informations des élèves et des classes
- Gérer les emplois du temps des différentes classes
- Saisir les notes et appréciations
- Saisir les dates de conseil de classes et des appréciations
- Saisir les dates de vacances scolaires

## Utilisateurs

Le logiciel sera utilisé par l'équipe dirigeante du collège, les professeurs, les parents d'élèves et les élèves. Chaque utilisateur devra s'authentifier avant d'accéder à une page d'accueil comportant un menu qui dépend de son profil.

![Diagramme d'utilisation](/Diagramme%20scollege.png)

## Diagramme d'activités de la page de connexion

Nous travaillons actuellement sur le diagramme d'activités pour la page de connexion à l'application web du collège "Les Sardines" de Kelville.

### Les Besoins

Pour se connecter, un utilisateur doit saisir son identifiant ainsi que son mot de passe. Voici les différentes étapes du processus de connexion :

- Si la connexion réussit, l'utilisateur est redirigé vers la page d'accueil.
- Si l'utilisateur a un identifiant inconnu, un message d'erreur est affiché : "Votre identifiant n'est pas connu. Veuillez vérifier vos informations de connexion." et la page de connexion s'affiche à nouveau.
- Si le mot de passe est incorrect, un compteur d'essais incorrects est incrémenté de 1, un message d'erreur est affiché : "Votre mot de passe est incorrect. Veuillez vérifier vos informations de connexion." et la page de connexion s'affiche à nouveau.
- Si le nombre d'essais incorrects dépasse 3, le compte de l'utilisateur est bloqué et un message d'erreur est affiché : "Votre compte a été bloqué en raison d'un trop grand nombre d'erreurs. Veuillez contacter le secrétariat du collège."

Nous mettrons à jour ce README avec le diagramme d'activités une fois qu'il sera terminé.

![Diagramme d'activités](./images/Diagramme%20activité.drawio.png)
## Technologies

Le logiciel sera une application web. Les technologies spécifiques utilisées seront déterminées à une date ultérieure.

## Développement

Le développement du logiciel est en cours. Les mises à jour seront publiées sur ce site au fur et à mesure de leur disponibilité.