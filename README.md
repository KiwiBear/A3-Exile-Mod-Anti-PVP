# A3 Exile Mod Anti PVP
Remove PVP damage for PVE server.

# Install
Extract Exile.Mapname.pbo and copy **Scripts** folder to Exile.Mapname folder.
Like this :
    Exile.Altis\Scripts

Add "**ExileClient_object_player_event_onHandleDamage = "Scripts\AntiPVP\ExileClient_object_player_event_onHandleDamage.sqf"**" to CfgExileCustomCode block of config.cpp file.
Like this :
    class CfgExileCustomCode 
    {
    	ExileClient_object_player_event_onHandleDamage = "Scripts\AntiPVP\ExileClient_object_player_event_onHandleDamage.sqf";
    };

Repack mission file to PBO and upload to server. done.