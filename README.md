# Document Technique – Portfolio personnel (Astro)

## 🔧 Contexte et Objectif

Ce projet est un site portfolio personnel développé avec le framework **Astro**, conçu pour présenter mes compétences, projets, et expériences professionnelles de manière moderne et performante.  
L’objectif de ce document est de présenter l’architecture du projet, les choix techniques effectués, et les moyens de consultation (GitHub + Vercel).

---

## 🌐 Accès au projet

- **Repository GitHub** : [https://github.com/Auxabe/Portfolio_template.git]  
- **Site en ligne (déployé via Vercel)** : [lien Vercel ici]

---

## 🛠️ Technologies et outils utilisés

- **Framework principal** : Astro (vX.X)  
- **Langages** : HTML, CSS (TailwindCSS), JavaScript  
- **Déploiement** : Vercel  
- **Gestion de version** : Git + GitHub  
- **Autres outils** : VS Code, Prettier, ESLint

---

## 🧱 Structure du projet

├── public/ # Fichiers statiques (images, favicon, etc.)
├── src/
│ ├── components/ # Composants Astro réutilisables
│ ├── layouts/ # Layouts de pages
│ ├── pages/ # Pages principales du site
│ ├── styles/ # CSS personnalisé
├── astro.config.mjs # Configuration d’Astro
├── package.json # Dépendances et scripts
└── vercel.json # (Optionnel) config Vercel


---

## 🧠 Choix techniques expliqués

- **Astro** : pour le rendu statique rapide, moderne, et SEO-friendly.
- **Tailwind CSS** : design rapide, responsive, propre.
- **Vercel** : déploiement continu automatisé avec GitHub.

---

## 📄 Fonctionnalités principales

- Navigation fluide type SPA
- Liste de projets dynamiques (via JSON ou Markdown)
- Responsive mobile/tablette/desktop
- Animations CSS simples
- SEO optimisé

---

## 🔍 Exécution locale

1. Cloner le projet :
   ```bash
   git clone (https://github.com/Auxabe/Portfolio_template.git)
   cd monportfolio
