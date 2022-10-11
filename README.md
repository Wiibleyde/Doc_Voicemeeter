# Documentation installation de Voicemeeter *par Wiibleyde*

Quelle version à installer ?
- Voicemeeter classic (gratuit) : simple, mais pas de possibilité de mixer plusieurs sources audio (micro, musique, etc.)
- Voicemeeter Banana (gratuit) : plus complet, possibilité de mixer plusieurs sources audio (micro, musique, etc.)
- Voicemeeter Potato (payant) : plus complet, possibilité de mixer plusieurs sources audio (micro, musique, etc.) et de rajouter des effets (réverbération, égaliseur, etc.) (possibilité d'essai gratuit à vie mais bon pas pratique)

Pour la suite de la doc, je vais utiliser Voicemeeter Banana, mais les manipulations sont les mêmes pour Voicemeeter potato, mais étant donné qu'il est payant, je ne vais pas le détailler.

## Installation

Lien pour voicemeeter banana : https://download.vb-audio.com/Download_CABLE/VoicemeeterSetup_v2064.zip

Après avoir téléchargé le fichier, il faut l'extraire et lancer l'installation, un fichier nommé "VoicemeeterSetup.exe" va s'ouvrir, il suffit de suivre les instructions.
Il faut ensuite redémarrer son ordinateur pour les périphériques audio de Voicemeeter soient utilisables.

## Configuration

L'intérêt de Voicemeeter est de pouvoir mixer plusieurs sources audio (micro, musique, etc.) et de pouvoir les envoyer sur plusieurs périphériques audio (casque, enceintes, etc.).	

Par exemple :
- Mixer le son de la musique, du PC et du micro pour l'envoyer sur le casque et en stream
- Mixer le son de la du micro pour l'envoyer dans le jeu (team speak, discord, etc.)
- Ou alors mixer le son de la musique et du micro pour l'envoyer sur le jeu (team speak)

Voicemeeter Banana nous offre deux sortie virtuelle (VAIO et Aux VAIO), on peut dit que :
- VAIO est la sortie principale (stream)
- Aux VAIO est la sortie secondaire (jeu, team speak, etc.)

Voici une image pour mieux comprendre :  
![banana](https://raw.githubusercontent.com/Wiibleyde/Doc_Voicemeeter/main/assets/bananaPict.png)

On peut distinguer 4 parties :  
![banana_separe](https://raw.githubusercontent.com/Wiibleyde/Doc_Voicemeeter/main/assets/bananaPictPart.png)  
- La première partie (à gauche) est la partie de configuration des périphériques audio **PHYSIQUES** (casque, enceintes, etc.)  
- La deuxième partie (au milieu) est la partie de configuration des périphériques audio **VIRTUELLES** (VAIO (PC) et Aux VAIO (musique/truc que tu veux pourrais devoir envoyer en jeu))  
- La troisième partie (à droite mais pas entièrement) est la partie de configuration des sorties audio **PHYSIQUES** (casque, enceintes, etc.)  
- La quatrième partie (à droite) est la partie de configuration des sorties audio **VIRTUELLES** (VAIO (sortie stream), Aux VAIO (sortie jeu, team speak, etc.))

### Configuration des périphériques audio physiques

Pour ajouter le micro, il faut cliquer sur `Select Input Device` et sélectionner le micro (je crois que tu as une focusrite donc le périphérique devrait se nommer comme ça).

Pour le renvoyer dans le jeu il faut cliquer sur les boutons en dessous :   
![banana_micro](https://raw.githubusercontent.com/Wiibleyde/Doc_Voicemeeter/main/assets/Sorties.png)  
Ces boutons renvoient à la partie de configuration des sorties audio physiques et virtuelles. Par exemple :
- Le bouton `A1` renvoie à la partie de configuration des sorties audio physiques et virtuelles, et plus précisément à la sortie `A1` (casque)
- Le bouton `A2` renvoie à la partie de configuration des sorties audio physiques et virtuelles, et plus précisément à la sortie `A2` (Ce que tu veux)
- ...
- Le bouton B1 permet de renvoyer le son vers la première sortie virtuelle (VAIO : stream)
- Le bouton B2 permet de renvoyer le son vers la deuxième sortie virtuelle (Aux VAIO : jeu, team speak)

### Configuration de la sortie pc

Pour que voicemeeter s'occupe du son du pc, il faut simplement sélectionner dans Windows le périphérique `Voicemeeter VAIO` comme périphérique.

### Configuration de la sortie de logiciel

Pour que voicemeeter s'occupe du son d'un logiciel et l'envoie sur la sortie virtuelle 2, il faut sélectionner dans le logiciel le périphérique `Voicemeeter Aux VAIO` comme périphérique dans le mélangeur de son de Windows.
