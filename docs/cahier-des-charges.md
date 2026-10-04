# Challenge Bat-ID — Hack VS (Foire du Valais 2026)

> Cahier des charges du challenge Bat-ID. Document destiné aux équipes et à leurs
> assistants IA. La documentation produit complète est disponible séparément :
> https://bat-i.apcom.app/llms-full.txt — chargez les deux pour être pleinement
> contextualisé.

Événement : Hack VS, Espace Innothèque, 3–4 octobre 2026.
Cahier des charges en ligne : https://bat-i.apcom.app/hack-VS/
Documentation produit (AI-ready) : https://bat-i.apcom.app/llms-full.txt
Site institutionnel : https://bat-i.ch

## Titre du challenge

Comment optimiser l'application Bat-ID pour offrir une expérience plus ergonomique
et immersive ?

## Contexte

Bat-ID est une application suisse destinée aux propriétaires immobiliers et fait
partie de l'écosystème Bat-i. Son ambition est de devenir l'espace de référence du
propriétaire pour gérer, suivre et organiser son bien immobilier.

Principales fonctionnalités :

- enregistrer ses parcelles et activer leur suivi ;
- créer des zones d'alerte autour d'un bien ou dans une zone libre ;
- recevoir une notification ou un e-mail lorsqu'une nouvelle publication du Bulletin
  officiel concerne une zone suivie (mise à l'enquête, demande d'autorisation de
  construire) ;
- consulter les publications concernées, leurs sources et les documents officiels
  associés ;
- organiser les documents liés au bien, en les stockant dans Bat-ID ou en connectant
  un cloud personnel ;
- transmettre des documents de manière sécurisée via des liens de partage ;
- créer des espaces partagés pour gérer un bien en commun (cadre familial, vente).

Accessible sur mobile et desktop. Deux offres :

- Découverte (gratuit) : accès aux publications de sa commune, sans suivi
  personnalisé ni système d'alerte lié à ses propres biens ;
- Averti (suivi) : suivi personnalisé, selon le nombre de biens suivis et les espaces
  partagés nécessaires.

## Problématique

Au fil de son développement, l'application s'enrichit de nouvelles fonctionnalités.
Cette richesse soulève un double enjeu : offrir une prise en main simple et ergonomique
pour éviter le décrochage lors des premières utilisations, puis créer une expérience
engageante qui permet au propriétaire de comprendre rapidement la valeur de Bat-ID,
d'avoir envie d'y revenir et de percevoir l'intérêt des fonctionnalités de l'offre Averti.

## Description du challenge

Analyser l'expérience actuelle et identifier des optimisations concrètes et réalistes.
Pistes d'analyse :

- l'organisation et la compréhension des fonctionnalités ;
- la navigation, l'ergonomie et la fluidité de l'application ;
- le parcours utilisateur, de l'onboarding aux usages courants ;
- la manière dont l'utilisateur comprend progressivement la valeur de Bat-ID et les
  actions à sa disposition ;
- la cohérence de l'expérience entre mobile et desktop ;
- la manière dont l'application accompagne l'utilisateur dans la durée et facilite son
  retour lorsqu'une information nécessite son attention.

### Cadre à respecter

- Pas de refonte de l'application : optimisations ciblées, pas une reconstruction.
- Fonctions de base conservées : le fonctionnement général de Bat-ID reste en place.
- L'inscription n'est pas un sujet central : la procédure de création de compte
  (mobile ou desktop) sort du périmètre du challenge.

## Livrables attendus

Fil rouge de tous les livrables : la couverture des deux environnements — desktop et
application mobile — et de leur cohérence.

- Un diagnostic de l'expérience actuelle, mettant en évidence les principaux points de
  friction, incompréhensions ou étapes pouvant compliquer l'utilisation de Bat-ID ;
- Des propositions concrètes d'optimisation (organisation, navigation, ergonomie, accès
  aux fonctionnalités) ;
- Des recommandations sur le parcours utilisateur, de l'onboarding à l'utilisation
  régulière, en tenant compte des offres Découverte et Averti ;
- Une priorisation des recommandations selon leur impact et leur complexité de mise en
  œuvre.

### Format de rendu — rapports et maquettes

- Souhaité : un fichier HTML autonome, CSS et JavaScript embarqués ; les visuels
  (images, maquettes, croquis, esquisses) peuvent l'accompagner comme assets. Support de
  présentation, pas un prototype codé.
- À éviter : PDF et suites bureautiques.
- Non souhaité : les rendus hébergés sur des solutions en ligne, qu'elles nécessitent ou
  non un identifiant ou la création d'un compte.

## Kit technique du challenge

Le hackathon se joue entièrement sur l'environnement de démonstration.

- Connexion (démo) : https://demo.bat-id.ch/qr-login
- Application Android : APK démo https://cloud.apcom.app/index.php/s/wSD4MqqQnKTBeqA
  (à installer manuellement, hors Play Store).
- iOS : aucun accès test sur la démo. Pour juger le rendu iOS, installer l'app de
  production depuis l'App Store.
- Compte : à créer depuis l'application mobile ou depuis le desktop. Nécessite un numéro
  de mobile et un e-mail valides et accessibles.
- Cartes de crédit de test : https://docs.datatrans.ch/docs/testing-credentials — carte
  Visa conseillée 4111 1111 1111 1111, exp. 06/28, CVC 123, mot de passe 3D Secure 4000.
- Documentation produit : https://bat-i.apcom.app (version AI-ready :
  https://bat-i.apcom.app/llms-full.txt).

Impératif : les applications de production (App Store / Play Store) ne sont pas reliées
à la démo. Pour travailler sur le challenge, installez impérativement l'APK Android. La
prod iOS sert uniquement à visualiser le rendu.

## Prise en main pratique

Partir d'un environnement vierge fait partie du challenge : chaque équipe crée et alimente
ses propres comptes, comme un nouveau client. Aucun compte pré-rempli n'est fourni.

### Comptes

Chaque équipe crée ses propres comptes utilisateur (un par numéro de mobile). Gardez-en
certains en Découverte, passez-en d'autres en Averti à l'aide des cartes sandbox Datatrans.

### Alertes et géoinformation en action

Enregistrez une parcelle en Valais, posez-y une zone d'alerte : les publications du
Bulletin officiel du voisinage remontent. La commune de Nendaz publie aussi sa
géoinformation AIT (voir https://bat-i.apcom.app/solutions/ait/).

Parcelles conseillées : 7787 et 8376, Nendaz — en les sélectionnant, vous obtenez à la
fois les alertes et la géoinformation de la commune.

## Contact technique

Grégory Liand — 079 209 44 78 — gregory.liand@apcom.ch
