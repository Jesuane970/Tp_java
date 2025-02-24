#Tp_java
# Gestion de Voitures en Java

Ce projet est une application Java qui permet de créer et stocker des voitures en demandant à l'utilisateur d'entrer les caractéristiques de chaque véhicule. 

## 📌 Fonctionnalités
- Saisie des informations de 5 voitures via la console.
- Stockage des voitures dans un tableau.
- Utilisation des accesseurs (getters) et mutateurs (setters) pour gérer les données des voitures.
- Affichage des détails de chaque voiture après sa création.

## 🛠️ Structure du projet
Le projet est divisé en deux fichiers principaux :

1. **`Voiture.java`**  
   - Définit la classe `Voiture` avec les attributs suivants :
     - `marque` : La marque de la voiture (ex: Toyota, BMW).
     - `nombrePortes` : Nombre de portes du véhicule.
     - `nombrePneus` : Nombre de pneus.
     - `nombreChaises` : Nombre de sièges.
   - Contient des accesseurs (`getters`) et mutateurs (`setters`) pour modifier et récupérer les valeurs.

2. **`Main_class.java`**  
   - Gère la saisie utilisateur et la création des objets `Voiture`.
   - Stocke les voitures dans un tableau.
   - Affiche un message après chaque création de voiture.

## 🚀 Comment exécuter le projet ?
### 1️⃣ Compilation des fichiers
Ouvrez un terminal et naviguez dans le dossier contenant les fichiers. Ensuite, compilez les fichiers avec :
```sh
javac Voiture.java Main_class.java
