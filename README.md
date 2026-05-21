# Il Est Midi — Le déjeuner réinventé

Plateforme de mise en relation entre foodtrucks et entreprises.

## Pages publiées

- `/` — page d'accueil (choix entreprise / foodtruck)
- `/entreprise` — landing offre entreprise
- `/foodtruck` — landing offre foodtruck

## Structure

```
il-est-midi/
├── index.html                                  # Page d'accueil (choix)
├── vercel.json                                 # Config Vercel (clean URLs + rewrites)
├── assets/
│   └── images/                                 # Logos
├── design/
│   └── brand.json                              # Charte graphique
└── pages/
    ├── landing-foodtruck.html                  # Landing foodtruck
    └── landing-entreprise.optimized.html       # Landing entreprise
```

## Développement local

Le site est 100% statique. Pour le tester en local, ouvrir `index.html` directement dans un navigateur, ou servir le dossier :

```bash
python3 -m http.server 8000
# puis http://localhost:8000
```

## Déploiement

Déploiement automatique sur Vercel à chaque push sur `main`.

## Contact

hello@ilestmidi.fr
