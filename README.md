# FCSC 2022 I2CyouToo

Un ami vous affirme qu'une EEPROM de 1024 bits branchée à son Arduino est une solution extrêmement sécurisée pour 
stocker ses secrets, vu que le protocole utilisé est “obfusqué” et “bas niveau” selon ses dires, “pas comme l'USB 
qui est hotplug et qu'on peut brancher directement sur n'importe quel OS !”.

Voulant le confronter à ses inepties, vous sortez votre analyseur logique pour sniffer la communication entre 
l'Arduino et l'EEPROM lorsqu'il tape son secret. Pourrez-vous remonter à ce dernier avec vos logiciels **Sigrok** 
et **gtkwave** ?

Fichier :
- [capture.vcd](capture.vcd)

Auteur : rbe

Origine : [I2CyouToo](https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-i2c-you-too/)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2022-hardware-i2c-you-too.git

> cd fcsc2022-hardware-i2c-you-too


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-i2c-you-too/