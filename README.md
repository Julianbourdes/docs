# Teamova Documentation

Documentation officielle de Teamova, la plateforme SaaS innovante pour le management humain et la collaboration d'équipe.

## 🎯 À propos

Ce dépôt contient la documentation utilisateur complète de Teamova, construite avec [Mintlify](https://mintlify.com). La documentation est disponible en français et en anglais.

Teamova propose une suite d'outils collaboratifs pour transformer le management d'équipe : Planning Poker, One-to-One, Squad Health Check et bien plus encore.

**Accès à la documentation** : [docs.teamova.net](https://docs.teamova.net)

## 🌍 Langues supportées

- 🇫🇷 Français (`/fr`)
- 🇬🇧 English (`/en`)

## 📚 Contenu

- **Introduction** : Découvrir Teamova et ses fonctionnalités principales
- **Fonctionnalités** : Guide détaillé des fonctionnalités disponibles
- **Changelog** : Historique des mises à jour et nouvelles fonctionnalités
- **Référence API** : Documentation de l'API Teamova (à venir)

## 🛠️ Développement local

### Prérequis

Installer le [CLI Mintlify](https://www.npmjs.com/package/mint) :

```bash
npm i -g mint
```

### Lancer le serveur de développement

À la racine du projet, où se trouve `docs.json` :

```bash
mint dev
```

La documentation sera accessible sur `http://localhost:3000`.

### Mise à jour du CLI

Si le serveur ne démarre pas correctement :

```bash
mint update
```

## 📝 Structure du projet

```
docs/
├── docs.json           # Configuration Mintlify (navigation, thème, etc.)
├── en/                 # Documentation anglaise
│   ├── introduction.mdx
│   ├── features.mdx
│   ├── changelog.mdx
│   └── api-reference/
├── fr/                 # Documentation française
│   ├── introduction.mdx
│   ├── features.mdx
│   ├── changelog.mdx
│   └── api-reference/
└── logo/               # Logos Teamova (light/dark)
```

## 🚀 Déploiement

Les changements poussés sur la branche `main` sont automatiquement déployés en production via l'application GitHub de Mintlify.

Pour configurer le déploiement automatique, installer l'app depuis le [dashboard Mintlify](https://dashboard.mintlify.com/settings/organization/github-app).

## 🔗 Liens utiles

- **Site web** : [teamova.net](https://teamova.net)
- **Application** : [app.teamova.net](https://app.teamova.net)
- **Page de statut** : [status.teamova.net](https://status.teamova.net)
- **Documentation Mintlify** : [mintlify.com/docs](https://mintlify.com/docs)

## 📧 Support

Des questions ? Contactez-nous à [contact@teamova.net](mailto:contact@teamova.net)
