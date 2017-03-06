
# FastPokeMap

![Python 2.7](https://img.shields.io/badge/python-2.7-blue.svg) 

Live visualization of all the pokemon (with option to show gyms and pokestops) in your area.Currently runs on a Flask server displaying Google Maps with markers on it.


## Features:

* Shows Pokemon, Pokestops, and gyms with a clean GUI.
* Notifications 
* Lure information
* Multithreaded mode
* Filters
* Independent worker threads (many can be used simulatenously to quickly generate a livemap of a huge geographical area)
* Localization (en, fr, pt_br, de, ru, ko, ja, zh_tw, zh_cn, zh_hk)
* DB storage (sqlite or mysql) of all found pokemon
* Incredibly fast, efficient searching algorithm (compared to everything else available)


## Installation

For instructions on how to setup and run the tool, please refer to the project [documentation](Soon)



## iOS Version

There is an [iOS port](https://github.com/istornz/iPokeGo) in the works. All iOS related prs and issues please refer to this [repo](https://github.com/istornz/iPokeGo).


Building off [tejado's python pgoapi](https://github.com/tejado/pgoapi), [Mila432](https://github.com/Mila432/Pokemon_Go_API)'s API, [leegao's additions](https://github.com/leegao/pokemongo-api-demo/tree/simulation) and [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps). Current version relies primarily on the pgoapi and Google Maps JS API.

Discord icon: "Rocket" by Flat Icons (flaticon.com)
