# Z Development

Site one-page de présentation de mon activité de création de sites web professionnels.

**En ligne :** [zdevelopment.fr](https://zdevelopment.fr)

## Stack

- HTML / CSS / JS vanilla (aucun build)
- [Lucide Icons](https://lucide.dev) (CDN)
- Google Fonts : Inter + Playfair Display
- Hébergement : [Vercel](https://vercel.com)

## Structure

```
.
├── index.html          # Page principale
├── assets/             # Images (hero, portfolio)
├── documents/          # Modèles de documents
│   ├── devis.html
│   ├── facture.html
│   └── contrat.html
└── README.md
```

## Sections du site

1. Hero
2. Stats (chiffres clés)
3. Services
4. Portfolio (3 réalisations)
5. Process
6. Pourquoi me choisir
7. Témoignages
8. FAQ
9. Contact (formulaire dépliable + boutons)
10. Footer (mentions légales, CGV, confidentialité)

## Documents pro

Des modèles imprimables / exportables en PDF :

- `documents/devis.html` — Modèle de devis
- `documents/facture.html` — Modèle de facture
- `documents/contrat.html` — Contrat de prestation

## Développement local

Le site étant statique, il suffit de servir le dossier :

```bash
npx serve .
```

Puis ouvrir [http://localhost:3000](http://localhost:3000).

## Déploiement

Push sur la branche `main` → déploiement automatique sur Vercel.
