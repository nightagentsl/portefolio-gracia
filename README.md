# Portfolio de Gracia Nambea

Je suis **Gracia Nambea**, étudiante en Bachelor 3 Cybersécurité et réserviste opérationnelle dans l'Armée de Terre.

J'ai créé ce portfolio pour présenter mon profil, mes projets en cybersécurité, mon parcours et mes compétences autour de trois axes :

- SOC et supervision de sécurité
- Gouvernance, Risques et Conformité (GRC)
- Sécurité opérationnelle

## Aperçu

J'ai conçu ce portfolio comme une page web statique responsive, pensée pour une consultation sur ordinateur, tablette et téléphone.

J'y présente notamment :

- mon profil et ma recherche d'alternance ;
- mes projets PSSI GlobalTech, Booking App et TP SOC ;
- mon parcours académique et professionnel ;
- mes compétences techniques et de gouvernance ;
- mes liens de contact, GitHub et LinkedIn.

## Technologies

- HTML5
- CSS3
- JavaScript vanilla
- GitHub Actions
- GitHub Pages

## Lancer le projet en local

Mon projet ne nécessite aucune installation de dépendances.

### Avec Visual Studio Code

1. Installer l'extension **Live Server**.
2. Ouvrir `index.html`.
3. Cliquer sur **Go Live** dans la barre d'état de VS Code.

### Avec un serveur HTTP local

Depuis le dossier du projet, j'utilise un serveur HTTP disponible sur ma machine, puis j'ouvre l'adresse affichée dans le navigateur.

Par exemple, avec Python :

```bash
python -m http.server 5500
```

Le site sera disponible à l'adresse `http://localhost:5500`.

## Déploiement

J'utilise le workflow situé dans `.github/workflows/deploy-pages.yml` pour déployer automatiquement le contenu du dépôt sur GitHub Pages à chaque push sur la branche `main`.

Une fois GitHub Pages activé dans les paramètres du dépôt, le site est accessible à l'adresse :

[https://nightagentsl.github.io/portefolio-gracia/](https://nightagentsl.github.io/portefolio-gracia/)

Pour activer Pages manuellement, je suis ces étapes :

1. Ouvrir **Settings** dans le dépôt GitHub.
2. Aller dans **Pages**.
3. Choisir **GitHub Actions** comme source de déploiement.
4. Vérifier le résultat du workflow dans l'onglet **Actions**.

## Structure

```text
.
├── index.html                         # Structure et contenu du portfolio
├── styles.css                         # Mise en page et responsive design
├── script.js                          # Menu mobile et année du footer
├── README.md                          # Documentation du projet
└── .github/workflows/deploy-pages.yml # Déploiement GitHub Pages
```

## Contact

- Email : [gnambea.securite@gmail.com](mailto:gnambea.securite@gmail.com)
- GitHub : [github.com/nightagentsl](https://github.com/nightagentsl)
- LinkedIn : [gracia-nambea-tech](https://www.linkedin.com/in/gracia-nambea-tech)

## Auteur

**Gracia Nambea**  
Étudiante en cybersécurité — SOC / GRC & sécurité opérationnelle
