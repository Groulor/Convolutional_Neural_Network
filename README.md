## ⚠️ Confidentialité et Restrictions
### Il est important de noter qu'une grande partie de ce projet est confidentielle en raison des exigences de sécurité et des clauses de confidentialité liées au secteur nucléaire. De ce fait, certaines parties essentielles du code, telles que la gestion de l'interface utilisateur (IHM), la gestion des composants et d'autres fonctionnalités sensibles, ne sont pas publiées sur ce dépôt GitHub.

### Ce dépôt sert principalement de vitrine pour présenter le projet dans son ensemble et en exposer les principes fondamentaux. Il permet ainsi de partager des informations générales et de montrer l’architecture du système, mais ne reflète pas l'intégralité de l'implémentation qui reste réservée dans un cadre sécurisé.

### Merci de comprendre ces restrictions liées à la confidentialité.

---
<p align="center">
  <img src="Logo_EDF.png" alt="EDF ⚡️" width="400">
</p>

# EDF - Convolutional Neural Network (CNN) ⚡️

**One More Time** est un projet développé pour **EDF**, et plus précisément pour le **service prévention des risques**, l’objectif est de développer un système de **contrôle automatique de la présence et du bon fonctionnement des dosimètres opérationnels** des agents entrant en zone radioactive.

Ce projet contribue à renforcer la sécurité des agents travaillant en zone "chaude" et à limiter les coûts cachés engendrés par les oublis ou dysfonctionnements des dosimètres.

---

## 🔧 Principe 
Pensé comme une solution **clé en main**, un boîtier usiné embarque tous les éléments du système dans un format compact et robuste. Ce boîtier intègre l’ensemble des composants essentiels au fonctionnement du système, depuis le micro-ordinateur jusqu’à la caméra et ses capteurs, en passant par les relais, boutons de commande, interfaces USB, éléments de redondance et écran d’affichage sécurisé. L’ensemble est conçu pour garantir la **fiabilité, la maintenabilité et la durabilité** du dispositif, tout en facilitant les interventions techniques grâce à une **architecture optimisée et accessible**.

## 🛡️ Fiabilité et redondance dans le contexte nucléaire 
Dans le secteur nucléaire, la fiabilité et la redondance sont des impératifs absolus pour garantir la sûreté des opérations. Le boîtier a donc été conçu pour répondre à ces exigences :

- Redondance des capteurs critiques afin d'assurer la détection même en cas de défaillance d'un composant.
- Choix de composants éprouvés, pour la fiabilité et la disponibilité à long terme.
- Sécurisation mécanique et électronique des éléments fragiles (caméra, connectiques), pour limiter les déconnexions ou erreurs de lecture.
- Boîtier usiné unique qui protège l'ensemble des composants et simplifie la maintenance.
Cette approche garantit une exploitation sécurisée du dispositif, conforme aux exigences élevées du milieu nucléaire.


Le boîtier est conçu pour un fonctionnement 24 heures sur 24, 7 jours sur 7, sur une très longue période de plusieurs années, sans interruption.
Dans l’environnement exigeant du nucléaire, où la moindre défaillance peut avoir des conséquences critiques, la fiabilité est une priorité absolue.
Pour cela, il embarque de multiples modes de fonctionnement pour garantir la continuité de service : 

- ✅ Mode normal : fonctionnement optimal avec tous les composants opérationnels.
- ⚙️ Mode dégradé : permet au système de continuer à fonctionner partiellement en cas de panne d’un ou plusieurs sous-systèmes critiques.
- 🔄 Mode bypass : désactive temporairement certaines sécurités ou automatismes pour maintenir un fonctionnement minimum du boîtier, dans l’attente d’une intervention de maintenance.
- 🛠️ Mode maintenance : mode spécifique pour faciliter la vérification rapide de l’état du système. Il permet d’avoir un diagnostic clair et immédiat des composants défectueux ou en fin de vie, simplifiant ainsi les opérations de maintenance préventive et corrective

## 🚀 Fonctionnalités
- **Détection automatique** de la présence d'équipement de sécurité de l’agent.
- **Vérification du bon fonctionnement** des équipements.
- Réduction des risques liés à l’oubli ou au défaut d’activation des équipements.
- Diminution des coûts opérationnels liés aux procédures correctives.



## 🧑‍💻 Technologies utilisées
- **Langage** : Python
- **Deep Learning** : PyTorch
- **Réseaux de neurones** : Convolutional Neural Network (CNN)
- **Traitement d’image** : OpenCV
- **Matériel** : Caméra pour la détection visuelle



## 📂 Installation

### 📌 Prérequis
Assurez-vous d'avoir **Python (>= 3.8)** installé.  
Vérifiez la version avec :
```bash
python --version
