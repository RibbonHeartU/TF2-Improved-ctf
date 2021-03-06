# TF2-Improved-ctf (Updated 5/13/20)
### Version b3.3
Tired of needing to defend an intel for 60 second whole seconds before it returns? Do you know how many scouts can throw their bodies at it in that time? Improved CTF is here to help

## What does it do?
Allows players of the same team (or opposite teams in Special Delivery) to stand within a visualized capture radius of a flag to speed up the return time. This capture speed is impacted by number of players within the flag's radius along with vanilla methods of increasing capture rate (Scout and The Pain Train). Admins can also modify the default flag timer and more to suit their server's preference.

## Installation
This plugin requires Sourcemod and only works with Team Fortress 2

Place the included .SMX file into your server's `tf/addons/sourcemod/plugins` folder. On server or plugin startup, "Improved CTF enabled" should print to your server's console.

## Customization
Improved CTF includes several Cvars to help you make your gameplay just right.
```
sm_ictf_version - Prints the installed version of Improved CTF
sm_ictf_enable - Set to 0 to disable ICTF. Set to 1 to enable. (Default: 1)
sm_ictf_flag_time - Sets the initial time, in seconds, until the flag is returned. (Default: 30)
sm_ictf_cap_multiplier - Determines how much capping players effect the return time, as a decimal representing percentage. (Default: 0.6)
sm_ictf_cap_radius - Determines the distance, in hammer units, from the flag players can return it. Changes the ring visual to match. (Default: 100.0)
sm_ictf_hud_text - Enables/disables on-screen text for a flag's capture rate (Default: 1)
```

## Planned features
- Wider gamemode support
- Custom weapon capture rate support
