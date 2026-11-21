# Plateforme-E-Sport-Jeu-de-Nim
Application web pair-à-pair de Jeu de Nim en temps réel dans le navigateur (salons, tournois, replays, statistiques), réalisée dans le cadre du cours **ISI3195 – Technologies et Programmation Web 1** (Niveau 3, ISI), Institut Saint Jean, Yaoundé.

## Technologies

- HTML5, CSS3, JavaScript natif en modules ES (sans framework)
- PeerJS pour la connexion pair-à-pair, basée sur WebRTC
- [Framework CSS et version, si utilisé]
- Vite comme outil de développement
- Node.js pour les scripts et les tests

## Installation

```bash
git clone git@github.com:Jonnorich/Plateforme-E-Sport-Jeu-de-Nim.git
cd Plateforme-E-Sport-Jeu-de-Nim
npm install
```

## Lancer le projet

```bash
npx vite ou `npm run dev`
```
puis ouvrir l'adresse affichée dans le terminal (par défaut `http://localhost:5173`).

## Lancer les tests

```bash
npm test
```

## Structure

```
├── css/
├── js/
│   ├── core/       Règles du jeu
│   ├── network/    Connexion P2P
│   ├── features/   Tournoi, rejeu, statistiques
│   ├── ui/         Interface
│   └── utils/      Outils
├── tests/
├── index.html
└── package.json
```

## Auteurs(NOM, Matricule, Classe/niveau,  Profil Github)

- MENGUE NGA MBIDA Alain Joseph, matricule 2627i917, INGE 3 ISI
GitHub : [github.com/Jonnorich](https://github.com/Jonnorich)

- 

- 

- 

- 

## Licence

Projet académique, Institut Saint Jean Ingénieur.