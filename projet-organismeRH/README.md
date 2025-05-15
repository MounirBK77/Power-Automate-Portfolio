# 📁 Projet 2 – Validation des Virements Organismes (Impôts, URSSAF…)

Ce projet Power Automate automatise le processus de validation des virements vers des organismes externes tels que l’URSSAF, la DGFiP, Sécu etc.

---

## 🎯 Objectif du projet

- Éviter les oublis ou erreurs dans le traitement des virements
- Accélérer la validation et centraliser la traçabilité
- Optimiser le stockage des demandes dans SharePoint

---

## ⚙️ Fonctionnement du flux

1. Un utilisateur complète un **formulaire de demande** de virement
2. Les données sont enregistrées dans une **liste SharePoint**
3. Un **flux Power Automate** est déclenché automatiquement
4. Une **colonne de validation** est mise à jour selon la décision du service comptable
5. Un **email de confirmation** est envoyé

> 💡 Aucune logique conditionnelle liée aux montants n’est utilisée : la validation est unique pour toutes les demandes.

---

## 🧩 Outils utilisés

- Microsoft Power Automate
- Microsoft Forms
- SharePoint Online
- Outlook (notification email)

---

## 📸 Captures d’écran du flux

Voici les étapes illustrées du flux :

![Flow 1](Flow%201.png)  
![Flow 2](Flow%202.png)  
![Flow 3](Flow%203.png)  
![Flow 4](Flow%204.png)  
![Flow 5](Flow%205.png)  
![Flow 6](Flow%206.png)

---

## ✅ Résultats obtenus

- ⏱ **Gain de temps** dans le traitement administratif
- 🗂 **Stockage centralisé** des virements dans SharePoint
- 🔎 **Traçabilité complète** grâce à l’historique de validation

---

🔁 [Retour au Portfolio principal](../README.md)

