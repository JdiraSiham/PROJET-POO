# Application de Gestion d’Hôpital


## Contexte

Application pour informatiser la gestion d’un petit hôpital :  
- Suivi des patients  
- Gestion des médecins  
- Planification des rendez-vous via une interface graphique simple

---

## Base de données

**SQLite** avec 3 tables principales :  

**Patients**  
`id_patient | nom | prenom | CIN | date_naissance | telephone`  

**Médecins**  
`id_medecin | nom | prenom | specialite | telephone`  

**Rendez-vous**  
`id_rdv | id_patient | id_medecin | date_rdv | heure_rdv | motif`  

---

## Fonctionnalités

- Ajouter / modifier / supprimer patients et médecins  
- Programmer et gérer les rendez-vous  
- Rechercher patients, médecins ou rendez-vous  
- Affichage du planning d’un médecin  
- Validation automatique : CIN unique, téléphone valide, dates correctes  

---

## Interface

- Développée avec **Tkinter**  
- Menu principal avec onglets : **Patients**, **Médecins**, **Rendez-vous**  
- Fenêtres de saisie et tableaux pour afficher les listes  
- Recherche flexible avec filtres multiples  

---

# Présentation du Projet

Voici une démonstration du projet :  
[La vidéo de démonstration de l'interface graphique](https://drive.google.com/file/d/1Tb53-RvXZUuhe4kd59-aglkWiEveEmLm/view?usp=sharing)
