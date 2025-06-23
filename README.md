# AFN Determination Tool 🔁

Un outil Java permettant de convertir un automate fini non déterministe (AFN) en automate fini déterministe (AFD), avec une interface graphique développée en Swing.

---

## 📘 Description

Ce projet a été réalisé dans le cadre d’un cours sur les techniques de compilation à l’INSEA. Il implémente le processus théorique de déterminisation, transformant un AFN en un AFD équivalent tout en conservant le langage accepté.

---

## 🎯 Fonctionnalités

- Définition personnalisée des états, transitions, états initiaux et finaux  
- Interface visuelle interactive pour la création et la gestion des automates  
- Support des transitions non déterministes  
- Algorithme automatique de déterminisation par construction des sous-ensembles  
- Vérification de l’acceptation des chaînes d’entrée  

---

## 🧠 Théorie sous-jacente

L’outil s’appuie sur la théorie formelle des automates, utilisant la méthode de construction d’états composites pour la déterminisation des AFN :  
- Génération des états composés  
- Union des ensembles de transitions  
- Identification des états finaux  

---

## 🛠️ Technologies

- Java (Core et Swing)  
- Programmation orientée objet (POO)  
- Structures de données personnalisées (HashMap, HashSet)  

---

## 📷 Captures d’écran

![Interface principale](acceuil.png)  
![Configuration des transitions](transitions.png)  

---

## 📚 Contexte académique

- Développé par : Zakaria Douih & Abderrahmane Nait-El-Haj  
- Encadrant : M. Adil Kabbaj  
- Institut : INSEA – Département Génie Logiciel et Data  
- Date : Janvier 2025  

---

## 🚀 Exécution

Pour compiler et lancer l’application, utilisez les commandes suivantes dans votre terminal :  

```bash
javac Automate.java
java Main
