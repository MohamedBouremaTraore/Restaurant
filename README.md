Pour exécuter sur un environnement local :
-------------------------------------------------- --------------------
1. Importez le fichier .sql présent dans le répertoire Database File/.
Modifiez le nom et le mot de passe de la base de données dans les fichiers config.ini trouvés dans includes/, admin/includes/, staff/includes.

2. Le projet utilise [PHPMailer](https://github.com/PHPMailer/PHPMailer) pour envoyer des e-mails.
Pour pouvoir envoyer des e-mails sur un environnement local, mettez à jour l'utilisateur et passez les paramètres dans les fichiers config.ini trouvés dans includes/, admin/includes/, staff/includes avec votre identifiant GMAIL et votre mot de passe.

3. Activez les applications moins sécurisées sur votre identifiant gmail. (Suivez les instructions sous "Activer les paramètres des 'applications moins sécurisées' en tant qu'utilisateur de boîte aux lettres" [ici](https://hotter.io/docs/email-accounts/secure-app-gmail/)). Ceci est nécessaire pour que les e-mails soient envoyés.
-------------------------------------------------- --------------------
Autres identifiants :

1. Testez les détails de la passerelle de paiement :
Carte:
Numéro de carte : N'importe quelle carte Visa ou Master Card (Ex : 4111-1111-1111-1111)
Mois et année d'expiration : Tous les mois et années futurs (Ex : 21/11)
CVV : 123
Porte monnaie:
Numéro de portable : 77777 77777
Mot de passe : Paytm12345
OTP : 489871

2. Connexion administrateur :
admin@swadesh.com
passe: 123456

Connexion du personnel :
staff@swadesh.com
passe: 123456

Connexion client :
swadeshrest@gmail.com
passe: 123456

3. Client : http://swadesh.epizy.com/swadesh/
Administrateur : http://swadesh.epizy.com/swadesh/admin
Personnel : http://swadesh.epizy.com/swadesh/staff