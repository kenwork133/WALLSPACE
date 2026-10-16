# Données de WALLSPACE — bêta 0.7.0

## Stockage sur votre PC

WALLSPACE conserve sa bibliothèque, ses préférences, sa session de bureau et ses journaux dans `%LOCALAPPDATA%\APP.WALLSPACE`. Les imports gérés sont copiés localement ; les fichiers originaux restent à leur emplacement. Les dossiers d'import et de téléchargement sont réglables. Les miniatures et les personnalisations restent locales. Les sauvegardes et transferts entre PC se font par packs que vous exportez vous-même.

Le monitoring CPU/RAM et les informations d'écran sont traités localement. Les disponibilités des capteurs varient selon le matériel. Aucun envoi automatique de diagnostics ni de médias personnels n'est activé.

## Fonctions réseau facultatives

La météo, si vous l'autorisez et choisissez une ville, contacte les services Open-Meteo nécessaires à la prévision. Une vérification de mises à jour peut contacter l'adresse de catalogue que vous avez configurée. Les serveurs contactés reçoivent les données techniques habituelles d'une connexion, notamment l'adresse IP. Aucun catalogue de mises à jour n'est configuré par défaut dans cette bêta.

Sans service de compte configuré, aucun compte ne se crée et aucune bibliothèque n'est envoyée. En cas d'utilisation volontaire d'un service Auth configuré, l'adresse e-mail et le mot de passe saisis sont transmis par HTTPS au serveur indiqué ; les jetons de session sont protégés localement par Windows DPAPI. Le mot de passe n'est pas enregistré par l'application. Les boutons de synchronisation de bibliothèque sont bloqués dans cette version.

La future base officielle est réservée aux profils et aux droits sur les créations officielles. Aucune photo, vidéo, miniature, chemin Windows, préférence ou personnalisation personnelle n'y est prévue. Un service public de comptes exige encore une configuration et des tests réels ; sa présence dans l'interface ne signifie pas qu'il est actif.

## Retrait et assistance

La suppression d'un fond de la bibliothèque exige confirmation et ne supprime pas son fichier original. Retirer le dossier du programme conserve les données locales. Avant tout effacement volontaire de `%LOCALAPPDATA%\APP.WALLSPACE`, quitter WALLSPACE et exporter les sauvegardes utiles. Cet effacement local ne supprime pas un éventuel compte distant.

Les rapports de problème sont facultatifs. Vérifiez-les avant de les joindre à une demande publique. Utilisez les problèmes GitHub de ce dépôt pour une question générale ; ne publiez jamais un mot de passe, un jeton ou des données personnelles dans un ticket.
