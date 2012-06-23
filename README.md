n6-bidule-groups
================
Here you'll find some *hopefully* useful custom Bidule groups to use with Plogue Bidule. All groups are built using common Building Blocks (no external plugins, etc.) for easy reuse. 

The intention is that these Bidule groups can also be used as Building Blocks themselves.

These Bidule groups specifically work with http://www.plogue.com/products/bidule/. So you'll need a copy to run any of them.

To use these groups, cd to your Bidule groups directory and run: `git clone git://github.com/n6/n6-bidule-groups.git`

* OSX `~/Library/Application Support/Plogue/Bidule/groups`
* Windows `C:\Users\<username>\AppData\Roaming\Plogue\Bidule\groups`

On Bidule startup the new groups will be *automagically* recognized. 

NoiseSynth
==========
My attempt at nearly random noise generation. Two LFOs modify the group's parameters.

### NoiseSynth UI screenshot
![NoiseSynth UI screenshot](https://github.com/n6/n6-bidule-groups/raw/master/NoiseSynth/NoiseSynth.png)

### NoiseSynth Group Layout
![NoiseSynth Group Layout](https://github.com/n6/n6-bidule-groups/raw/master/NoiseSynth/NoiseSynthLayout.png)

ManualNoteSelect
================
Manually output a MIDI note using a drop down menu. Also uses Note_Octave_Select (from Hansje) and ManualNoteValueInput group. Great for drones. 

ManualNoteValueInput
====================
Manually output a MIDI note using a specific frequency. ManualNoteSelect relies on this group.  