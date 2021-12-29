# Firewall Linux
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](http://forthebadge.com)  

## Pour commencer

Iptables est le programme en ligne de commande pour l'espace utilisateur,
utilisé pour configurer l'ensemble des règles de filtrage de paquets et
de NAT sous Linux. Il est destiné aux administrateurs système et réseau.

Systemd est un gestionnaire de système et de services pour Linux. Il
fournit des capacités de parallélisation agressives, utilise l'activation
de sockets et D-Bus pour lancer les services, propose le démarrage à la
demande de démons, garde une trace des processus grâce aux groupes de
contrôle Linux, maintient les points de montage et de montage automatique
et implémente une logique élaborée, transactionnelle et basée sur des
dépendances, de contrôle de services.

### Pré-requis

#### Vous devez avoir les priviléges root

- iptables => version : 1.8.7
- systemd => version : 247.3-6

### Installation

_Donné les droits d'exécution aux fichiers :_ Executez la commande ``chmod +x firawall flush firewall.service`` pour commencer ensuite [...]
_Copier les fichiers dans /etc :_ Executez la commande ``cp firewall flush /etc/ && cp firewall.service /etc/systemd/system`` [...]

## Démarrage

_L'activer au démarage :_ Executez la commande ``systemctl enable firewall.service`` [...]
_Status le service :_ Executez la commande ``systemctl status firewall.service`` [...]

## Par default

_Commande pour remétrer à zéro les règles :_ Executez la commande ``cd /etc/ && ./flush.sh`` [...]

## Versions

_stable :_ **Dernière version stable :** 1.0

## Auteurs

* **Skulls-sky** _alias_ [@outout14](https://github.com/skulls-sky)




