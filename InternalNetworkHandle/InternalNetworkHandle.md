# InternalNetworkHandle

## Module Function

### module.Init

Parametre : 
AUCUN
Retour :
AUCUN

Description : 
Sert juste à lancé le script

### module.CreateANetworkNode

Parametre : 
networkConfiguration: Configuration
ipRange: string
Retour :
AUCUN

Description :
Fonction du module qui permet de faire le lien avec la fonction "findIPToGiveToEquipement"

### module.getIpTable

Parametre : 
AUCUN
Retour :
tableIpReturn: {string}

Description :
Permet de sortir la table des IP compilé en string.

### module.IPSOrder

Parametre : 
networkConfiguration: Configuration
ipRange: string
Retour :
AUCUN

Description :
Fonction qui permet de prendre une IP même si elle est déjà prise et 
de la ré-assigné à un équipement.

## Function

### function subDiviseIp
Parametre : 
ip: string
Retour :
ipClasses: {any}

Description :
Fonction qui permet de créer une table avec les classes Ip séparé d'une IP 
donnée en string

### function findIPToGiveToEquipement

Parametre : 
networkConfiguration: Configuration
ipRange: string
Retour :
AUCUN

Description :
Fonction qui permet de donnée une IP dans une range tous en créant les sous classes.