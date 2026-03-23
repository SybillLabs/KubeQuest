# 🚀 KubeQuest : De la conteneurisation à l'orchestration

![Statut](https://img.shields.io/badge/Statut-En%20perp%C3%A9tuelle%20%C3%A9volution-purple?style=flat-square&logo=github)
![FR](https://img.shields.io/badge/Langue-Fran%C3%A7ais-blue?style=flat-square&logo=github)

![DOCKER](https://img.shields.io/badge/Docker-Conteneurisation-pink?style=flat-square&logo=docker)
![KUBERNETES](https://img.shields.io/badge/Kubernetes-Orchestration-pink?style=flat-square&logo=kubernetes)

## 📝 Contexte
**KubeQuest** est un laboratoire *évolutif* consacré à l'apprentissage de **Docker** et **Kubernetes**.  
Il rassemble une série de quêtes, chacune prenant la forme d'un mini-lab conçu pour découvrir, comprendre et pratiquer les bases de la conteneurisation et de l'orchestration.

L'objectif est simple : progresser pas à pas dans les technologies clés de la *culture DevOps*, tout en documentant chaque étape pour créer une base de connaissances claire, structurée et facile à réutiliser.  
**KubeQuest** grandira au fil de mon apprentissage, du niveau débutant jusqu’aux pratiques plus avancées.

## 📂 Organisation du dépôt
Le dépôt est organisé de manière à faciliter la navigation et la compréhension :
- **README.md** : Présentation générale du laboratoire, de ses objectifs et de son fonctionnement.
- **Quest/** : Dossier regroupant l'ensemble des quêtes, chacune dans un fichier Markdown dédié (ex : `quest01.md`, `quest02.md`, etc.)
- **Resources/** : Dossier regroupant les ressources utiles pour approfondir les notions abordées(liens, tutoriels, outils, etc.).

## 📌 Quêtes
Cette section regroupe les différentes quêtes.

[![Quête 1](https://img.shields.io/badge/Qu%C3%AAte%201-Comprendre%20et%20utiliser%20Docker%20%26%20Kubernetes-blue?style=social&logo=github)](/Quest/quest01.md)
- Découvrir les bases de Docker et Kubernetes et apprendre à manipuler les premiers conteneurs et pods.
- Explorer la création d’images Docker et comprendre comment déployer une application simple dans un cluster local.
- Mettre en place les premiers manifestes Kubernetes pour saisir la logique des Deployments et des Services.

## ⚡ Prérequis
Pour utiliser ce laboratoire, il est recommandé de :
- Savoir utiliser un *terminal de commande*.
- Avoir *Docker Desktop* installé pour la conteneurisation.
- Disposer d'un *cluster Kubernetes local* (comme Minikube ou Kind) pour l'orchestration.
- Installer *kubectl* pour interagir avec le cluster Kubernetes.
- Comprendre quelques notions simples (une image, un conteneur, un Pod, un fichier YAML).

## ⚠️ Avertissements
Ce laboratoire est conçu pour l’apprentissage et l’expérimentation.  
Les commandes Docker et Kubernetes utilisées dans les quêtes peuvent créer des conteneurs, consommer des ressources ou ouvrir des ports sur votre machine.  
Il est recommandé de suivre les exercices dans un environnement de test et de vérifier régulièrement les conteneurs et clusters actifs.

---

[![Profil](https://img.shields.io/badge/Back%20to-SybillLabs%20(Profil)-blue?style=social&logo=github)](https://github.com/SybillLabs)