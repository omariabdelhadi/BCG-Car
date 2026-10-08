# Location de Voitures

Application web de gestion de location de véhicules : catalogue, réservation en ligne, suivi des disponibilités et gestion des clients.

## Objectif

- consulter le catalogue des véhicules ;
- réserver un véhicule en ligne ;
- suivre les disponibilités des véhicules ;
- gérer les clients.

## Technologies

| Domaine | Technologies |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js, JavaScript |
| Base de données | MySQL |

## Structure du projet

```
location-voitures/
├── backend/    API Node.js (point d'entrée : server.js)
└── frontend/   Interface web HTML / CSS / JavaScript
```

## Aperçu

### Catalogue des véhicules

<img width="997" height="603" alt="image" src="https://github.com/user-attachments/assets/d886831f-0e19-4c44-96a8-1cabfccbaf96" />


### Réservation d'un véhicule

<img width="945" height="507" alt="image" src="https://github.com/user-attachments/assets/d99ec728-baa8-4d37-a937-da869ec3987e" />


### dashboard - administrateur

<img width="945" height="450" alt="image" src="https://github.com/user-attachments/assets/8573646b-0d09-4c88-bea7-76f9ce8eb357" />


### Ajouter une voiture

<img width="945" height="470" alt="image" src="https://github.com/user-attachments/assets/35034468-3859-46c5-b9a0-4bbb70657353" />

## Lancer le projet

### Prérequis

- Node.js et npm
- MySQL installé et démarré
- VS Code avec l'extension **Live Server**

### 1. Récupérer le projet

```bash
git clone https://github.com/omariabdelhadi/location-voitures.git
cd location-voitures
```

### 2. Démarrer le backend

Renseigne ton utilisateur et ton mot de passe MySQL dans le fichier de connexion à la base du backend. La base et les tables sont créées directement par le code au démarrage, il n'y a aucun script SQL à lancer à la main.

```bash
cd backend
npm install
node server.js
```

### 3. Démarrer le frontend

Dans VS Code, ouvre le dossier `frontend`, fais un clic droit sur `index.html`, puis choisis **Open with Live Server**.
