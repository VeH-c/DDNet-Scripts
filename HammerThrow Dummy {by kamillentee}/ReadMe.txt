Bind to HammerThrow dummy to a certain direction without freezing it before

First you need to choose whether you want to throw the dummy to the right or to the left. You do this by binding bind x exec activate_dummy_mover.cfg and pressing x. The next pressing of either a or d will execute onright.cfg or onleft.cfg.
If you are HammerFlying release mouse1 and use mouse2 to continue with the HammerFly until you want to throw your dummy.
Now you can throw the dummy to the specified direction and hammer it , pressing mouse1 now for hammer does multiple things it immediately switches to the dummy while holding +right/+left and you get hit with the hammer of the main tee via DeepFly.
That will work exactly one time and then it will rebind deepfly and unbind HookDeepFly. Repeat by pressing x.

Explanations why its done this way:
+right/+left is temporary binded on mouse1 because on dummy switch a/d would need to be repressed to work again (which causes the tee to loose momentum)
activate_dummy_move.cfg is binding dummy HammerFly on mouse2 because there is a bug that causes a delay for a/d movement when mouse1 is still pressed. It will work without this workaround if you don't DeepHammerFly before (e.g. on ground)
DeepFly is turned on at the end because most of the time it's needed afterwards.
it is possible to +toggle the dummy so you can return very fast to the main tee, but keep in mind that rebinding a key that is held with a +toggle command always causes bugs
They are bugs like DeepFly delay but only for one tee, when switching either direction of movement or the used tee it works. I have no idea why.


To initiate: exec "show_others_on.cfg"  Then use X in-game to toggle it on & off.

 Author: kamillentee // https://forum.ddnet.tw/memberlist.php?mode=viewprofile&u=208

note: Copy&Pasted, please direct questions & comments for this to the author
