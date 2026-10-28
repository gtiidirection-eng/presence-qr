# Présence QR 📋

Application mobile de présence des travailleurs par code QR
(Capacitor, sans serveur : les données restent dans le téléphone).

## Utilisation
1. Onglet **Travailleurs** : ajoute chaque travailleur, puis **Voir le QR**
   (capture d'écran ou impression pour lui donner son code).
2. Onglet **Scanner** : scanne le QR d'un travailleur.
   Premier scan du jour = arrivée, scan suivant = départ.
3. Onglet **Présences** : choisis une date, vois les heures et le total,
   puis partage le rapport.

## Obtenir l'APK
1. Mets tout le contenu de ce dossier sur GitHub (branche `main`),
   sans oublier le dossier caché `.github`.
2. Onglet **Actions** > **Build APK** : attends le rond vert (5 à 10 min).
3. Dans **Artifacts**, télécharge `presence-qr-apk`, dézippe, installe `app-debug.apk`.
4. Au premier lancement, autorise la caméra.
