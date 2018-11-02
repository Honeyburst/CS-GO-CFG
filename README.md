# CS-GO-CFG

//VIDEO
fps_max "999"
net_graph "1"
net_graphproportionalfont "0"
net_graphpos "1"
net_graphheight "55"
r_dynamic "0"
r_drawtracers_firstperson "0"
mat_monitorgamma "1.65"


//RADAR & HUD SETTINGS
cl_radar_always_centered "0"
cl_radar_scale "0.3"
cl_hud_radar_scale "1.15"
cl_radar_icon_scale_min "1"
cl_radar_rotate "1"
cl_radar_square_with_scoreboard "1"
cl_radar_rotate "0"
cl_radar_square_with_scoreboard "0"
cl_hud_playercount_showcount "1"
cl_hud_playercount_pos "0"


//SOUND
voice_scale "0.4"
snd_musicvolume "0"


//VIEWMODEL
viewmodel_presetpos "3"
cl_righthand "1"


//MOUSE
sensitivity "1.3"
zoom_sensitivity_ratio_mouse "1.0"
m_rawinput "1"
m_pitch "0.022"
m_customaccel "0"
m_mouseaccel1 "0"
m_mouseaccel2 "0"


//CROSSHAIR
cl_crosshairalpha 255
cl_crosshaircolor 5
cl_crosshaircolor_r 255
cl_crosshaircolor_g 0
cl_crosshaircolor_b 255
cl_crosshairdot 0
cl_crosshairgap -2
cl_crosshairsize 2
cl_crosshairstyle 4
cl_crosshairusealpha 1
cl_crosshairthickness 1
cl_crosshair_drawoutline 0
bind "MWHEELUP" "cl_Crosshairsize 999;  cl_crosshair_drawoutline 0; cl_crosshairdot 0"
bind "MWHEELDOWN" "cl_Crosshairsize 2;  cl_crosshair_drawoutline 0; cl_crosshairdot 0; cl_crosshairthickness 1; cl_crosshairgap -2; cl_crosshairstyle 4; cl_crosshairusealpha 1"


//BUYSCRIPT
bind "b" "buymenu"
bind "INS" "buy vest"
bind "HOME" "buy vesthelm"
bind "PGUP" "buy defuser"
bind "DEL" "buy m4a1; buy ak47"
bind "END" "buy p250"
bind "PGDN" "buy mp9; buy mac10"

bind "leftarrow" "buy incgrenade; buy molotov"
bind "uparrow" "buy smokegrenade"
bind "rightarrow" "buy hegrenade"
bind "downarrow" "buy flashbang"


//BINDS
alias "+jumpthrow" "+jump;-attack"
alias "-jumpthrow" "-jump"
bind "c" "+jumpthrow"

bind "w" "+forward"
bind "a" "+moveleft"
bind "s" "+back"
bind "d" "+moveright"
bind "e" "+reload"
bind "r" "+use"
bind "f" "+lookatweapon"
bind "g" "drop"
bind "m" "teammenu"
bind "q" "lastinv"
bind "t" "+spray_menu"
bind "y" "messagemode"
bind "u" "messagemode2"
bind "i" "holdpos"
bind "o" "roger"
bind "p" "negative"


bind "ALT" "noclip"

bind "MOUSE1" "+attack"
bind "MOUSE4" "+attack2"
bind "MOUSE2" "+jump"
bind "MOUSE3" "+voicerecord"

bind "SHIFT" "+duck"
bind "SPACE" "+speed"

bind "TAB" "+showscores"


bind "CTRL" "use weapon_knife; use weapon_smokegrenade"
bind "n" "use weapon_knife; use weapon_flashbang"
bind "x" "use weapon_knife; use weapon_hegrenade"
bind "capslock" "use weapon_molotov; use_weapon_incgrenade"
bind "z" "r_cleardecals"


//MISC
developer "0"
con_enable "1"
con_filter_text "Damage " // highlight damage in console
cl_autohelp "1"
bind "k" "host_framerate 0.05"
bind "l" "host_framerate 0"

host_writeconfig
