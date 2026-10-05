# Dragonne Club

Appli Android de Dragonne Créa pour les ventes au club de rugby : catalogue avec photos et prix, ventes en espèces, commandes avec acompte, suivi de fabrication, bilan et export Excel.

## Installer sur la tablette

Sur la tablette, ouvrir ce lien dans Chrome :

**https://github.com/Sebastien-design-fr/dragonne-club/releases/latest/download/dragonne-club.apk**

Puis ouvrir le fichier téléchargé et toucher **Installer**. La première fois, Android demande d'autoriser Chrome à installer des applis : accepter.

Une nouvelle version s'installe de la même façon, par-dessus l'ancienne. Les articles, ventes et commandes sont conservés.

## Données

Tout est enregistré sur la tablette, rien n'est envoyé en ligne. Faire régulièrement une sauvegarde depuis l'onglet **Bilan** et la garder ailleurs (mail, Drive, ordinateur). Désinstaller l'appli efface ses données.

## Fonctionnement technique

- `www/` : l'appli (une page HTML, sans dépendance).
- `.github/workflows/apk.yml` : à chaque modification, GitHub fabrique l'APK avec Capacitor et le publie dans **Releases**.
- `signing/` : clé de signature. Elle doit rester identique pour que les mises à jour s'installent par-dessus l'ancienne version.
