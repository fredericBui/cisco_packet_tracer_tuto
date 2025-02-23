# Configurer un ordinateur
- Configurer son adresse IP
- Entrer dans le terminal de commande
- Voir l'adresse IP

![Configure IP of a computer](1.png "Configure IP of a computer")

# Faire communiquer deux ordinateurs ensemble
- Connecter deux ordinateurs via un cable
- Ajouter un masque de sous réseau
- Envoyer un ping depuis un ordinateur

![2 computers linked, PC0 ping PC1](2.png "2 computers linked, PC0 ping PC1")

# Relier 3 machines via un switch
- Placer un switch
- Ajouter un troisième ordinateur sous le même masque réseau
- Envoyer un ping depuis un ordinateur vers les deux autres

![3 computers linked by a switch](3.png "3 computers linked by a switch")

# Créer des sous réseaux avec des VLAN
(Segmentation logique au niveau 2 - réseau virtuel)

- Ajouter un autre ordinateur
- Ajouter deux VLAN
- Faire correspondre les VLAN aux interfaces pour créer deux sous réseaux

![2 computers per subnetwork with VLAN](4.png "2 computers per subnetwork with VLAN")

# Créer un sous réseaux via les masques de sous réseaux
(Segmentation au niveau 3 - adressage IP)

![create a new subnetwork just with IP and netmask](5.png "create a new subnetwork just with IP and netmask")

# Communiquer d'un sous réseaux à un autre via un routeur

- Repartir de zéro pour se simplifier la tâche
- Ajouter deux ordinateurs, deux switch et un routeur
- Configurer les adresses IP, Gateway
**Ne surtout pas oublier d'activer les interfaces**

![2 computer in a separate network that communicate through a gateway with a router](6.png "2 computer in a separate network that communicate through a gateway with a router")

# Router on a stick
