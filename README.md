# KICS 4.1.2
This is an updated [VoiceAttack](https://www.voiceattack.com/) profile for the Ripley Galactic [KICS](https://github.com/mwerle/KICS) Voice Pack for Elite Dangerous by Arflint

If you already have the Ripley Galactic KICS profile audio files installed then all you need to download and import, into VoiceAttack, is the .**vap** file.

If you **do not** have the Ripley Galactic KICS profile audio files installed then you should download and import, into VoiceAttack, the .**vax** file, this contains the audio files along with the VoiceAttack profile.

## Updated VA Profile
This updated version **requires** [bindED](https://github.com/alterNERDtive/bindED) in order to function. All the **Key Bindings** entries have been updated to support variable keys, like so;
```
Begin Text Compare : [edDeployHeatSink] Has Been Set
    Press variable key(s) [edDeployHeatSink] and hold for 0.05 seconds and release
Else
    Write [Red] 'Missing keybind for: (The key needs to be set in game)' to log
    Write [Gray] '[Cooling - 02. Deploy Heat Sink]' to log
End Condition
```

## ED:Odyssey
This profile has support for ED:Odyssey check out the **On Foot** category in the profile.

## 3rd Party Applications
The profile now has some options to start some 3rd party apps such as CMDRs Toolbox, Inara, EDSM, EDSY, Coriolis, Spansh and if you have them installed EDDiscovery and EDMC.

## Commands ~ Selection of available commands

See the Ripley Galactic [KICS](https://github.com/mwerle/KICS) page for commands. The ones shown here are either new to the profile or have been altered in some way.

### Additional Commands:

Current Game Mode

Disembark from the ship; Disembark from the SRV

Prepare for take off;prepare to take off;prep for departure *[modified to now optionally check for limpets/crew member]*

what cargo;chat cargo do I have

enter FSS;enter fss Mode

how much fuel do I have left; fuel level

### On Foot Commands: [Odyssey]

backpack consumables;backpack assets;backpack goods;backpack data;backpack transfer

open insight hub; close insight hubc

crouch;walk;sprint

hub back; hub close

hub codex

hub commander

hub contacts

hub engineer

hub fleet carrier

hub galnet news

hub navigation

hub powerplay

hub shuttle

hub squadrons

hub transactions

next weapon;previous weapon

open backpack;close backpack; show backpack

open comms; show comms; hide comms

throw grenade; grenade

toggle tool mode; tool Mode

battle stats

clear authority

flashlight on; flashlight off

genetic sampler

holster weapon

interact; use

open emote wheel

open item wheel

reload

secondary interact; alternative use

select primary weapon; select secondary weapon

select frag grenade; select emp grenade; select shield grenade

sheilds on; sheilds off

switch weapon

### Option Commands:

auto stop on; auto stop off

clear va log

crew check on; crew check off

honorific use on; honorific use off

jump count on; jump count off

limpet check on; limpet check off

scan after jump on; scna after jump off

silent mode on; silent mode off

system announce on; system announce off

va listening on; va listening off


# Notes
1. You will need to enable plugin support within VA.

	• Click the Spanner (Wrench) icon on the lower right of the VA main window, make the General tab active and check (tick) `Enable Plugin Support` on the right and then click OK. You'll need to restart VA.

2. This VA profile will **NOT** work without [bindED](https://github.com/alterNERDtive/bindED) being installed as a plugin in VoiceAttack. Also make sure you've setup keys for all the functions you wish to use in game, you will be shown an error if a keybind is missing (Red message) and the Category/Key that requires a keybind (Grey message).

3. You'll need to edit the command `KICS.startup` and enable the keyboard layout line you wish to use for bindED, should you not wish to use the default of `en-us`.
