# Saison

Page publiée de l’application **Saison** : le planning des manifestations d’un conservatoire, tenu dans un fichier `planning.md`, avec l’affiche à imprimer (une page par période) et le corps du mail « Demandez le programme ».

La page ne contient aucune donnée : elle lit et écrit le fichier choisi par l’utilisateur. Les sources sont dans un dépôt privé.

Polices intégrées : Inter (Rasmus Andersson) et Lora (Cyreal), sous licence SIL Open Font License 1.1.

## Appli Android « Saison »

Le dossier `android/` contient le Compagnon : une coquille qui affiche cette page et lui donne accès à `planning.md` (par l'appli OneDrive du téléphone, puis directement en ligne). Elle est fabriquée par GitHub Actions et publiée dans la version « android » de ce dépôt (`saison.apk`). La fabrication exige les secrets `KEYSTORE_B64` et `KEYSTORE_PASS` (clé de signature).
