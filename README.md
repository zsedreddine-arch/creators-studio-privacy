# Créateurs Studio — Politique de confidentialité

Politique de confidentialité de l'application **Créateurs Studio 1.2.0** (Android, compatible iOS), publiée en HTTPS via GitHub Pages.

🌐 **Page publique :** https://zsedreddine-arch.github.io/creators-studio-privacy/

## À propos

Ce dépôt contient exclusivement la page web publique de la politique de confidentialité. Il ne contient **ni code source de l'application, ni clé d'API, ni certificat, ni donnée de paiement**.

L'e-mail de contact de l'éditeur est **ZSedreddine@gmail.com**.

## Fichiers

| Fichier | Rôle |
| --- | --- |
| `index.html` | Page autonome bilingue FR/EN, sans script externe ni traceur — c'est la page servie par GitHub Pages. |
| `.gitignore` | Exclut secrets, clés, certificats, binaires (`.apk`, `.aab`) et tout fichier sensible. |
| `README.md` | Ce fichier. |

## Utilisation dans la Play Console

À coller dans **Play Console → Présence sur le Store → Fiche de l'application → Politique de confidentialité** :

```
https://zsedreddine-arch.github.io/creators-studio-privacy/
```

L'URL est stable, publique et forcée en HTTPS.

## Hébergement

- **GitHub Pages**, branche `main`, racine `/`
- Build automatique à chaque push sur `main`
- Aucun domaine personnalisé ; sous-domaine `github.io` officiel

## Mise à jour de la politique

1. Modifier la source bilingue `PLAY_STORE\politique-confidentialite.md` dans le projet.
2. Synchroniser `PLAY_STORE\politique-confidentialite.html` et `PLAY_STORE\hebergement\index.html`.
3. Remplacer `index.html` dans ce dépôt, puis `git add`, `git commit`, `git push`.
4. Vérifier que https://zsedreddine-arch.github.io/creators-studio-privacy/ répond en **HTTP 200** et affiche la nouvelle version.

La déclaration « Sécurité des données » à recopier dans la Play Console se trouve en fin de `politique-confidentialite.md` ; elle doit rester cohérente avec `fiche-play-store.md`.

## Éditeur

**SEDREDDINE ZAKARIA** — ZSedreddine@gmail.com

L'application Créateurs Studio est distribuée sous licence MIT et licence d'utilisation (EULA) au nom de SEDREDDINE ZAKARIA. Les modalités de traitement des données sont décrites dans la page `index.html`.
