# bloc_project

`Project Current State: 💻Developing💻`

This is a base project to implement the bloc pattern in Flutter.
In this case, this is just the base project. Below, in the [Getting Started](#getting-started) section,
you will find the basic installation for this project and the initial dependencies that I think
are required for this project.

This project is being completed on the Twitch Channel [NecroCoding](https://www.twitch.tv/necrocoding).

For more information about the project and some explanations in Spanish about the basic project structure and
architecture, check out the YouTube Channel [Necro Coding].

## Prerequisites

- [Flutter](https://flutter.dev/)
- [Dart](https://dart.dev/)
- Packages:
  - [bloc](https://pub.dev/packages/bloc)
  - [flutter_bloc](https://pub.dev/packages/flutter_bloc)
  - [dio](https://pub.dev/packages/dio)
  - [sqflite](https://pub.dev/packages/sqflite)
  - [reflectable](https://pub.dev/packages/reflectable)
  - [shared_preferences](https://pub.dev/packages/shared_preferences)
  - [equatable](https://pub.dev/packages/equatable)
  - [sqflite_simple_dao_backend](https://pub.dev/packages/sqflite_simple_dao_backend)
  - [logger](https://pub.dev/packages/logger)
  
To use the Visual Studio Code extension "Pubspec Assist", I provide you with the list
of packages that you need to pass to this extension.
```bloc,flutter_bloc,dio,sqflite,reflectable,shared_preferences,equatable,sqflite_simple_dao_backend,logger```

## Getting Started

First of all. I will resume what I want to do in this project and It will be my [Index](#table-of-contents).

In my case, I want to make an Android/IOs app in order to learn about bloc pattern. I will
be using the official documentation that I provide on Documentation section.

This project will have a local database and it will connect to an api to get information.

We are makin a real app that you can use for fun or you can sell. In my case is just portfolio.

This app will be a recipe app. These are the principal points to develop.

### Table of Contents

  1. [User Authentication](#user-authentication)
  2. [Home Screen](#home-screen)
  3. [Recipe Details](#recipe-details)
  4. [Search Recipes](#search-recipes)
  5. [Favorites](#favorites)
  6. [User Profile](#user-profile)
  7. [Publish Recipes](#publish-recipes)
  8. [Notifications](#notifications)
  9. [Settings](#settings)

## User Authentication

Implement user login and registration. This will provide an opportunity to learn about managing authentication states with bloc.

## Home Screen

After authentication, users will be redirected to the home screen where they can view a list of recipes. This is a chance to learn how to handle events and states with bloc.

## Recipe Details

By clicking on a recipe, users can view the recipe details. This will involve navigating between screens and passing data between them.

## Search Recipes

Users can search for recipes by name. This will involve using a bloc to manage the search state.

## Favorites

Users can mark recipes as favorites. These recipes will be stored locally in the database using sqflite.

## User Profile

Users can view and edit their profile. This will involve managing user states with bloc.

## Publish Recipes

Users can publish their own recipes. This will involve managing forms and data validation with bloc.

## Notifications

Users will receive notifications when new recipes are published. This will involve using background services and managing states with bloc.

## Settings

Users can change the application settings, such as the theme and language. This will involve using shared_preferences to store user settings and managing states with bloc.
