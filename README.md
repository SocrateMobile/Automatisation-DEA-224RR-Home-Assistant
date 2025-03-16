# Domotiser un Portail DEA System 224RR avec Shelly Uni

## Introduction
Ce guide explique comment utiliser un Shelly Uni pour automatiser un portail avec un contrôleur DEA System 224RR.

## Matériel Nécessaire
- Un contrôleur DEA 224RR
- Un Shelly Uni
- 4 câbles pour prolonger le câble du Shelly
- Une plaque à soudure de petite taille
- Un capteur de température

## Schéma de la Carte Mère DEA 224RR

![Carte Mère DEA 224RR](images/dea_224rr.jpg)

## Schéma du Capteur de Température

![Capteur de Température](images/capteur_temperature.jpg)

## Schéma de Montage

![Schéma de Montage](images/schema_montage.jpg)

## Schéma de rallonge des câbles

![Schéma rallonge](images/carte.jpg)

## Configuration du Shelly Uni
### Paramétrage des Boutons
1. **Activer l'entrée** : Allez dans les paramètres de l'application et activez l'affichage de l'état de l'entrée.
2. **Configurer le type de bouton** : Dans les paramètres, sélectionnez "Interrupteur autonome".
3. **Minuterie** : Configurez l'arrêt automatique à 00:00:01.

![Configuration Shelly](images/configuration_shelly.jpg)


## Intégration avec Home Assistant
Le capteur de température et d'humidité s'intègre automatiquement dans Home Assistant sans configuration supplémentaire.

![Rendu HA](images/rendu_ha.jpg)

## Rendu du projet

![Rendu](images/projet.jpg)

## Conclusion
Ce projet permet d'automatiser un portail DEA 224RR en utilisant des composants simples et accessibles.

