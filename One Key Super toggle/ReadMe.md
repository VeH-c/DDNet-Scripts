A pair of Script-Binds that Toggles Super on & off with one key, providing you have already authenticated Rcon with the right privileges.
the ingame HUD element for Health + Ammo is hidden when Super is active for easy differentiating between the two modes. I use "i" here as the default bind.
Initiate with: exec SuperOff.cfg


Note About +toggle: in Config's/Script's +toggle is the equivalent to setting a value, so
+toggle cl_showhud_healthammo 1 0
cl_showhud_healthammo 0
are one & the same(in the case of Config's/Script's) as
1. there is no Key Held down time, it's executed instantly & just sets the command to the given value.
2. +toggle does not check the current value, it simply changes the values [VIA](https://www.merriam-webster.com/dictionary/via) the key press state, meaning the current value of cl_showhud_healthammo is meaningless.






  
