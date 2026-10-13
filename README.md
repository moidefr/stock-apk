# APK disponibles

## Nemo — dernière version : 0.16.1

[Télécharger Nemo 0.16.1 pour Android](https://raw.githubusercontent.com/moidefr/stock-apk/main/nemo-0.16.1-debug.apk)

Ouvre le fichier téléchargé pour installer la mise à jour. Même paquet et même certificat que les versions 0.10.0 et 0.16.0 publiées ici : installation par-dessus, données conservées.

Correctifs de la 0.16.1 :

- La fin normale d’un parcours web libère le téléphone immédiatement, même hors ligne ; le créneau ne se reverrouille pas au prochain passage. « Arrêter ici » reste distinct d’une session terminée.
- Pendant la génération, « Discuter avec l’assistant » ouvre la même conversation Claude/ChatGPT pour répondre ou préciser la demande. Une clarification n’arrête plus immédiatement l’attente de publication.
- Les actions de l’écran de blocage restent accessibles en faisant défiler la page.

Les fonctions de la 0.16.0 restent présentes : ouverture depuis le site, prompts mobiles, listes sur l’accueil, quatre animations et petit jeu d’attente.

Construit par [GitHub Actions](https://github.com/moidefr/nemo-app/actions/runs/38426406257), source : [PR #4](https://github.com/moidefr/nemo-app/pull/4), commit `5f1775e258f2da53ec3d5708a5accad2be9818d3`. Tests de régression Android, compilation et signature vérifiés. Parcours réel avec les comptes assistants encore à vérifier sur téléphone.

SHA-256 : `67a4e1777b0ff7035fe9f8ddc810b101b16c66319b703ece14096ceb1fb71d44`.

Les anciennes versions et les APK des autres applications restent disponibles dans les fichiers du dépôt.
