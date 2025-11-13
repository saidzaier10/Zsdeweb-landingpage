# ZsDevWeb v3 - Professional Quote Generator

🚀 **Landing page avec démo vidéo pour le générateur de devis professionnel**

## 📋 Description

ZsDevWeb v3 est une application web complète de developpeur freelance pour la génération automatique de devis professionnels avec signatures électroniques, génération de PDF et analytics en temps réel.

## 🎯 Fonctionnalités principales

- **Générateur de devis 8 étapes** avec calcul de prix en temps réel
- **Signatures électroniques** sécurisées avec tokens uniques
- **Génération automatique de PDF** avec WeasyPrint
- **Dashboard administrateur** avec Chart.js
- **Sécurité entreprise** (JWT, rate limiting, prévention d'attaques)
- **Haute performance** avec cache Redis et optimisation des requêtes

## 🛠 Stack technique

### Backend
- **Django 5.1** + Django REST Framework
- **PostgreSQL 17** - Base de données principale
- **Redis 7** - Cache et sessions
- **Gunicorn** - Serveur WSGI

### Frontend
- **Vue.js 3** - Framework frontend
- **Pinia** - Gestion d'état
- **Tailwind CSS** - Styling
- **Chart.js** - Visualisations

### Infrastructure
- **Docker** - Containers
- **Nginx** - Reverse proxy
- **GitHub Actions** - CI/CD

## 🚀 Déploiement

Le site est déployé automatiquement via GitHub Pages à chaque push sur la branche `main`.

### URL de production
https://saidzaier10.github.io/Zsdevweb-v3

### Déploiement manuel
```bash
# Cloner le repository
git clone https://github.com/saidzaier10/Zsdevweb-v3.git
cd Zsdevweb-v3

# Le site est statique, ouvrir index.html dans un navigateur