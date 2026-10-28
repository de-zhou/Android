KIT PWA ANDROID — Test

Contenu :
- index.html : page de lancement avec bouton vers votre lien Qualtrics.
- manifest.webmanifest : nom et réglages de l'icône installable.
- icons/icon-192.png et icons/icon-512.png : votre icône personnalisée.

Mise en ligne sans coder :
1. Décompressez le ZIP.
2. Déposez le contenu du dossier (index.html, manifest.webmanifest et dossier icons) sur un hébergeur de site statique HTTPS, par exemple Netlify Drop.
3. Ouvrez l'adresse HTTPS obtenue dans Chrome Android.
4. Dans le menu ⋮, cherchez « Installer l'application » ou « Ajouter à l'écran d'accueil ».
5. Lancez l'icône installée, puis appuyez sur « Ouvrir Qualtrics » pour tester le questionnaire.

IMPORTANT :
- La page affiche un bouton plutôt qu'une redirection immédiate pour faciliter l'installation et le test. L'appui sur l'icône ouvre la page « Test », puis le bouton mène à Qualtrics.
- Le lien contient participant_id=104. Si plusieurs participants utilisent ce même lien, leurs accès ne seront pas distingués par cet identifiant. Préparez des liens distincts si l'attribution individuelle est nécessaire.
- L'ouverture du lien ne garantit pas à elle seule qu'une nouvelle réponse soit enregistrée à chaque appui. Vérifiez le résultat dans Qualtrics.
- Utilisez le dispositif conformément au protocole de recherche et informez les participants du suivi prévu.
