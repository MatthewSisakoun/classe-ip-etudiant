# classe-ip-etudiant

Documentation de la classe IpPackage

Déclaration du package :
Définit le package IpPackage.

Déclaration de la classe IpPackage :
Déclare la classe publique IpPackage.

Déclaration des variables d'instance :
Déclare quatre variables privées octet1, octet2, octet3, octet4 pour stocker les quatre octets d'une adresse IP.

Constructeur privé :
Constructeur privé initialisant les variables d'instance avec les valeurs fournies en arguments.

Méthode de test :
Méthode publique test affichant un message de test.

Méthode statique getInstance :
Crée et retourne une instance de IpPackage après avoir vérifié que chaque octet est compris entre 0 et 255. Affiche les valeurs des octets et un message d'erreur si les valeurs sont incorrectes.

Méthode ToString :
Retourne une chaîne de caractères représentant les valeurs des octets de l'instance.

Accesseurs (getters) pour les octets :
Méthodes publiques getOctet1, getOctet2, getOctet3, getOctet4 pour accéder aux valeurs des octets.

Méthode getClasse :
Détermine la classe de l'adresse IP en fonction du premier octet (A, B, ou C).

Méthode adresseReseau :
Retourne l'adresse réseau de l'instance actuelle, en fonction de sa classe (A, B, ou C).

Méthode estMemeReseau :
Vérifie si l'instance actuelle et une autre instance de IpPackage appartiennent au même réseau.
