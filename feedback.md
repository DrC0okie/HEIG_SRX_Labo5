Question 1 : Le problème est que le traffic n'est pas chiffré de bout en bout (-0.5pt)
Question 2 : Il suffit de faire confiance au CA pour faire confiance aux autres client. -1pt
Question 4 bonus : +1.5 pt. SCP et SFTP ne sont pas une bonne solution à elles seule pour envoyer des clé privée, car le canal n'est pas authentifié. 
Question 10: MainS doit déchiffrer les paquet par wg et les rechiffrer. -1pt
Question 12 : Oubli de la mise en place du CA. -0.5pt
Question 15 : AES-256 n'existe jamais seul, mais plutot AES-256-GCM qui permet d'avoir de l'intégrité -0.5Wireguard utilise les PSK uniquement pour ajouter de la sécurité supplémentaire, et ne base pas son authentification la dessus. Non pénalisé car mention de Noise dans la Q16
Question 16: OpenVPN, il ne peut pas avoir de MITM avec un PKI en utilisant Diffie-Hellman. On va vérifier la clé publique de l'autre hôte. -0.5
Question 19 : Vos résultat doivent être du au fait que docker n'est pas un vrai environnement de test, et que le temps de test est un peu bas. Personnellement je fais tourner ces tests quelque minutes, car les changement de clé peuvent prendre du temps. Pas pénalisé.

Note provisoire : 5.7
