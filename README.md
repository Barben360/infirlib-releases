# InfirLib — releases

Distribution publique des APK signés d'InfirLib (application de gestion de
tournée pour infirmières libérales). Le code source vit ailleurs, dans un
dépôt privé — ce dépôt-ci ne porte que des Releases (APK + changelog) et un
`manifest.json`.

## Installer ou mettre à jour

Dernière version : **[releases/latest](https://github.com/Barben360/infirlib-releases/releases/latest)**

Ce lien pointe toujours vers la dernière version publiée — partageable
directement ou sous forme de QR code.

Installation par sideload : téléchargez l'APK depuis la page de la release et
ouvrez-le sur le téléphone. Android demandera d'autoriser l'installation
depuis cette source la première fois (réglage à valider une seule fois).

## `manifest.json`

`manifest.json`, à la racine de `main`, décrit la dernière version publiée et
la version plancher encore supportée. Il est lu par l'application elle-même
pour la vérification de mise à jour, via
[`raw.githubusercontent.com`](https://raw.githubusercontent.com/Barben360/infirlib-releases/main/manifest.json).
