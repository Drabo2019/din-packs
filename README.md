# DIN — packs de recueils de hadiths

Fichiers SQLite téléchargés à la demande par l'application DIN (un fichier par recueil).
Ils sont publiés dans les **Releases** de ce dépôt (tag `collections`) ; le nom de chaque fichier
contient sa version (`collection-<recueil>-<version>.db`) et ne change jamais.

## Contenu et provenance

- Texte arabe vocalisé, numérotation, livres et jugements de savants nommés :
  [hadith-api](https://github.com/fawazahmed0/hadith-api) de fawazahmed0, commit `df57907`,
  **domaine public ([Unlicense](https://github.com/fawazahmed0/hadith-api/blob/1/LICENSE))**.
- Seul le texte arabe est repris : les traductions de hadith-api sont exclues (provenance non licenciée
  ou traduction automatique).
- Chaque fichier contient une table `sources` (jeu de données, licence, texte d'attribution) et une
  table `meta` (version, empreinte SHA-256 du contenu, comptes).

L'intégrité d'un fichier est vérifiée par l'application (taille et MD5 publiés dans son pack de base).

Toute connaissance mène à sa source.
