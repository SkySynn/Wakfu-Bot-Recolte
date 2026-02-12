# 🤖 Wakfu Harvest Bot

Bot de récolte automatisé développé pour Wakfu.  
Ce projet a pour objectif de démontrer la conception d’un système d’automatisation capable de gérer la récolte complète des métiers, la détection dynamique des ressources ainsi que la gestion des captchas.

---

## 🎯 Objectif du projet

Créer un bot capable de :

- Automatiser la récolte sur tous les métiers
- Détecter les ressources disponibles
- Gérer automatiquement les captchas
- Fonctionner en arrière-plan sans interrompre l’utilisation du PC
- Optimiser les déplacements et les cycles de farm

Ce projet met en avant des compétences en :
- Automatisation
- reverse engineering
- C++/ JNI
- Multithreading
- Optimisation logique

---

## ⚙️ Fonctionnement global

### 1️⃣ Détection des ressources
Le bot analyse l’écran en temps réel afin d’identifier :
- Les ressources récoltables
- Les états interactifs
- Les éléments bloquants
- L'etat du joueur

---

### 2️⃣ Système de récolte
Une fois une ressource détectée :
- Déplacement automatique du personnage
- Interaction
- Vérification de réussite
- plantation si besoin
- Passage à la ressource suivante

Le cycle est optimisé pour minimiser les déplacements inutiles.

---

### 3️⃣ Gestion du captcha
Le bot :
- Détecte l’apparition d’un captcha
- Analyse son contenu
- Résout automatiquement la validation
- Reprend le cycle de récolte

---

### 4️⃣ Mode arrière-plan
Le système peut fonctionner :
- En tâche de fond
- Sans bloquer l’utilisation normale de l’ordinateur
- Avec gestion parallèle des threads

---

## 📊 Métiers supportés

- 🌾 Paysan  
- 🌲 Forestier  
- ⛏️ Mineur  
- 🌿 Herboriste  
- 🐾 Trappeur  

---

## 🔒 Statut du projet

Projet privé — démonstration technique uniquement.  
Le code source n’est pas destiné à être partagé.

---

## 📸 Démonstration

<p align="center">
  <a href="https://youtu.be/PA7KBZm1uJM">
    <img src="https://img.youtube.com/vi/PA7KBZm1uJM/maxresdefault.jpg" width="800">
  </a>
</p>

---

