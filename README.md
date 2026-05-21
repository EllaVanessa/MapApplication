# Application de Localisation avec OpenStreetMap

## Objectif
Développer une application Android permettant :
- de récupérer la position GPS
- d’enregistrer les coordonnées dans une base de données MySQL
- d’afficher les positions sur une carte OpenStreetMap

---

# Technologies utilisées
- Android Studio
- Java
- OpenStreetMap / OSMDroid
- PHP
- MySQL
- XAMPP
- Volley

---

# Fonctionnalités
- Récupération de la position GPS
- Envoi des coordonnées vers un serveur PHP
- Stockage dans MySQL
- Affichage des positions sur la carte
- Gestion des permissions Android

---

# Structure du Projet

## Frontend Android
- MainActivity.java
- GoogleMapActivity.java

## Backend PHP
- createPosition.php
- getPosition.php

## Base de données
- Base : `map_project`
- Table : `positions`

---

# Captures d’écran

## 1. Permission téléphone
<img width="322" height="701" alt="Capture d&#39;écran 2026-05-21 025137" src="https://github.com/user-attachments/assets/84a24585-6cc1-4bc5-ab23-f73785c0d3bc" />



## 2. Permission localisation
<img width="311" height="694" alt="Capture d&#39;écran 2026-05-21 025127" src="https://github.com/user-attachments/assets/5f9c8053-06b8-4bce-bfe5-970e16867c24" />

## 3. Interface principale
<img width="332" height="697" alt="Capture d&#39;écran 2026-05-21 025144" src="https://github.com/user-attachments/assets/cc6c3542-da27-43f5-a77d-e668c78667cc" />


## 4. Affichage de la carte
<img width="327" height="695" alt="Capture d&#39;écran 2026-05-21 025219" src="https://github.com/user-attachments/assets/66a6cb2c-f28f-43fa-a849-64124eb17771" />


---

# Résultat
L’application récupère correctement la position GPS de l’utilisateur, enregistre les coordonnées dans la base de données et affiche les positions sur la carte.

---

# Auteur
Ella Vanessa MUGISHA
