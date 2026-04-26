INSTALLATION - YTM BY GODAS DEV

⚠️ IMPORTANT :
Suivre les étapes dans l’ordre.

----------------------------------

1. INSTALLER YOUTUBE MUSIC DESKTOP

Lancer :
YouTube Music Desktop Setup.exe

----------------------------------

2. CONFIGURER YTM API

Ouvrir YouTube Music Desktop

Paramètres → Extensions → Serveur API Beta

Mettre :

✔ Activé
✔ Hôte : 127.0.0.1
✔ Port : 26538
✔ Plan d’autorisation : Pas d’autorisation

----------------------------------

3. CONFIGURER GOOGLE CLOUD

➡️ Voir fichier :
02 - GOOGLE CLOUD.txt

----------------------------------

4. IMPORTER LE BOT

Ouvrir Streamer.bot

Import → sélectionner le fichier dans :
StreamerBot Export/

----------------------------------

5. CONFIGURER LES VARIABLES

Dans l’action :
godasytm

Remplir :

youtubeApiKey = TA_CLE_API
youtubeClientId = TON_CLIENT_ID
youtubeClientSecret = TON_CLIENT_SECRET
youtubePlaylistId = TON_ID_PLAYLIST
ytmHost = 127.0.0.1
ytmPort = 26538

----------------------------------

6. LANCER LE SETUP

Dans le chat Twitch :

!godasytm

➡️ Autoriser Google dans le navigateur

----------------------------------

7. TEST

!sr nom musique
!song
!next
!playlist

----------------------------------

INSTALLATION TERMINÉE ✅
