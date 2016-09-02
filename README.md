
# PokéAlert

![Python 2.7](https://img.shields.io/badge/python-2.7-blue.svg) ![License](https://img.shields.io/github/license/pokemongomap/pokemongo-map.svg)

Live visualization of all the Pokémon (with option to show gyms and pokestops) in your area. This is a proof of concept that we can load all the Pokémon visible nearby given a location. Currently runs on a Flask server displaying Google Maps with markers on it.

## Warnings:

This software is made for learning and experimental purposes, and using it violates Niantic's terms of service for using Pokémon Go. Using it can result in your account being permanently terminated, so use this map at your own risk.

## Features:

* Shows Pokemon, Pokestops, and gyms with a clean GUI.
* Notifications
* Lure information
* Multithreaded mode
* Filters
* Independent worker threads (many can be used simulatenously to quickly generate a livemap of a huge geographical area)
* Localization (en, fr, pt_br, de, ru, ja, zh_tw, zh_cn, zh_hk)
* DB storage (sqlite or mysql) of all found Pokémon
* Incredibly fast, efficient searching algorithm (compared to everything else available)

### Features added in this fork:

* Pokémon sounds from the original Game Boy series added as an option for notifications.

## Installation

For instructions on how to setup and run the tool, please refer to the project [documentation](https://pgm.readthedocs.io/en/develop/) or the [video guide](https://www.youtube.com/watch?v=2ACJHCNZ3ow).

## Information
* [Documentation](https://pgm.readthedocs.io/en/develop/) for installation and usage docs

Forked from [PokemonGoMap](https://github.com/PokemonGoMap/PokemonGo-Map). Building off [tejado's python pgoapi](https://github.com/tejado/pgoapi), [Mila432](https://github.com/Mila432/Pokemon_Go_API)'s API, [leegao's additions](https://github.com/leegao/pokemongo-api-demo/tree/simulation) and [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps). Current version relies primarily on the pgoapi and Google Maps JS API.
