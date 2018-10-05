## FOMATION WORDPRESS

###### Liens Utiles
* Téléchargement de [Mamp](https://www.mamp.info/en/) 
* Téléchargement de [Wordpress](https://fr.wordpress.org/download/) 
* Installation Wordpress en Local avec Mamp [Lien](https://www.nicolas-mauhin.fr/installer-wordpress-mac-mamp) 
* Installation Wordpress sur serveur + configuration [Lien](https://www.hostinger.fr/tutoriels/tuto-wordpress/) 
* Installation d'un sous-dossier dans wordpress (ex : http://nomdedomaine.fr/toto/ mais http://nomdedomaine.fr) [Lien](https://codex.wordpress.org/fr:Donner_%C3%A0_WordPress_son_Propre_Dossier) 
* Installation d'un thème ex: divi [Lien](https://www.elegantthemes.com/documentation/divi/install-divi/) 
* Installation d'un plugin [Lien](https://wpformation.com/comment-installer-plugin-wordpress-gratuit-premium/) 
* Site de référence Wordpress [Lien](https://fr.wordpress.org/) 

###### Liste de plugins
* Yoas pour le référencement [Lien](https://fr.wordpress.org/plugins/wordpress-seo/) 
* Mettre son site en maintenance [Lien](https://fr.wordpress.org/plugins/wp-maintenance/)
* Sauvegarder son site bdd + wordpress [Lien](https://fr.wordpress.org/plugins/updraftplus/)
* Formulaire de contact [Lien](https://fr.wordpress.org/plugins/contact-form-7/)
* Dupliquer le site [Lien](https://fr.wordpress.org/plugins/duplicator/)


###### Fichier .htaccess
Il faut récupérer le fichier .htacces qui est à la racine des fichiers wordpress
très important il ne faut pas oublié de modifier

<IfModule mod_rewrite.c>  
RewriteEngine On  
RewriteBase /nomdudossierwp/  
RewriteRule ^index\.php$ - [L]  
RewriteCond %{REQUEST_FILENAME} !-f  
RewriteCond %{REQUEST_FILENAME} !-d  
RewriteRule . /nomdudossierwp/index.php [L]  
</IfModule>

