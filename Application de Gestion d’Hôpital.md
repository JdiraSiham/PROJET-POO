# 🏥 Application de Gestion d’Hôpital

![Python](https://img.shields.io/badge/Python-3.x-blue)
![SQLite](https://img.shields.io/badge/SQLite-DATABASE-orange)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-green)

---

## 💡 Contexte

Application pour informatiser la gestion d’un petit hôpital :  
- Suivi des patients  
- Gestion des médecins  
- Planification des rendez-vous via une interface graphique simple

---

## 🗄 Base de données

**SQLite** avec 3 tables principales :  

**Patients**  
`id_patient | nom | prenom | CIN | date_naissance | telephone`  

**Médecins**  
`id_medecin | nom | prenom | specialite | telephone`  

**Rendez-vous**  
`id_rdv | id_patient | id_medecin | date_rdv | heure_rdv | motif`  

---

## ⚙ Fonctionnalités

- Ajouter / modifier / supprimer patients et médecins  
- Programmer et gérer les rendez-vous  
- Rechercher patients, médecins ou rendez-vous  
- Affichage du planning d’un médecin  
- Validation automatique : CIN unique, téléphone valide, dates correctes  

---

## 🪟 Interface

- Développée avec **Tkinter**  
- Menu principal avec onglets : **Patients**, **Médecins**, **Rendez-vous**  
- Fenêtres de saisie et tableaux pour afficher les listes  
- Recherche flexible avec filtres multiples  

---

## 🚀 Installation

1. Installer **Python 3.x**  
2. Tkinter est inclus dans Python standard, SQLite3 est intégré  
3. Lancer le script :  

```bash
python main.py
