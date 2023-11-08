# UserBenchmark.com UML

## Table des matières
1. [Introduction](#1-introduction)
2. [Diagramme de cas d'utilisation](#2-diagramme-de-cas-dutilisation)
3. [Diagramme de classe](#3-diagramme-de-classe)
4. [Diagramme de séquence](#4-diagramme-de-séquence)
5. [Contribution](#contribution)

---

## 1. Introduction
**UserBenchmark.com** est une plateforme en ligne qui permet aux utilisateurs de comparer les performances de divers composants informatiques, tels que les processeurs, les cartes graphiques, et bien d'autres. Ce document décrit les spécifications du projet en utilisant des diagrammes UML pour représenter les cas d'utilisation, les classes et les séquences.

---

## 2. Diagramme de cas d'utilisation

#### Acteurs
- **Utilisateur non inscrit** : Un visiteur du site n'ayant pas créé de compte.
- **Utilisateur inscrit** : Un utilisateur disposant d'un compte sur le site.
- **Administrateur** : Responsable de la gestion du site.

#### Cas d'utilisation principaux
- **S'inscrire** : Les utilisateurs non inscrits peuvent créer un compte.
- **Se connecter** : Les utilisateurs inscrits peuvent accéder à leur compte.
- **Rechercher des composants** : Les utilisateurs peuvent rechercher des composants.
- **Comparer des composants** : Les utilisateurs peuvent comparer les performances de plusieurs composants.
- **Soumettre des benchmarks** : Les utilisateurs peuvent ajouter des données de benchmark.
- **Afficher des statistiques** : Les utilisateurs peuvent accéder aux statistiques globales.
- **Gérer les comptes (Administrateur)** : L'administrateur peut gérer les comptes des utilisateurs et les données soumises.
![Alt Text]("C:\Users\DIAE\Desktop\uml\benchmark.jpg")

---

## 3. Diagramme de classe
### Diagramme de classe

#### Classes principales
- **Utilisateur** : Représente les utilisateurs inscrits sur le site.
- **Composant** : Représente les composants informatiques, tels que les processeurs et les cartes graphiques.
- **Benchmark** : Stocke les données de performance soumises par les utilisateurs.
- **Statistiques** : Génère des statistiques à partir des benchmarks.
- **Commentaire** : Permet aux utilisateurs de laisser des commentaires sur les composants.
- **Administrateur** : Gère les comptes des utilisateurs et le contenu du site.

---

## 4. Diagramme de séquence
### Diagramme de séquence

#### Exemple de séquence : Recherche de composants
1. L'utilisateur saisit des critères de recherche.
2. Le système traite la demande et affiche les résultats.

---

## Contribution
Contributeurs à ce projet :
- [Diae-Eddine Jamal](#)
- [Ali el jouali](#)
- [Abdelghani Esenhaji](#)
