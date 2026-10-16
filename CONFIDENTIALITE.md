# Données de WALLSPACE — version 0.8.1

## Données sur votre PC

WALLSPACE conserve sa bibliothèque, ses préférences, sa session de bureau et ses journaux dans `%LOCALAPPDATA%\APP.WALLSPACE`. Les fichiers originaux restent à leur emplacement. Les imports gérés, miniatures et personnalisations restent locaux. Les sauvegardes et transferts se font par les packs que vous exportez vous-même.

Le monitoring CPU/RAM et les informations d’écran sont traités localement. Aucun envoi automatique de diagnostics, de photos, de vidéos, de miniatures, de chemins Windows, de préférences ou de personnalisations personnelles n’est activé.

## Compte facultatif

Le service officiel est préconfiguré. Lorsque vous utilisez volontairement les fonctions de compte, votre adresse e-mail, votre mot de passe et les codes de validation sont transmis par HTTPS au projet Supabase WALLSPACE. Supabase gère l’identité, l’authentification et les données actives du compte. Le projet de base est situé en région Stockholm. Les profils et droits d’accès aux créations officielles sont isolés entre comptes par les règles du serveur.

Le mot de passe n’est pas enregistré par WALLSPACE sur le PC. Les jetons de session nécessaires pour rester connecté sont protégés localement pour l’utilisateur Windows par DPAPI. Une session expirée peut nécessiter une nouvelle connexion. L’application ne contient aucune clé d’administration du service.

Brevo transmet les e-mails de confirmation et de récupération à l’adresse que vous indiquez. Les prestataires reçoivent aussi les informations techniques nécessaires au fonctionnement et à la protection du service, notamment les adresses IP et les événements d’authentification ou de livraison. Leurs journaux techniques et sauvegardes suivent leurs propres règles de conservation.

Le compte ne synchronise pas votre bibliothèque personnelle entre PC. Les fonctions locales restent utilisables sans compte.

## Autres fonctions réseau

La météo, si vous l’autorisez et choisissez une ville, contacte Open-Meteo. La recherche de mises à jour peut consulter le catalogue HTTPS que vous avez configuré. Ces fonctions ne transmettent pas les médias de votre bibliothèque ; les serveurs contactés reçoivent les informations habituelles d’une connexion.

## Déconnexion et suppression

Dans **Paramètres → Compte en ligne**, **Se déconnecter** ferme la session sur ce PC. **Supprimer mon compte** exige de confirmer le mot de passe actuel et de saisir `SUPPRIMER`. Le serveur exige une authentification récente par mot de passe et une session active, puis supprime uniquement le compte concerné, ses sessions et les lignes de profil et de droits qui lui appartiennent. La suppression est définitive pour les données actives du compte.

Les fichiers personnels, la bibliothèque et les réglages sur votre PC sont conservés lors de cette suppression. Effacer le dossier local ou retirer le programme ne supprime pas le compte distant. La suppression d’un fond de la bibliothèque exige confirmation et conserve le fichier original.

## Assistance

Les rapports de problème sont facultatifs. Vérifiez leur contenu avant tout partage. Utilisez les [problèmes GitHub WALLSPACE](https://github.com/kenwork133/WALLSPACE/issues) pour les questions générales, sans publier vos e-mails, mots de passe, codes, jetons, fichiers personnels ou journaux bruts.

Les conditions des prestataires sont disponibles auprès de [Supabase](https://supabase.com/privacy) et de [Brevo](https://www.brevo.com/fr/legal/privacypolicy/).
