# Facture Facile — Code du prototype

## Ouvrir le site
1. Décompressez cette archive (clic droit > Extraire tout sous Windows).
2. Ouvrez le dossier Facture-Facile dans Visual Studio Code.
3. Double-cliquez sur index.html depuis l’explorateur de fichiers pour ouvrir le site dans votre navigateur.
4. Après une modification, enregistrez le fichier dans VS Code puis actualisez la page du navigateur.

Aucune installation de Node.js ou compilation n’est nécessaire.

## Les fichiers
- index.html : structure de la page et navigation.
- style.css : couleurs, mise en page, gros caractères et impression.
- app.js : clients fictifs, devis, factures, calculs et interactions.

## Tester
Cliquez sur Nouvelle facture, choisissez un client, ajoutez une prestation, puis vérifiez et enregistrez le document d’essai.
Pour produire un PDF, ouvrez le document puis utilisez Imprimer / PDF et choisissez Enregistrer au format PDF dans la fenêtre du navigateur.

## Limites de cette version
Les données sont uniquement en mémoire : actualiser ou fermer la page efface les modifications.
Le code ne contient pas de base de données, d’authentification, d’envoi d’e-mail ou de connexion Peppol.
Les factures portent la mention document d’essai, sans valeur comptable. Les taux et mentions doivent être validés pour un usage professionnel.
L’accès privé du site hébergé est fourni par l’hébergement ; cette archive ne contient pas cette protection.
Les polices Google Fonts nécessitent une connexion Internet. Sans connexion, une police de remplacement est utilisée.
