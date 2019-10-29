
postool mod for minetest
============

Adds configurable HUD elements for current: position (node and block) and time
If advtrains is installed, it can also display railway time.
Use chat command /postool to invoke formspec to toggle elements and position.

# Comming
The actual PosTool that will show graphically where the borders of current block are.

# Settings

Settings with default values:
```
# HUD offsets in screen percentage
postool.hud.offsetx				0.8
postool.hud.offsety				0.95
# how to seperate
# x, y and z values
postool.hud.posseperator		' | '
# titles in HUD and formspec
postool.hud.titletrain			'Railway Time: '
postool.hud.titletime			'Time: '
postool.hud.titlenode			'Node: '
postool.hud.titleblock			'Block: '
# value shown in HUD when
# advtrains is not enabled
postool.hud.titletrainna		'advtrains not enabled'
# main HUD switch
postool.hud.defaultshowmain		false (0/1)
# which items to initially show
postool.hud.defaultshowtrain	false (0/1)
postool.hud.defaultshowtime		false (0/1)
postool.hud.defaultshownode		true (0/1)
postool.hud.defaultshowblock	true (0/1)
# wait at least this long
# before updating HUD (seconds)
postool.hud.minupdateinterval	2

# Thanks
This mod was strongly inspired by [poshud] https://github.com/orwell96/poshud
Some techniques I borrowed from [missions] https://github.com/thomasrudin-mt/missions
Thanks also to the users of pandorabox.io for feedback and inspiration to actually
write this mod.
(If you feel I should include you by name, just submit a PR)
