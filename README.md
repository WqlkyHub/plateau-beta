# Plateau — version de test

Plateau (nom provisoire) est un logiciel de **production audiovisuelle** pour Windows : écriture, dépouillement,
découpage, storyboard, plans de feu (2D et 3D), plan de travail, feuilles de service, tournage et post-production.

**Tout reste sur ton ordinateur, chiffré.** Aucun compte n'est nécessaire et rien n'est envoyé sur internet, sauf si tu
choisis de partager un projet avec un autre appareil.

## Télécharger

Va dans **[Releases](../../releases/latest)** et télécharge `Plateau_0.4.3_x64-setup.exe` (environ 6 Mo).

## Installer

1. Ouvre le fichier téléchargé.
2. Windows affiche sans doute **« Windows a protégé votre ordinateur »** : le logiciel n'a pas encore de certificat de
   signature payant. Clique sur **Informations complémentaires**, puis sur **Exécuter quand même**.
3. Suis l'installation (pas besoin d'être administrateur). Plateau s'ouvre ensuite depuis le menu Démarrer.

Configuration : Windows 10 ou 11, 64 bits. Si Microsoft Edge WebView2 manque (rare), l'installateur le télécharge.

**Vérifier le fichier (facultatif)** : dans PowerShell, `Get-FileHash .\Plateau_0.4.3_x64-setup.exe` doit afficher
`07DDAC543FA02CFFD96FF84A18E3F632739831AC90EF46A683CFD144448D2D16`.

## Pour commencer

Au premier lancement, ouvre le **projet d'exemple** (« Les Heures Bleues ») : il montre tous les modules déjà remplis.

## C'est une version de test

- Il peut rester des bugs : pour un vrai projet, fais régulièrement **Fichier › Exporter ou sauvegarder le projet**.
- Tes retours sont précieux : ce qui est pratique, ce qui ne l'est pas, ce qui manque, ce qui plante (avec une
  capture si possible). Envoie-les à la personne qui t'a donné ce lien, ou ouvre une **Issue** sur cette page (compte
  GitHub nécessaire).

## Désinstaller

Paramètres Windows › Applications › Plateau › Désinstaller. Tes projets restent dans
`%APPDATA%\fr.plateau.studio` tant que tu ne supprimes pas ce dossier.
