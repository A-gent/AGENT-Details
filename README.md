# AGENT-Details
SourcePawn ConVar/Cvar/Alias Directive Repository For Cataloguing Notable Commands Within [AGENT]

<p align="center">

#### AGENT-ADMINISTRATION-DEV
  
|   COMMAND           |    VALUE         | DESCRIPTION  |
| ------------------- |:----------------:| ------------:|
| sm_refresh     |      N/A      | Refresh plugins (same as 'sm plugins refresh'). |
| sm_renew       |      N/A      | Unload and Refresh plugins (same as 'sm plugins unload_all; sm plugins refresh'). |
| sm_unload      |      N/A      | Unload all plugins (same as 'sm plugins unload_all'). |
| sm_round       |      N/A      | Executes 'mp_restartgame 1' to restart round. |
| sm_cheats      |      N/A      | Toggles sv_cheats. |
| sm_logit       |     "text"    | Logs specified text to 'sourcemod/logs/sm_logit.txt'. |
| sm_gametime    |      N/A      | Displays the GetGameTime() float. |
| sm_uptime      |      N/A      | Displays how long the server has been up. Maybe inaccurate if server hibernation is active. |
| sm_playtime    |      N/A      | Displays how long players have been playing on the server. |
| sm_changes     |      N/A      | Displays how many map changes have occurred. |
| sm_createent   |  "classname" | Creates and removes the entity classname, reports success. |
| sm_cv          | "cvar" "value" | Get/Set cvar value without the notify flag. |
| cv             | "cvar" "value"  | Get/Set cvar value without the notify flag. |
| sm_e           | "cmd" "args" | Executes a cheat command. |
| e              | "cmd" "args" | Executes a cheat command. |
| sm_ccmd        | "user" "cmd" "args" | Executes a client command on the target you specify. |
| sm_clientcmd   | "user" "cmd" "args" | Executes a client command on the target you specify. |
| sm_fcmd        | "user" "cmd" "args" | Executes a fake client command on the target you specify. |
| sm_fakecmd     | "user" "cmd" "args" | Executes a fake client command on the target you specify. |
| sm_servercmd   | "cmd"         | Executes a server command. |
| sm_scmd        | "cmd"         | Executes a server command. |
| sm_rngc        | "0-100" "cmd string" | Chance out of 100 to execute the command string, client command. |
| sm_rngf        | "0-100" "cmd string" | Chance out of 100 to execute the command string, fake client command. |
| sm_rngs        | "0-100" "cmd string" | Chance out of 100 to execute the command string, server command. |
| sm_views       |      N/A      | Saves your current position and eye angles. |
| sm_viewr       |      N/A      | Teleports you to the saved position and eye angles. |
| sm_pos         |      N/A      | Displays your position vector. |
| sm_aimpos      |      N/A      | Displays the position vector where your crosshair is aiming. |
| sm_setang      | "user" "vec ang" | Teleport someone to the x y z angles vector specified. Place ? to ignore an XYZ vector and use the targets current value. |
| sm_setpos      | "user" "vec pos" | Teleport someone to the x y z origin vector specified. Place ? to ignore an XYZ vector and use the targets current value. |
| sm_bringents   | "class" "distance 'Def. 50'" | Teleport specified entities by classname to around the player. e.g. sm_bringents weapon_rifle. |
| sm_tele        | "user" "xyz vec pos" | Teleport specified targets to aim location or to the x y z origin vector specified. Place ? to ignore an XYZ vector and use the targets current value. |
| sm_tel         | "vec pos" "vec ang" | Teleport yourself to the x y z vector specified. Place ? to ignore an XYZ vector and use the targets current value. |
| sm_range       |   "entity"    | Shows how far away an object is that you're aiming at, or optional arg to specify an entity index. |
| sm_near        |    "range"    | Lists all nearby entities within the specified range. Usage sm_near: [range]. |
| sm_dist        |      N/A      |  Enter twice to measure distance between the origins you stand on. |
| sm_distdir     |      N/A      | Get distance between you and end point of direction you are looking at (considering collision). |
| sm_distfloor   |      N/A      | Get distance between you and floor below you (considering collision). |
| sm_distroof    |      N/A      | Get distance between you and roof above your head (considering collision). |
| sm_size        |      N/A      | Get sizes (Width, Length, Height) of your player. |
| sm_sizee       |      N/A      | Get sizes (Width, Length, Height) of the entity you are looking at. |
| sm_del         |      N/A      | Deletes the entity your crosshair is over. |
| sm_dele        |    "entity"   | Deletes the entity you specify. |
| sm_delents     |    "class"    | Delete all the entities of a specific classname. |
| sm_ent         |      N/A      | Displays info about the entity your crosshair is over. |
| sm_ente        |    "entity"   | Displays info about the entity you specify. |
| sm_vertex      |    "entity"   | Displays vMaxs and vMins bounding box about the specified entity or aimed at entity. |
| sm_box         |    "entity"   | Displays a beam box around the specified entity or aimed at entity for 10 seconds. |
| sm_find        |    "class"    | List entity indexes from the given classname. |
| sm_findname    |  "targetname" | List entity indexes from a partial targetname. |
| sm_count       |      N/A      | Displays a list of all spawned entity classnames and count. Optional sm_count <classname>. |
| sm_modlist     |      N/A      | Saves a list of all the models used on the current map to 'sourcemod/logs/models_<MAPNAME>.txt'. |
| sm_collision   | are neat      |    $1 |
| sm_movetype    | are neat      |    $1 |
| sm_anim        | are neat      |    $1 |
| sm_weapons     | are neat      |    $1 |
| sm_lobby       | are neat      |    $1 |
| sm_ledge       | are neat      |    $1 |
| sm_spit        | are neat      |    $1 |
| sm_alloff      | are neat      |    $1 |
| sm_director    | are neat      |    $1 |
| sm_hold        | are neat      |    $1 |
| sm_halt        | are neat      |    $1 |
| sm_nb          | are neat      |    $1 |
| sm_nospawn     | are neat      |    $1 |
| sm_zspawnv     | are neat      |    $1 |
| sm_bots        | are neat      |    $1 |
| sm_slayall     | are neat      |    $1 |
| sm_slaycommon  | are neat      |    $1 |
| sm_slaywitches | are neat      |    $1 |
| sm_stopang     | are neat      |    $1 |
| sm_c           | are neat      |    $1 |
| sm_r           | are neat      |    $1 |
| sm_s           | are neat      |    $1 |
| sm_v           | are neat      |    $1 |
| sm_sc          | are neat      |    $1 |
  
</p>
