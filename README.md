# EclipiumServerManager
## Un gestionnaire d'applications utilisant systemd
Il vous permettera de gérer des applications NodeJS, Python, Java, .NET 5/6/Core 3.1, et Go sous les distributions Linux utilisant systemd 
(Principalement testé sur Fedora et Almalinux, les distributions basées sur Debian ne sont pas encore supportées).

## Liste des commandes

```
esm list => Affiche la liste des applications hébergées
esm status <app> => Affiche le statut d'une application
esm log <app> => Affiche l'historique de la console de l'application
esm start <app> => Démarre une application
esm stop <app> => Arrête une application
esm restart <app> => Redémmare une application
esm kill <app> => Tue le processus d'une application
esm enable <app> => Active le démarrage automatique de l'application au démarrage du système
esm disable <app> => Désactive le démarrage automatique de l'application au démarrage du système
esm delete <app> => Supprime l'application
esm rename <app> <new-name> => Renomme l'application
esm backup <app> => Crée une sauvegarde de l'application
esm backup all => Crée une sauvegarde de toutes les applications
esm list-backups => Liste toutes les sauvegardes
esm list-backups <app> => Liste les sauvegardes d'une application
esm delete-backup <backup-name> => Supprime une backup si elle existe
esm restore-backup <backup-name> => Restaure une backup si elle existe

```
