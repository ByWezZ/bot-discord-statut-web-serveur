# info 
le bot a etais fait a l'aide d'un autre bot similaire mais malle fait je les donc modifier pour le rendre simple a configurer
si vous voulez plus soutenez moi sur [patreon](https://www.patreon.com/ILowayn) (j'ai fait tout un doc pour comment l'utiliser <3 chaque 100 euro de dont j'upload un bot prive en publique ! )  
support sur [Genesis](https://discord.gg/yuEy6W7) lien discord

# information du bot
le bot et capable d'afficher les statut de vos sites ou serveurs (gmod,fivem,autre)   
il et tres simple a configure et a modifier . 
# Image
la version que vous aurez sera comme ça  

![](https://github.com/Ateek2/bot-discord-statut-web-serveur/blob/main/image/photo.PNG)  

le bot a etais configure pour qu'il soit comme ça (vous devez modifier le ``index.js`` si vous le voullez comme ça)  

![](https://github.com/Ateek2/bot-discord-statut-web-serveur/blob/main/image/top%201.PNG)  

![](https://github.com/Ateek2/bot-discord-statut-web-serveur/blob/main/image/top%202.PNG)  

# pourquoi ce bot ?
ce genre de bot ce trouver beaucoup dans les serveurs discord de type hebergeur , serveur jeu 
mais il et privé de tousse je les donc fait pour que les future fondateur ou developeur puisse montre l'etats de leur service comme un panel en ligne ou un site web ou un serveur de jeu
# Installation  
-- Windows 
 - Telecharge le bot 
 - extraire dans un fichier  
 - double clic sur ``install.bat`` (installe les fichier require)
 - ouvre et configure le fichier ``config.json`` (il y a un exemple ``EXEMPLE.config.json``)
 - !! attention avant de demare assure vous que votre bot disposse des droit admin dans votre serveur discord sinon sa marche pas !!
 - demare le bot avec ``start.bat``

-- Linux (non testé !)
 - faite ``wget https://github.com/Ateek2/bot-discord-statut-web-serveur/archive/refs/heads/main.zip``
 - extraire le fichier avec la commende ``tar bot-discord-statut-web-serveur.zip``
 - allez dans le fichier avec ``cd bot-discord-statut-web-serveur``
 - installer les fichier require avec la commande ``npm install`` (vous devez avoire ``nodejs`` et ``npm`` installez sur la machine !)
 - ouvre le fichier config avec ``nano config.json`` (il y a un exemple ``EXEMPLE.config.json``)
 - !! attention avant de demare assure vous que votre bot disposse des droit admin dans votre serveur discord sinon sa marche pas !!
 - demare le bot avec ``node index.js``
# configuration 
il et limiter a 5 service (2 service web , 2 service VPS , 1 service node) si vous vouller rajouter plus il faudras modifier le ``index.js``
dans le fichier ``config.json`` ce trouve des parametre a remplire vous pouvez tout remplire ou laisser vide 
vous ne pouvez pas faire de copier coller de ces parametre  car il faut les deffinire !!! 
```json
{
    "bottoken": "", <-- le token de votre bot
    "setchannel": "", <-- l'id du salon au quelle il envera le message

    "nameweb0": "google.com",   <-- le nom du site web
    "ipweb0": "google.com",  <-- l'ip du site web
    "portweb0": "80", < -- le port du site (part default il restea 80)

    "nameweb1": "youtube.com",  <-- le nom du site web
    "ipweb1": "youtube.com", <-- l'ip du site web
    "portweb1": "80", < -- le port du site (part default il restea 80)

    "namevps0": "google.com",  <-- le nom du vps
    "ipvps0": "google.com",  <-- l'ip du vps
    "portvps0": "80", < -- le port du vps (part default il restea 80)

    "namevps2": "google.com",  <-- le nom du vps
    "ipvps2": "google.com", <-- l'ip du vps
    "portvps2": "80", < -- le port du vps (part default il restea 80)

    "namenode0": "google.com",  
    "ipnode0": "google.com",
    "portnode0": "80" < -- le port du node (part default il restea 80)
}
```
# autre type de configuration dans ``Index.js``  
a la ligne ``93`` fait une actualisation toute les 5 min  
a la ligne ``58-59`` vous pourez changer le ou la couleur , emojy pour definire le on et off   
de la ligne ``15 a 31`` definie les variable dans le ``config.json``   
de la ligne ``60 a 67`` definie si l'ip a repondue au ping ou non   
de la ligne ``53 a 57`` montre les info du ping dans la console ou terminal  
de la ligne ``43 a 52`` tcpp fait  le ping au varable donais dans le ``config.json``   
