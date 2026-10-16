# WALLSPACE

Application gratuite pour Windows 11 x64 : images, vidéos et scènes interactives derrière les icônes du bureau, sans Lively et sans installation de .NET.

## Télécharger et démarrer

[Télécharger WALLSPACE 0.7.0 — bêta publique](https://github.com/kenwork133/WALLSPACE/releases/tag/v0.7.0-beta.1)

1. Télécharger **WALLSPACE-0.7.0-beta.1-win-x64.zip** dans les fichiers de la version.
2. Extraire entièrement le dossier dans un emplacement durable, par exemple `Documents\WALLSPACE`.
3. Ouvrir **APP_WALLSPACE.exe**. Aucun droit administrateur n'est nécessaire.
4. Utiliser **Importer** pour ses images/vidéos, ou **Découvrir** pour obtenir les six créations gratuites. Rien n'est ajouté à la bibliothèque sans choix de l'utilisateur.
5. Choisir un écran ou le panorama, puis **Appliquer**. **Pause / Reprendre** et **Tout arrêter** restent accessibles en bas.

Le programme n'est pas signé numériquement. Windows peut donc afficher un avertissement de réputation. Vérifier l'origine du téléchargement et son empreinte dans `SHA256SUMS.txt` ; ne pas désactiver les protections de Windows.

## Fonctions disponibles

- Images et vidéos locales, horloge/date et particules réagissant à la souris.
- Plusieurs écrans : fonds distincts, même fond et panorama.
- Bibliothèque avec recherche, filtres, favoris, collections, renommage et confirmation de retrait.
- Personnalisation des scènes : aperçu, enregistrement indépendant, Annuler/Rétablir.
- Démarrage Windows facultatif, zone de notification, pauses automatiques et rotation activable dans Paramètres.
- Sauvegarde/restauration par packs locaux, manuel intégré et options d'accessibilité.

## Données et compte

Les médias importés, chemins, miniatures, bibliothèque, préférences et personnalisations restent sur le PC. WALLSPACE fonctionne sans compte et sans connexion Internet. La météo et la vérification de mises à jour sont des fonctions réseau facultatives.

Cette bêta n'annonce aucun service public de comptes opérationnel. La base en préparation est réservée aux profils de compte et aux droits sur les créations officielles ; elle ne sert pas à synchroniser les fichiers personnels. Les boutons de compte restent indisponibles tant qu'un service réellement prêt n'est pas configuré.

Lire [CONFIDENTIALITE.md](CONFIDENTIALITE.md) pour les données, services facultatifs et suppression locale.

## Mettre à jour ou retirer l'application

Pour quitter complètement, choisir **Quitter** dans le menu WALLSPACE de la zone de notification. Une mise à jour se fait après fermeture complète, en extrayant le nouveau programme dans son dossier. Les données ne sont pas contenues dans le ZIP.

Si le lancement automatique est activé, désactiver puis réactiver ce réglage après un changement de dossier. Pour retirer WALLSPACE, désactiver d'abord le démarrage automatique, choisir **Tout arrêter**, quitter, puis retirer le dossier du programme. Les données dans `%LOCALAPPDATA%\APP.WALLSPACE` et les fichiers originaux sont conservés.

## Qualité et limites de cette bêta

Le binaire 0.7.0 a passé **489 contrôles sur 15 suites**. Ces contrôles couvrent interface WPF, bibliothèque, sauvegardes, paramètres et moteur. Deux moniteurs physiques ont été exercés avec des affectations temporaires. Les tests réseau historiques emploient des transports simulés : ils ne valident pas un service distant public.

Restent à éprouver : changement d'identité des moniteurs après reconnexion, redémarrage réel et restauration avec différentes configurations, performances GPU/vidéos sur longue durée. Certains codecs dépendent de Windows. Les réglages FPS concernent les scènes générées ; ils ne forcent pas la cadence de toutes les vidéos. Les réglages vidéo restent surtout globaux ou par écran.

Les mises à jour sont manuelles. Pas de boutique payante, de communauté, d'envoi de médias personnels ni de synchronisation de bibliothèque en ligne dans cette version.

## Assistance

[Signaler un problème](https://github.com/kenwork133/WALLSPACE/issues) en indiquant version, édition de Windows et étapes de reproduction. Éviter d'inclure ses photos, identifiants, chemins privés ou journaux bruts ; vérifier le contenu de tout rapport avant de le publier.

Ce dépôt distribue les versions officielles et leur documentation. Le code source privé de l'application n'y est pas publié. Les licences des composants .NET sont fournies dans le dossier `Licences` du téléchargement.
