# ExileSupplementalPlayerMarkers
Description: Modified Exile Client Files To Support Friendly Player Markers
Credits: ExileMod Team for their excellent work.
License: You are free to use this software and modify it without restriction other than that of the standard ExileMod licensce.
  Credit to the source is expected.
  
To install, save this file in a folder in a new folder 'ExileClient'

Open config.cpp
and change it to add a line as shown below
class CfgExileCustomCode 
{
	// [GRG] Custom Player Icons
	ExileClient_gui_hud_renderPartyESP = "ExileClient\ExileClient_gui_hud_renderPartyESP.sqf";
};
