# Guide d'installation portfolio — React & Vite:

Portfolio web collaboratif développé en duo pour présenter nos projets passés, nos futures réalisations et nos compétences combinées.

---

## Prérequis

Avant de commencer, vérifiez que ces outils sont installés sur votre ordinateur :
* Node.js (version 18 ou supérieure)
* Git (ou Git Bash)

---

## Guide d'installation sur Windows (Étape par étape)

### Étape 1 : Ouvrir le terminal
1. Appuyez sur la touche Windows de votre clavier.
2. Tapez `Git Bash` ou `PowerShell` et ouvrez l'application.

### Étape 2 : Se placer dans le dossier de travail
```bash
cd Documents
```

### Étape 3 : Télécharger le projet depuis GitHub
```bash
git clone [https://github.com/NaivoRZK/andriAnges.git](https://github.com/NaivoRZK/andriAnges.git)
```

### Étape 4 : Accéder au dossier du projet
```bash
cd andriAnges/deux
```

### Étape 5 : Installer les dépendances
Cette commande télécharge toutes les bibliothèques React nécessaires :
```bash
npm install
```

### Étape 6 : Lancer le serveur local
```bash
npm run dev
```

### Étape 7 : Visualiser le site
Ouvrez votre navigateur web (Chrome, Edge ou Firefox) et allez à l'adresse suivante :
http://localhost:5173

---

## Commandes utiles

* `npm run dev` : Démarre le serveur de développement local.
* `npm run build` : Génère les fichiers de production dans le dossier dist.
* `npm run preview` : Prévisualise le build de production en local.
* `Ctrl + C` (dans le terminal) : Arrête le serveur local.

---

## Workflow Git

Important : il faut créer une nouvelle branche `feature/` à chaque nouvelle fonctionnalité et **ne jamais envoyer (push) directement sur la branche `main`**.

1. Mettre à jour son code local avant de commencer :
```bash
git pull origin main
```

2. Créer une nouvelle branche pour chaque nouvelle fonctionnalité :
```bash
git checkout -b feature/nom-de-la-tache
```

3. Enregistrer et envoyer ses modifications (sur sa propre branche) :
```bash
git add .
git commit -m "feat: ajout de la section projets"
git push origin feature/nom-de-la-tache
```