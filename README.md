# Flutter

A new Flutter Lib.

## Getting Started

This Doc is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:


- [Flutter: Snaplist](https://pub.dev/documentation/snaplist/latest/ ) = Une petite bibliothèque confortable qui vous permet de créer des vues de liste accrochables.

- [Flutter: Widget](https://docs.flutter.dev/ ) = Un incontournable, les widgets de flutter.

- [Flutter: Freezed](https://pub.dev/packages/freezed ) = code generator for data-classes/unions/pattern-matching/cloning
En gros, vos réponses API et vos modèles. Freezed s’occupe de tout, du equals aux membres privés en passant par le parsing json (il s’appuie sur json_serializable pour ça). Bref, un must have.

- [Flutter: SVG](https://pub.dev/packages/flutter_svg) 
= Pour intégrer des icônes, avant on avait les formats classiques (png, jpg), le problème c’est qu’avec toutes les résolutions d’écrans, on a 2 side effectsc. Le problème, c’est qu’il n’y a rien de natif sur Flutter pour intégrer ça. Heureusement, flutter_svg est là pour ça. Très simplement on met l’image au format svg dans nos assets et il ne reste plus qu’à.
- [Flutter: Provider](https://pub.dev/packages/provider) = 
Provider est une librairie pour aider le state management, c’est-à-dire créer et mettre à jour vos écrans en fonction de certaines actions (utilisateurs, ou api).

- [Flutter: Auto-Size](https://pub.dev/packages/auto_size_text) = La problématique: vous avez un écran avec une taille limitée, et vous voulez afficher un texte dedans. Les solutions : couper le texte qui dépasse, limiter le nombre de caractères en entrée, ou resizer le texte au fur et à mesure.

- [Flutter: Mysql1](https://pub.dev/packages/mysql1) = Un pilote MySQL pour le langage de programmation Dart. Fonctionne sur Flutter et sur le serveur. Cette bibliothèque vise à fournir une interface facile à utiliser pour MySQL. mysql1 est à l'origine un fork du pilote SQLJocky.

- [Flutter: SQFLite](https://pub.dev/packages/sqflite)

- [Flutter: Parse](https://parseplatform.org/) = Créez des applications plus rapidement avec le stockage d'objets et de fichiers, l'authentification des utilisateurs, les notifications push, le tableau de bord et bien plus encore. 

- [Flutter: Translate](https://pub.dev/packages/flutter_translate) = Flutter Translate is a fully featured localization / internationalization (i18n) library for Flutter.
It lets you define translations for your content in different languages and switch between them easily.

- [Flutter: Cupertino](https://pub.dev/packages/cupertino_icons) = Il s'agit d'un référentiel d'actifs contenant l'ensemble par défaut d'actifs d'icônes utilisés par les widgets Cupertino de Flutter.

- [Flutter: LatLong](https://pub.dev/packages/latlong2) = For flutter map

- [Flutter: Getx](https://pub.dev/packages/get) = GetX est une solution extra-légère et puissante pour Flutter. Il combine une gestion d'état hautes performances, une injection de dépendance intelligente et une gestion des itinéraires rapide et pratique.

- [Flutter: Toast](https://pub.dev/packages/fluttertoast) = Va voir !



### Modules de Formation :

- [Cours API Rest: OpenClassRoom](https://openclassrooms.com/fr/courses/6031886-debutez-avec-les-api-rest)

- [Cours Flutter: UDEMY (Non Free)](https://www.udemy.com/course/flutter-dart-creez-des-applications-pour-ios-et-android/)

- [Cours Flutter: CommentCoder]( https://www.commentcoder.com/apprendre-flutter/)

- [Cours Youtube: Graven](https://www.youtube.com/watch?v=eKoo5gkEFjQ&list=RDCMUCIHVyohXw6j2T-83-uLngEg&index=2)

- [37H de vidéo: Flutter](https://www.youtube.com/watch?v=VPvVD8t02U8)

- [RoadMap](https://roadmap.sh/flutter)


# Laravel

[Laravel Site Web](https://laravel.com/)

### Description :
Nous aimons appeler Laravel un framework "progressif". Nous entendons par là que Laravel grandit avec vous. Si vous faites vos premiers pas dans le développement Web, la vaste bibliothèque de documentation, de guides et de didacticiels vidéo de Laravel vous aidera à apprendre les ficelles du métier sans être submergé.

Laravel est incroyablement évolutif. Grâce à la nature conviviale de la mise à l'échelle de PHP et à la prise en charge intégrée de Laravel pour les systèmes de cache distribués rapides comme Redis, la mise à l'échelle horizontale avec Laravel est un jeu d'enfant. En fait, les applications Laravel ont été facilement mises à l'échelle pour gérer des centaines de millions de demandes par mois.

### Wave :

Pour débuter je vais vous parler de [Wave](https://devdojo.com/wave), Wave est le kit de démarrage Software as a Service ultime, doté de fonctionnalités impressionnantes telles que l'authentification, les abonnements, les factures, les annonces, les profils d'utilisateurs et bien plus encore ! 

- Authentification entièrement chargée, vérification des e-mails et réinitialisation du mot de passe. Authentification en un clin d'œil !

- Profils d'utilisateurs personnalisables. Permettez à vos utilisateurs de saisir des données et de personnaliser facilement leurs profils d'utilisateurs.

- Accordez des autorisations aux utilisateurs en fonction des rôles, vous pouvez ensuite attribuer un rôle à un plan spécifique.

## install Laravel :

Avant de créer votre premier projet Laravel, vous devez vous assurer que PHP et Composer sont installés sur votre machine locale. Si vous développez sur macOS, PHP et Composer peuvent être installés via [Homebrew](https://brew.sh/).

- Après avoir installé PHP et Composer, vous pouvez créer un nouveau projet Laravel via la commande Composer create-project
```
$ composer create-project laravel/laravel example-app
```
> Si vous développez sur un Mac et que Docker Desktop est déjà installé, vous pouvez utiliser une simple commande de terminal pour créer un nouveau projet Laravel. Par exemple, pour créer une nouvelle application Laravel dans un répertoire nommé "example-app", vous pouvez exécuter la commande suivante dans votre terminal

```
$ curl -s "https://laravel.build/example-app" | bash
```
