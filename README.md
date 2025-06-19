# 🛰️ Star Wars Rebels Alliance Search System

Bienvenue dans l'Alliance Rebelle, jeune Padawan !  
Nous avons besoin de personnes motivées pour déjouer les plans de l'Empire.

Les espions du seigneur Vador sont partout...  
Il nous faut donc un moyen de contrecarrer leurs actions.

🎯 **Votre mission** (si vous l'acceptez) : créer une interface permettant de rechercher dans la base de données impériale.  
L’un de nos espions a donné sa vie pour que nous puissions y accéder via cette API : [SWAPI](https://swapi.info/)

---

## 🗂️ Modalités

- **Langages / frameworks obligatoires** :
  - Backend : **Node.js + TypeScript**
  - Frontend : **ReactJS + TypeScript**
  - Appels réseau avec : **React Query**
- **Livrables attendus** :
  - Un repo GitHub contenant :
    - `frontend/` et `backend/` clairement séparés
    - Un fichier `README.md` avec :
      - Instructions pour installer et lancer le projet
      - Explication des choix techniques
      - Améliorations possibles
  - Bonus : déploiement en ligne (Vercel, Netlify, Render, Railway…)

---

## 🧱 Étape 1 — Backend (Obligatoire)

Créer une API backend en Node.js avec **TypeScript** permettant d’interroger les données de la SWAPI.

### Fonctionnalités obligatoires :

- Implémenter un **endpoint de recherche unique** :
  - Il interroge **toutes les catégories** de SWAPI (`people`, `starships`, `planets`, etc.)
  - Le backend **agrège et filtre** les résultats
  - L’API doit être conçue pour être **extensible** (architecture claire : services / routes / contrôleurs)

### Bonnes pratiques à respecter :

- Utiliser `async/await` et bien gérer les erreurs (try/catch)
- Organisation modulaire et typée (`types/`, `interfaces/`, `services/`, etc.)
- Renvoyer des codes HTTP clairs (`200`, `400`, `500`…)

### Bonus (Optionnels mais fortement valorisés) :

- 🔐 Mise en place d’un système d’authentification (basique) :
  - Identifiants fixes :
    - username : `Luke`
    - password : `DadSucks`
  - Création d’un middleware pour protéger l’endpoint de recherche
- 🔄 Utilisation du framework [Hapi.js](https://hapi.dev/)

---

## 🧑‍🚀 Étape 2 — Frontend (Obligatoire)

Créer une interface React **avec TypeScript** permettant d’interagir avec votre backend.

### Fonctionnalités obligatoires :

- Champ de recherche permettant d’interroger le backend
- Appels réseau gérés **avec `react-query`**
- Affichage en **liste des résultats** avec leurs noms
- **Fiche détaillée** sur clic d’un résultat, affichant les infos principales

### Bonnes pratiques à respecter :

- Structure React modulaire (composants, hooks, services API)
- État de chargement (`loading`), vide (`no results`) et erreurs réseau
- Utilisation de `useState`, `useEffect`, `useQuery` de React Query

---

## ✨ Bonus (Optionnels mais fortement appréciés)

| Thème | Description |
|-------|-------------|
| 🎨 Fiches détaillées | Affichage différent selon le type de donnée (personnage, vaisseau...) |
| 🧭 Router React | Navigation entre pages de fiche ou résultat de recherche (`react-router-dom`) |
| 🧪 Tests unitaires | 1 ou 2 tests simples (ex. fonction de parsing) avec Jest ou équivalent |
| 🧼 CSS modules ou Tailwind | Structuration propre des styles CSS |
| 📦 Redux ou gestion globale de l'état | Si justifié dans l'architecture |
| 🔁 Debounce sur le champ de recherche | Pour limiter les appels réseau |
| 🔍 Filtres par type de résultat | Séparer par type : personnages, vaisseaux, planètes... |
| 🔐 Authentification frontend | Ajout de token à l’appel d’API, redirection si non connecté |
| 📱 Responsive design | Design qui s’adapte au moins aux tailles classiques (mobile, tablette) |
| 🚀 Déploiement en ligne | Mettre le frontend sur Vercel / Netlify et backend sur Render / Railway… |
| 📋 **React Hook Form** | Gestion propre du champ de recherche via [React Hook Form](https://react-hook-form.com/) |

---

## ⚠️ Restrictions

🚫 **L'utilisation de `swapi-node` est interdite.**  
L'application est surveillée par l’Empire. Utilisez uniquement vos propres appels HTTP (`fetch`, `axios`, `react-query`, etc.).

---

## 📤 Soumission

Merci de nous transmettre :
- Le lien de votre dépôt GitHub
- Optionnel : un lien vers votre démo en ligne

---

## 🖖 Que la force soit avec vous !

![May the force be with you](https://media.giphy.com/media/JDnaQ8qn0Myuk/200.gif)
