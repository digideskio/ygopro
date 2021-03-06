# ygopro
[![Build Status](https://travis-ci.org/mycard/ygopro.svg?branch=master)](https://travis-ci.org/mycard/ygopro) [![Build status](https://ci.appveyor.com/api/projects/status/qgkqi6o0wq7qn922?svg=true)](https://ci.appveyor.com/project/zh99998/ygopro)

A script engine for "yu-gi-oh!" and sample gui

[中文说明](https://github.com/Fluorohydride/ygopro/wiki/%E4%B8%AD%E6%96%87%E8%AF%B4%E6%98%8E)

###Keys:
* ESC: Minimize the window.
* A: Holding down this button will let the system stop at every timing.
* S: Holding down this button will let the system skip every timing.
* R: Fix the font error.
* F1~F4: Show the cards in your grave, banished zone, extra deck, xyz materials.
* F5~F8: Show the cards in your opponent's grave, banished zone, extra deck, xyz materials.

###Color in card list:
####Background: 
* White = your card, Grey = your opponent's card  

####Text: 
Cards in extra deck or removed: 
* Black = face-up, Blue = face-down

Xyz materials:
* Black = default, Blue = the owner of the xyz material is different from its controller

###Sequence:
* Monster Zone: 1~5, starting from the left hand side.
* Spell & Trap Zone: 1~5, starting from the left hand side.
* Field Zone: 6
* Pendulum Zone: 7~8, starting from the left hand side.
* The others: 1~n, starting from the bottom.

###Deck edit page:
* All numeric textboxs: They support >, =, <, >=, <= signs.
* Card name: Search card names and texts by default, $foo will only search foo in card names, and @foo will search cards of "foo" archetype(due to translation, card name contains "foo" does not mean that card is "foo" card).

### Command-line options:
* -j: Join the host in system.conf file.
* -d: Enter the deck edit page.
* -r: Enter the replay mode page.
* -s: Enter the single mode page.
* -efoo: Load foo as the extra database.

### Directories:
* pics: .jpg card images(177*254).
* pics\thumbnail: .jpg thumbnail images(44*64).
* script: .lua script files.
* textures: Other image files.
* deck: .ydk deck files.
* replay: .yrp replay files.
* expansions: *.cdb will be loaded as extra databases.
