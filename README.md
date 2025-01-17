![Benchmark screenshot](https://github.com/mikasmart/moodle-report_benchmark/blob/master/screenshot.jpg)

# Moodle Benchmark plugin

[![GitHub release](https://img.shields.io/github/release/mikasmart/moodle-report_benchmark.svg)](https://github.com/mikasmart/moodle-report_benchmark/releases/latest)
[![GitHub Release Date](https://img.shields.io/github/release-date/mikasmart/moodle-report_benchmark.svg)](https://github.com/mikasmart/moodle-report_benchmark/releases/latest)
[![GitHub last commit](https://img.shields.io/github/last-commit/mikasmart/moodle-report_benchmark.svg)](https://github.com/mikasmart/moodle-report_benchmark/commits/)

Performs various performance checks to determine the quality of the Moodle platform. It is compatible with Moodle 2.7 to 3.7.

## Availability

Code available at [https://github.com/mikasmart/moodle-report_benchmark](https://github.com/mikasmart/moodle-report_benchmark).

### Release notes

* 2019-07-24, version v1.2.0: Compatibility with Moodle 3.7.x. See [release v1.2.0](https://github.com/mikasmart/moodle-report_benchmark/releases/tag/v1.2.0).
* 2018-10-28, version v1.1.0: RGPD [Fix #18](https://github.com/mikasmart/moodle-report_benchmark/issues/18) and compatibility with Moodle 3.5 and 3.6
* 2017-09-07, version v1.0.3: [Fix #13](https://github.com/mikasmart/moodle-report_benchmark/issues/13)
* 2017-09-07, version v1.0.2: Update & test for moodle 3.2, 3.3
* 2016-07-08, version v1.0.1: Production version - Moodle Coding style
* 2016-07-02, version v1.0.0: Production version
* 2016-06-26, version v0.9-r3 (beta): Pre-production version
* 2016-06-26, version v0.9-r1 (beta): Preview version - Beta
* 2016-06-25, version 0.0.1b (alpha): all stuff is now in ./moodle/report/benchmark
* 2016-06-24, version 0.0.1a (alpha): Preview version - Alpha

## Installation
### English

#### Manually
* Clone or download the ***master*** *branch* directly on your  ./moodle/report directory server
* Rename it to benchmark
* Logon as admin on your Moodle server
* Go to "Site Administration > Notification"
* Install the new plugin as usual

#### Automatically
* [Download the zip](https://github.com/mikasmart/moodle-report_benchmark/archive/master.zip)
* Open the Zip and rename the folder *benchmark-master* in *benchmark*
* Logon as admin on your Moodle server
* go to "Site Administration > Plugins > Install plugins"
* Put the zip file i, *ZIP package*
* Clic on *Install plugin from the ZIP file*

### French

#### Manuellement
* Cloner ou télécharger *la branche* ***master*** directement vers le dossier ./moodle/report de votre serveur
* Renommez-le benchmark
* Logez-vous comme administrateur
* Allez à "Administration du site > Notification"
* Installez le nouveau plugin comme d'habitude

#### Automatiquement
* [Télécharger le zip](https://github.com/mikasmart/moodle-report_benchmark/archive/master.zip)
* Ouvrir le Zip et renommer le dossier *benchmark-master* en *benchmark*
* Logez-vous comme administrateur
* Allez à "Administration du site > Plugins > Installer des plugins"
* Placer le zip dans la zone *Paquetage ZIP*
* Cliquer sur *Installer le plugin à partir du fichier Zip*

## Usage

### English
As Admin logon your server, go to "Site Administration > Reports > Benchmark"

### French
Connectez-vous comme Administrateur, allez à "Administration du site > Rapports > Benchmark"

## Requirement

- Be an admin or a manager

## Requirement

- Moodle installed
- 1 minute (time to prepare a coffee / tea during the test)

## Roadmap

- Add more tests (please [send your test on the Moodle Forum](https://moodle.org/mod/forum/discuss.php?d=335282))
- Add sharing score on a global website (?)
- Add more languages

## Thanks

* To the [Moodle community](https://moodle.org/) and specially the [reviewers](https://moodle.org/mod/forum/discuss.php?d=335357)
* To Nicolas Martignoni, for help, time and perspective
* To Jean Fruitet, for help, time and traduction
* To [Martin Dougiamas](https://en.wikipedia.org/wiki/Martin_Dougiamas), for giving us Moodle

## Benchmark records

* 1st : Sergio Rabellino - 21 points
* 2nd : Richard Oelmann - 90 points
* 3rd : Usman Asar - 93 points

## License

Copyright ©2016 onwards, Mickaël PANNEQUIN <mickael.pannequin@gmail.com>

* All the source code is licensed under GPL 3 or any later version
* The documentation is licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details
