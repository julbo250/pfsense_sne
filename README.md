# pfsense_sne
Modification du template Pfsense

1. Définir les pages <b>login.html</b> et <b>login_error.html</b><br/>

Dans le menu <b>Services</b>, sous-menu <b>Captive portal</b>, éditer la zone concernée.<br />
Dans l'onglet <b>Configuration</b>, à la section <i>HTML Page Contents</i>, modifier l'attribut <i>Portal page contents</i> et choisir le fichier et selectionner <b>login.html</b>.<br />
Répeter l'opération pour l'attribut <i>Auth error page contents</i> et choisir le fichier <b>login_error.html</b>.


2. Ajouter les fichiers <b>captiveportal-style.css</b> et <b>logo.png</b> sur le serveur pfsense depuis l'interface d'administration du pfsense<br />

Toujours dans la configuration de la zone, dans l'onglet <b>File Manager</b> ajouter les fichiers un par un (+ADD).<br /><br/>


Votre thème est modifié !

<center><img src="https://github.com/julbo250/pfsense_sne/blob/master/Capture%20portail.PNG"></center>
