# [RollSheet](https://ax4m3.github.io/RollSheet/)

Un outil web statique, léger et (presque) complet pour générer, prévisualiser et exporter des fiches de personnage pour différents systèmes de jeu de rôle (Donjons & Dragons, Warhammer, etc.).

Le projet est entièrement codé en HTML, CSS et JavaScript pur, et s'exécute directement dans le navigateur sans aucune installation nécessaire.

![License MIT](https://img.shields.io/github/license/Ax4M3/RollSheet?style=flat-square&color=green)
![GitHub Issues](https://img.shields.io/github/issues/Ax4M3/RollSheet?style=flat-square)

### Pour me retrouver et me soutenir
[![Mastodon](https://img.shields.io/badge/Mastodon-Profil-563acc?style=flat-square&logo=mastodon)](https://piaille.fr/@Axm)
[![Liberapay](https://img.shields.io/badge/Liberapay-Faire_un_don-f6c915?style=flat-square&logo=liberapay&logoColor=black)](https://liberapay.com/AxM3/donate)

**[Pour tester l'outil en ligne (GitHub Pages)](https://ax4m3.github.io/RollSheet/)**

### Langues
- English version : [README in English](README.en.md)
- Deutscher Sprache : [README auf Deutsch](README.de.md)
- Versión en español : [README en español](README.es.md)

---

## Fonctionnalités

- **Formulaire Web** : Saisissez manuellement l'identité, l'avatar, les statistiques, compétences et l'histoire de votre personnage.
- **Génération aléatoire** : Créez des personnages instantanément grâce au bouton *Aléatoire*.
- **Système multilingue** : Interface disponible en Deutsch (DE), English (EN),  Español (ES) et Français (FR).
- **Thème adaptatif** : Gestion intégrée d'un mode sombre pour préserver vos yeux lors des sessions nocturnes.
- **Export multi-formats** :
  - **📥 PDF** : Générez une fiche prête à imprimer via.
  - **📄 DOCX (Word)** : Exportez un fichier modifiable pour peaufiner votre fiche sur votre traitement de texte.
  - **💾 JSON** : Sauvegardez la structure de données de votre personnage pour la recharger plus tard.
  - **Partage** : Partager votre fiche avec le lien généré fourni.

## Utilisation & Installation

### Option 1 : Utilisation en ligne (Recommandé)
Rendez-vous directement sur la page du projet hébergée par GitHub :
-> **[https://ax4m3.github.io/RollSheet/](https://ax4m3.github.io/RollSheet/)**

### Option 2 : Utilisation locale (Sans internet)
Aucun serveur ni installation (comme Python) n'est requis.
1. Téléchargez ou clonez le dépôt :
   ```bash
   git clone [https://github.com/Ax4M3/RollSheet.git](https://github.com/Ax4M3/RollSheet.git)
   cd RollSheet
   ```
2. Double-cliquez sur le fichier `index.html` pour ouvrir le générateur instantanément dans votre navigateur.

## Systèmes de jeux supportés
**- *Note* : Les systèmes installés nécessitent encore des améliorations, il manque encore beaucoup d'élément qui seront ajouté par la suite.**

| Système | État | Attributs gérés |
| --- | --- | --- |
| **Donjons & Dragons** | ✓ Implémenté | Force, Dextérité, Constitution, Intelligence, Sagesse, Charisme |
| **Warhammer** | ✓ Implémenté | WS, BS, S, T, Ag, Int, WP, Fel |
| **Call of Cthulhu** | ☓ À venir | *Prochainement* |
| **Pathfinder** | ☓ À venir | *Prochainement* |

## Contibuer
Les contibutions sont les bienvenues pour faire grandir l'outil. N'hésiter pas à ouvrir une *Pull Request* ou une *Issue* pour : 
- Proposer de nouveaux systèmes de jeu de rôle (Shadow run, Cyberpunk, etc.).
- Améliorer / Moderniser le design des fiches générées (CSS).
- Ajouter ou corriger des traductions.

## Licence
Ce projet est distribué sous licence MIT. Voir le fichier [LICENSE](https://github.com/Ax4M3/RollSheet/blob/main/license.html) ou la [page dédiée](https://ax4m3.github.io/RollSheet/license.html) pour plus de détails.