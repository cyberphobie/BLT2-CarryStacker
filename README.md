# BLT2 Carry-Stacker-Reloaded
# All Credits go to Lordmau5 for creating this mod!
Payday 2 BLT2 Mod

Have you ever thought  
*Man... I could get a hold of some more paintings on myself... But I can only carry one.*

**Well, wait no longer!**  
I hereby bring you a fully functional and customizable **Carry Stacker *(Reloaded)*** in a standalone version! 

***What can you do with it?***  
Well.. You can... Carry multiple bags at once...

***Is it restricted to anything?***  
**Yes!** *Let me fetch you the information from within the mod.*  

![Instructions](https://i.lordmau5.com/1447453991-328.png)  

***I want to go full nuts with this. Can I carry an infinite amount of bags somehow?***  
**Yes.**  
Just set the weight of the desired type to **0** and you're good to go :)

***Does this work in Multiplayer?***  
**Yes**, *in a restricted way.*  
If the **host** has the mod, he can use it fine.  
Vanilla clients won't be affected.  
Clients that have the mod can then use it.  
If a **client** has the mod, and the host **does NOT** have it, the client won't be able to use it.  

***When I'm hosting a game, do clients get notified that I am using the mod?***  
**Yes**, they do get notified about that.  
It's the same implementation as in *Keepers* or *Moveable Intimidated Cops*, for example.  
Thanks to TdlQ for the awesome code :)  

***The mod in action* (Youtube video)**  
[![The mod in action (click here for YT Video)](http://img.youtube.com/vi/3Jl-P5l-3Vk/0.jpg)](http://www.youtube.com/watch?v=3Jl-P5l-3Vk)  
*I know, I've used the PP trainer in this... But that's the only good way to debug things and to show off features real quick.*

# Download:  
http://download.paydaymods.com/download/latest/BLTCS_Reloaded

# Changelog:  
- **R6**: Fix for not being able to properly play the game online (WHO WOULD WANT TO DO SUCH A THING ANYWAY, AM I RIGHT GUYS?... guys...?)  

Also, revamped the config-system a bit. Old config is being deleted, so make sure to change your stuff again :)  
- **R5**: Fix for duplication. Also, it drops the bags with a proper delay now, as you see here:  
https://www.youtube.com/watch?v=InCfMRjuboc  
- **R4**: Rewrote Power-Throw implementation.  
It's not double-tap anymore, but rather holding the drop-key down.  
As long as you hold down the key, you will drop the bags.  
Upon releasing, you'll stop.  
- **R3**: Fixed crashes when the host doesn't have the mod, but the client does, and the client tries to pick up bags.  
- **R2**: Properly loading and saving the config now  
Added ability to sync the settings with clients, if you're the host. They are only temporary (for the current session) and don't overwrite your own.  
The host can change them mid-game and they get re-synced :)  
- **R1**: A fresh start...
