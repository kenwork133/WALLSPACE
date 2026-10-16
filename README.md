# WALLSPACE

Application gratuite pour Windows 11 x64 : images, vidéos et scènes interactives derrière les icônes du bureau. Autonome, sans Lively et sans installation de .NET.

## Télécharger

[Télécharger WALLSPACE 0.8.1 — bêta publique](https://github.com/kenwork133/WALLSPACE/releases/download/v0.8.1-beta.1/WALLSPACE-0.8.1-beta.1-win-x64.zip) · [Notes et empreintes de la version](https://github.com/kenwork133/WALLSPACE/releases/tag/v0.8.1-beta.1)

1. Extraire entièrement le ZIP dans un dossier durable, par exemple `Documents\WALLSPACE`.
2. Ouvrir **APP_WALLSPACE.exe**. Aucun droit administrateur n’est nécessaire.
3. Choisir **Importer** pour ses images et vidéos, ou **Découvrir** pour obtenir gratuitement les créations officielles.
4. Choisir son écran, plusieurs écrans ou le panorama, puis **Appliquer**.

Le programme n’est pas signé numériquement. Windows peut afficher un avertissement de réputation ; vérifier l’origine du téléchargement et son empreinte `SHA256SUMS.txt`. Ne pas désactiver les protections Windows.

## Créer et gérer son compte

La connexion officielle WALLSPACE est déjà configurée dans cette version. Aucune clé ni adresse de serveur n’est à saisir.

1. Ouvrir **Paramètres → Compte en ligne**.
2. Indiquer son adresse e-mail et choisir un mot de passe d’au moins 12 caractères, puis **Créer un compte gratuit**.
3. Recopier le code de huit chiffres reçu par e-mail dans **Valider mon adresse e-mail**. La saisie du code s’ouvre après l’inscription.
4. Utiliser ensuite **Se connecter** sur un autre PC, avec la même adresse et le même mot de passe.

**Mot de passe oublié** permet de demander un nouveau code et de choisir un nouveau mot de passe. Un code expire au bout d’une heure et ne s’utilise qu’une fois. Vérifier les courriers indésirables et attendre une minute avant de redemander un e-mail.

**Se déconnecter** ferme la session sur ce PC. **Supprimer mon compte** exige le mot de passe actuel et une confirmation explicite ; la suppression en ligne est définitive. Elle conserve les fichiers et la bibliothèque sur le PC.

Le compte reste facultatif. Les fonctions locales fonctionnent hors ligne. La bibliothèque personnelle, ses fichiers, chemins, miniatures et personnalisations ne sont pas synchronisés entre PC. Le transfert de ces données se fait par les sauvegardes locales que vous exportez.

## Fonctions disponibles

- Images et vidéos locales, horloge/date et particules réagissant à la souris.
- Plusieurs écrans : fonds distincts, même fond ou panorama.
- Bibliothèque avec recherche, filtres, favoris, collections, renommage et confirmation de retrait.
- Personnalisation avec aperçu, enregistrement indépendant, Annuler/Rétablir.
- Démarrage Windows facultatif, zone de notification, pauses automatiques et rotation dans Paramètres.
- Sauvegarde et restauration par packs locaux, manuel intégré et options d’accessibilité.

## Mise à jour et retrait

Choisir **Quitter** dans le menu WALLSPACE près de l’horloge Windows avant de remplacer le programme par une nouvelle version. Les données ne sont pas contenues dans le ZIP.

Si le dossier du programme change, désactiver puis réactiver son lancement avec Windows. Pour retirer l’application, désactiver le démarrage automatique, choisir **Tout arrêter**, quitter et retirer le dossier du programme. Les données locales et les fichiers originaux restent conservés. Cela ne supprime pas le compte en ligne.

## Vérifications et limites

Cette publication a passé **517 contrôles sur 15 suites** sur son exécutable autonome. L’inscription publique, les e-mails reçus, la connexion, la récupération, la déconnexion, la suppression et l’isolation de deux comptes réels ont aussi été vérifiées avec la seule clé publique. Les comptes de test ont été supprimés après les essais.

La distribution reste une bêta : restauration après un redémarrage réel, reconnexion des moniteurs et performances vidéo/GPU sur longue durée restent à éprouver sur davantage de PC. Certains codecs dépendent de Windows. La limite FPS concerne les scènes générées, pas la cadence encodée de toutes les vidéos.

Les mises à jour sont manuelles. Le service de comptes utilise des offres gratuites avec des quotas et sans disponibilité permanente garantie. Pas de boutique payante, de communauté ni d’envoi de médias personnels dans cette version.

## Données et assistance

Lire [CONFIDENTIALITE.md](CONFIDENTIALITE.md). [Signaler un problème](https://github.com/kenwork133/WALLSPACE/issues) en indiquant version, édition Windows et étapes de reproduction. Ne jamais publier un mot de passe, un code de connexion, un jeton, une adresse e-mail personnelle ou un journal brut.

Ce dépôt distribue les versions officielles et leur documentation. Le code source privé n’y est pas publié. Les licences .NET sont fournies dans le dossier `Licences` du téléchargement.
