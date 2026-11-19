
# Engineering Prompts

<p align="center">
  <img src="https://img.shields.io/badge/Engineering-Prompts-blue?style=for-the-badge" alt="Engineering Prompts">
  <img src="https://img.shields.io/badge/DevOps-DevSecOps-orange?style=for-the-badge" alt="DevOps et DevSecOps">
  <img src="https://img.shields.io/badge/MLOps-Machine%20Learning-purple?style=for-the-badge" alt="MLOps">
</p>

<p align="center">
  <a href="https://github.com/Angloma-federico/engineering-prompts">
    <img src="https://img.shields.io/badge/GitHub-Repository-black?logo=github" alt="Dépôt GitHub">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg" alt="Licence CC BY 4.0">
  </a>
  <a href="CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg" alt="Contributions ouvertes">
  </a>
</p>

<p align="center">
  <a href="https://creativecommons.org/licenses/by/4.0/">
    <img src="https://licensebuttons.net/l/by/4.0/88x31.png" alt="Creative Commons Attribution 4.0 International">
  </a>
</p>

<p align="center">
  <strong>Documentation :</strong>
  <a href="README.md">🇺🇸 🇬🇧 Anglais</a> |
  <a href="FR_README.md">🇫🇷 Français</a>
</p>

Une collection structurée de prompts IA réutilisables dédiés au génie logiciel, à l'administration système, au DevOps, au DevSecOps et au MLOps.

L'objectif de ce dépôt est d'améliorer la qualité, la cohérence, la sécurité et la maintenabilité du travail d'ingénierie assisté par l'intelligence artificielle.

---

## Objectifs

Ce dépôt propose des prompts réutilisables pour aider les ingénieurs à :

- Comprendre les problèmes techniques avant de commencer leur implémentation.
- Concevoir des architectures fiables et faciles à maintenir.
- Écrire du code propre, lisible et sécurisé.
- Automatiser les infrastructures et la livraison logicielle.
- Intégrer la sécurité dans les processus de développement et d'exploitation.
- Construire, déployer et superviser des systèmes de machine learning.
- Produire une documentation technique claire.
- Améliorer les méthodes de dépannage et de résolution de problèmes.

Ces prompts sont conçus pour accompagner l'apprentissage, les travaux pratiques et les processus d'ingénierie professionnels.

## Structure du dépôt

```text
engineering-prompts/
├── LICENSE
├── README.md
├── FR_README.md
├── CONTRIBUTING.md
│
├── shared/
│   ├── engineering-standards.md
│   └── project-context-template.md
│
├── general/
│   ├── code-review.md
│   ├── clean-code.md
│   ├── debugging.md
│   ├── documentation.md
│   └── commit-message.md
│
├── devops/
│   ├── docker.md
│   ├── kubernetes.md
│   ├── terraform.md
│   └── cicd.md
│
├── devsecops/
│   ├── security-audit.md
│   └── vulnerability-analysis.md
│
└── mlops/
    ├── model-training.md
    ├── model-deployment.md
    └── model-monitoring.md
```

## Catégories

| Catégorie | Description |
|---|---|
| `shared/` | Standards d'ingénierie communs et modèles de contexte projet |
| `general/` | Qualité du code, débogage, documentation et revues de code |
| `devops/` | Conteneurs, Kubernetes, infrastructure as code et CI/CD |
| `devsecops/` | Audits de sécurité défensifs et analyse des vulnérabilités |
| `mlops/` | Entraînement, déploiement et supervision des modèles |

## Démarrage

### 1. Cloner le dépôt

```bash
git clone https://github.com/Angloma-federico/engineering-prompts.git
cd engineering-prompts
```

### 2. Choisir un prompt

Accédez au répertoire correspondant à votre besoin.

Par exemple :

```text
devops/docker.md
```

### 3. Fournir le contexte du projet

Pour obtenir des résultats plus pertinents, utilisez le modèle suivant :

```text
shared/project-context-template.md
```

Fournissez les informations utiles concernant :

- Les objectifs du projet.
- La stack technologique.
- L'architecture.
- La structure du dépôt.
- L'état actuel de l'implémentation.
- Les contraintes et exigences.
- Le résultat attendu.

Les informations inconnues ne doivent pas être inventées. Laissez les champs concernés non renseignés.

### 4. Utiliser le prompt

Copiez le prompt sélectionné dans votre assistant IA et fournissez le contexte technique nécessaire.

Adaptez les instructions à votre environnement et à vos exigences réelles.

### 5. Vérifier les résultats

Les propositions générées par une IA doivent être examinées et validées avant leur application.

Vérifiez notamment :

- La justesse technique.
- Les implications en matière de sécurité.
- La compatibilité avec votre environnement.
- Les résultats des tests et des validations.
- L'exactitude de la documentation.

## Principes d'ingénierie

Les prompts reposent sur un ensemble de principes communs :

- **Comprendre avant d'implémenter :** analyser le contexte et le problème avant de proposer une solution.
- **Privilégier la simplicité :** éviter la complexité et les dépendances inutiles.
- **Code propre :** favoriser la lisibilité, la maintenabilité et la cohérence.
- **Sécurité dès la conception :** intégrer les considérations de sécurité tout au long du cycle de vie.
- **Fiabilité :** valider les configurations, les implémentations et les comportements attendus.
- **Dépannage fondé sur des preuves :** distinguer les faits confirmés des hypothèses.
- **Documentation :** expliquer les décisions importantes, les modifications et les limitations.
- **Amélioration continue :** privilégier des solutions pratiques et maintenables.

Pour consulter les exigences communes, référez-vous à [`shared/engineering-standards.md`](shared/engineering-standards.md).

## Documentation

Le dépôt propose une documentation en deux langues :

- [Documentation anglaise](README.md)
- [Documentation française](FR_README.md)

Certains prompts définissent également des exigences documentaires spécifiques aux projets dans lesquels ils sont utilisés.

## Contribution

Les contributions, corrections et améliorations sont les bienvenues.

Avant de proposer une modification, consultez le fichier [`CONTRIBUTING.md`](CONTRIBUTING.md).

Privilégiez les contributions pratiques, réutilisables, techniquement exactes et bien structurées.

## Licence

<p align="center">
  <a href="https://creativecommons.org/licenses/by/4.0/">
    <img src="https://licensebuttons.net/l/by/4.0/88x31.png" alt="CC BY 4.0">
  </a>
</p>

Sauf indication contraire, les prompts, modèles et documents originaux de ce dépôt sont distribués sous la licence **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

Vous êtes libre de partager, modifier et réutiliser ce contenu, y compris à des fins commerciales, sous réserve de respecter les conditions d'attribution :

- Mentionner correctement l'auteur original.
- Fournir un lien vers la licence.
- Indiquer si des modifications ont été effectuées.

Consultez les documents suivants :

- [Fichier LICENSE](LICENSE)
- [Texte juridique officiel CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode)

**Auteur original :** [Angloma-federico](https://github.com/Angloma-federico)

---

<p align="center">
  Maintenu par <a href="https://github.com/Angloma-federico">Angloma-federico</a>
</p>
