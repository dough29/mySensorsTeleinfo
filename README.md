# mySensorsTeleinfo
Sketch MySensors permettant de récupérer les informations de Téléinfo EDF

Basé sur la librairie suivante : https://github.com/jaysee/teleInfo

## Liste de courses
- Arduino Pro Mini
- Si besoin régulateur 3.3v pour la radio
- Optocoupleur SFH620A
- Résistance 1.5kΩ en amont de la borne n°1 de l'opto


## Branchements
- compteur I1 -> résistance 1,5kΩ -> borne n°1 opto
- compteur I2 -> borne n°2 opto
- Arduino borne A2 -> borne n°4 opto
- Arduino borne GND -> borne n°3 opto