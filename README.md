# R3F-Crate-Selling
R3F-Crate-Selling 
drop the folder on your mpmission 
add this on your config.cpp
class CfgExileCustomCode
{
	///BOX VERKAUF
	ExileClient_gui_traderDialog_updateInventoryDropdown = "overrides\ExileClient_gui_traderDialog_updateInventoryDropdown.sqf";
	ExileClient_gui_wasteDumpDialog_show = "overrides\ExileClient_gui_wasteDumpDialog_show.sqf";
	ExileServer_system_trading_network_wasteDumpRequest = "overrides\ExileServer_system_trading_network_wasteDumpRequest.sqf";	
	
};
need change maybe extDB3 to extDB2 
"extDB3" callExtension format["1:TRADING:%1",_traderLog];
@ ExileServer_system_trading_network_wasteDumpRequest
@ line 117 
