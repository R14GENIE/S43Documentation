# PlayerHandler

## Module Function

### Dépendance : 

MorphModule
MapSettingModule

### module.Init

Parametre : 
AUCUN
Retour :
AUCUN

Description :
Function qui lance le player Handler et qui gère les évènements suivant :

#### :PlayerAdded()

Va s'imbrique avec le CharactereAdded() juste en dessous.

Pour l'instant check juste si le compte du joueur n'est pas trop jeune.

#### :CharactereAdded()

Va faire utilisé le MorphModule