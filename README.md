# Conception d'un réseau local — Schéma et plan de déploiement

## Contexte

Ce projet porte sur la conception complète d'un réseau local d'entreprise, depuis l'analyse du besoin jusqu'à la planification de son déploiement, en respectant les bonnes pratiques de sécurité recommandées par l'ANSSI.

## Démarche

1. **Schéma physique** : implantation des équipements réseau (switches, points d'accès, câblage), en tenant compte de la capacité et du nombre de ports disponibles sur chaque switch.
2. **Schéma logique** : découpage en VLAN par usage/service, définition des sous-réseaux et des masques associés pour cloisonner les flux.
3. **Plan d'adressage IP** : répartition entre adressage dynamique (DHCP) pour les postes utilisateurs et adressage statique pour les équipements critiques (serveurs, imprimantes réseau, équipements d'infrastructure).
4. **Planification du déploiement** : diagramme de Gantt détaillant les phases du projet, les dépendances entre tâches et les délais associés.

## Bonnes pratiques appliquées

- Segmentation réseau par VLAN pour limiter la propagation d'un incident de sécurité.
- Séparation logique des flux utilisateurs, serveurs et administration.
- Plan d'adressage cohérent, documenté et évolutif.
- Démarche de projet structurée (jalons, dépendances, délais) plutôt qu'un déploiement improvisé.

## Outils utilisés

- **draw.io** : réalisation des schémas physique et logique.
- **Excel** : plan d'adressage IP et diagramme de Gantt.

## Structure du dépôt

```
├── Pic_Thomas_1_DAT_012026.pdf     # Dossier d'Architecture Technique (schémas, adressage, choix techniques)
├── Pic_Thomas_2_Gantt_012026.pdf   # Planning de déploiement (diagramme de Gantt)
└── README.md
```

## Auteur

**Thomas Pic** — Formation Administrateur Systèmes, Réseaux et Cybersécurité (Titre RNCP 40356), OpenClassrooms — Projet 1.
