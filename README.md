# pfsense_sne
Modification du template Pfsense

1- Ajouter les fichiers <b>captiveportal-style.css</b>, <b>login.html</b>, <b>login_error.html</b> et <b>logo.png</b> sur le serveur pfsense depuis l'interface d'administration du pfsense --> menu <b>Services</b> sous-menu <b>Portal Captive</b> Editer la <i>Captive Portal Zone</i> puis dans le menu <b>File Manager</b> (6ème menu à partir de la gauche) ajouter les fichiers un par un (+ADD).

2- Dans le menu <b>Configuration</b> (1er menu à partir de la gauche) de la zone repérer la section <i>HTML Page Contents</i> puis pour l'attribut <i>Portal page contents</i> appuyer sur choisisser un fichier et selectionner <b>index.html</b> puis faire de même pour <i>Auth error page contents</i> et choisir cette fois  <b>login_error.html</b>.

Votre thème est modifié !

<center><img src="https://github.com/julbo250/pfsense_sne/blob/master/Capture%20portail.PNG"></center>
