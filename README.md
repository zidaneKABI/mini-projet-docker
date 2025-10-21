# 🐳 Mini Projet Vagrant + Docker + Registry Privée

## 📘 Description du projet

Ce projet illustre le déploiement d’un environnement complet utilisant **Vagrant**, **VirtualBox** et **Docker**.  
L’objectif est de mettre en place une **infrastructure locale** permettant de déployer :

- Un **serveur Apache (PHP)** servant une page web.  
- Une **API Python** (exposée via Flask) qui fournit une liste d’étudiants à partir d’un fichier `data.json`.  
- Une **registry Docker privée** utilisée pour stocker et gérer les images Docker localement.

La page web consomme l’API Python pour afficher dynamiquement la liste des étudiants.

---

## 🧰 Technologies utilisées

- **Vagrant** pour la création et la configuration de la machine virtuelle.  
- **VirtualBox** comme fournisseur de virtualisation.  
- **Docker & Docker Compose** pour le déploiement des services.  
- **Apache (PHP)** pour le serveur web.  
- **Python / Flask** pour le backend API.  
- **Docker Registry** pour l’hébergement privé des images.
- Une image Mysql est intégrée au projet juste pour teste
- Une image Adminer est intégrée au projet juste pour teste

---

## 📁 Structure du projet

