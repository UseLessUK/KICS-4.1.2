# KICS 4.1.2
This is an updated [VoiceAttack](https://www.voiceattack.com/) profile for the [KICS](https://github.com/mwerle/KICS) Voice Pack for Elite Dangerous by Arflint

You'll need to grab the KICS profile from [here](https://github.com/mwerle/KICS) as you'll require the audio files, this VA profile doesn't have any included it's just the `vap` file for VA.

## Updated VA Profile
This updated version **requires** [bindED](https://github.com/alterNERDtive/bindED) in order to function. All the **Key Bindings** entries have been updated to support variable keys, like so;
```
Begin Text Compare : [edDeployHeatSink] Has Been Set
    Press variable key(s) [edDeployHeatSink] and hold for 0.05 seconds and release
Else
    Write [Red] 'Missing keybind for:' to log
    Write [Gray] '[Cooling - 02. Deploy Heat Sink]' to log
End Condition
```
## Notes
1. You will need to enable plugin support within VA.
	• Click the spanner (wrench) lower right of the VA main window, make teh General tab active and check (tick) `Enable Plugin Support` on the right and then click OK. You'll need to restart VA.
2. This VA profile will **not** work without [bindED](https://github.com/alterNERDtive/bindED) being installed as a plugin in VA
3. You'll need to edit the command `KICS.startup` and enable the keyboard layout line you wish to use for bindED, should you not wish to use the default of `en-us`.
