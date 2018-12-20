# TP2 Reseau 
# I.Exploration locale en solo
## 1.Affichage d'information sur la pile TCP/IP locale

Adresse ip wifi : `10.33.1.156`
Adresse réseau de l'adresse ip wifi : `10.33.0.0 /22`
Adresse Broadcast de l'adresse ip wifi : `10.33.3.255 /22`

Adresse physique wifi : `14-4F-8A-53-76-2C`

Adresse ip Ethernet : Tant que c'est pas branché elle n'en a pas.
Adresse physique Ethernet : `8C-EC-4B-1A-88-D3` Elle en a toujours une même quand elle n'est pas branché.

L'adresse réseau et l'adresse Boradcast ne peuvent se faire qu'à partir de l'adresse ip il n'y en a donc pas pour les adresses physique ou adresse MAC que ce soit pour le wifi ou pour l'ethernet.

Pour afficher l'adresse ip de la passerelle de notre carte wifi il faut aller sur l'invite de commande et taper la commande ipconfig (/all).
L'adresse de passerelle par défaut et dans la carte réseaux sans fil wifi.
Adresse passerelle : `10.33.3.253`

Pour accéder a l'addresse IP en utilisant l'interface graphique il faut aller sur le panneau de configuration, cliquer sur réseau et internet, ensuite aller sur centre réseau et partage. Quand vous en êtes la cliquer sur votre réseau wifi, allez sur détails et ça va vous affichez votre adresse IP, la MAC et la gateway (tout ça c'est pour windows).

Dans le réseau ingésup la Gateway sert a communiquer avec les réseaux exterieur.

## 2.Modifications des informations
### A.Modification d'adresse IP - pt.1

- La première IP du réseau est l'adresse réseau +1 ce qui nous donne:
 `10.33.0.1 /22`
- La dernière IP du réseau est l'adresse Broadcast -1 ce qui nous donne:
 `10.33.3.254 /22`
- Le +1 et -1 sont nécéssaire car les deux adresses (réseau et broadcast) ne sont pas disponible.

### B.`nmap`

Fait



# II.Exploration locale en duo