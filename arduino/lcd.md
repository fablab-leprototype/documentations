---
layout: arduino
title: Afficheur LCD
---
# Introduction

Il est courant dans les kits arduino de proposer un écran LCD. Celui que j'ai
dans mon kit est un 1602a.

Mon kit fournissait en outre un contrôleur pour l'écran, nous avons donc deux
solutions:

* Soit on cable directement l'écran sur l'arduino
* Soit on passe par le contrôleur I2C fourni

La deuxième solution permet d'avoir moins de cables à brancher sur l'arduino,
ce qui peut permettre de privilégier d'autres périphériques sur les entrées
sorties.

# Méthode 1: LCD sans contrôleur I2C

Cf [Ce tutoriel](http://www.dreamdealer.nl/tutorials/connecting_a_1602a_lcd_display_and_a_light_sensor_to_arduino_uno.html){:.text-danger}.


# Méthode 2: LCD avec contrôleur I2C

Voir [Ce post de blog](http://blog.mklec.com/how-to-use-iici2c-serial-interface-module-for-1602-lcd-display/){:.text-danger}.

