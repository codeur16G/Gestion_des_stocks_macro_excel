# Application de Gestion des Stocks avec Excel

## Description

Cette application Excel de gestion des stocks est conçue pour faciliter le suivi des entrées et sorties de marchandises, gérer les niveaux de stock, et fournir un inventaire clair et détaillé. Les opérations sont divisées en plusieurs feuilles pour une organisation optimale et une navigation simple. 

## Structure de l'Application

L'application est organisée en quatre feuilles principales : 

1. **Opérations** : Permet de gérer chaque opération d'entrée ou de sortie en enregistrant les informations dans les feuilles correspondantes.
2. **Marchandises** : Sert de point de départ pour l'ajout de nouvelles marchandises dans le stock. 
3. **Entrées** et **Sorties** : Enregistre respectivement toutes les opérations d'entrées et de sorties de marchandises.
4. **Inventaire** : Fournit un état récapitulatif des marchandises en stock, avec des informations sur la quantité en stock, la valeur totale et un message d'avertissement si le stock est bas.

## Fonctionnalités

### 1. Feuille **Opérations**
   - Permet d'**initialiser l'application** en ajoutant les informations de toutes les marchandises de base déjà présentes dans le stock.
   - Saisie initiale des détails des marchandises, tels que la référence, le prix unitaire, la date et la quantité.
   - La catégorie, la désignation (nom) et l'unité sont automatiquement chargées depuis la feuille Marchandises après la saisie de la référence.

### 2. Feuille **Marchandises**
   - Permet d'ajouter les informations pour chaque opération d'**entrée** ou de **sortie** de marchandises.
   - Si une marchandise est nouvelle (non présente dans le stock), ses informations de base doivent être saisies ici pour être enregistrées dans l'inventaire.
   - Les données sont automatiquement enregistrées dans la feuille **Entrées** ou **Sorties** selon l'opération sélectionnée.

### 3. Feuilles **Entrées** et **Sorties**
   - Enregistre toutes les opérations d'entrées et de sorties pour un suivi détaillé.
   - Chaque opération est horodatée et associée à une description spécifique de la marchandise, de sa quantité, et de son coût ou prix de vente.

### 4. Feuille **Inventaire**
   - Affiche un **résumé en temps réel** de toutes les marchandises en stock.
   - Pour chaque marchandise, la feuille fournit des informations sur :
     - Quantité totale d'entrées
     - Quantité totale de sorties
     - **Stock final** restant
     - **Valeur totale** du stock
     - Message d’**alerte** sur l’état du stock si les quantités sont faibles, pour faciliter le réapprovisionnement.

## Utilisation

1. **Initialisation** : Rendez-vous sur la feuille **Marchandises** pour ajouter toutes les marchandises qui doivent être présentes dans le stock.
2. **Opérations de Stock** :
   - Pour chaque entrée ou sorties de marchandises, utilisez la feuille **Opérations** pour saisir les informations de l'opération.
   - Sélectionnez le type d'opération (Entrée ou Sortie), et les données seront automatiquement enregistrées dans la feuille appropriée.
3. **Suivi de l'Inventaire** : La feuille **Inventaire** affiche le statut des stocks en temps réel avec les mises à jour de chaque opération. Un message d'avertissement est visible si une marchandise a un stock bas.

## Aperçu de l'Application

> Ajoute ici des captures d'écran pour montrer chaque feuille (Opérations, Marchandises, Inventaire) et les principales informations affichées.

## Technologies Utilisées

- **Microsoft Excel** pour la gestion des données, l'automatisation de calculs et la création de tableaux et graphiques.
- **Formules Excel** avancées pour les calculs automatiques des stocks, valeurs et alertes.
- **Macros Excel** pour automatiser certaines actions, telles que l'enregistrement des opérations dans les feuilles correspondantes.

## Installation et Configuration

1. Téléchargez le fichier Excel depuis ce dépôt.
2. Ouvrez le fichier dans Microsoft Excel.
3. Suivez les étapes d'initialisation dans la feuille **Marchandises** pour commencer.

## Améliorations Futures

- **Ajout d'un tableau de bord** pour une vue d'ensemble plus graphique de l'état des stocks.
- **Automatisation avancée avec VBA** pour des actions comme le réapprovisionnement automatique ou des notifications d'alerte.
