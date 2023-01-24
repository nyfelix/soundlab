# Twelve SoundLab

This ist the root of SoundLab. It's the documentaiton of hardware and software, configuraitons, presets and experiance of my home recording studio. Currently, the full steup is based on commercial or open source souftware. Maybe in futere my own plugins might go here, too.

This repo organizes:
- Tempaltes
- Channel strip presets
- Recording settings (and accoring expereiments)



## Infrastructure

### Studio Hardware
- Audiointerface: Audient iD44
- Condensor microphone voice and acustic instruments: Lewit LCT 440 Pure
- Condensor microphone voice: Electro Voice PL84
- Dynamic microphone acutsitc instruments and amps: Shure SM57
- DAW Controler: iCon QCon pro G2
- Midi Controler (manly for synths and drums): AKAI MPK mini
- Headphones: Neumann studio headphones NDH20
- Headphones: Sennheisser HD555
- Various stands and cables

### Hardware Instrumets
- Piano: Roland DP990F
- Acusitc steel guitar: Martin Nazareth PA
- Acustic calssic concert guitar: Handcrafted
- Electric guitar: Fender Stratocaster US, palisander neck
- Guitar Amp: Harper SilvertubePlus
- Electric bass: Hofner
- Banjo: Deering "Goodtime"
- Ukulelele: 
- Meldoica: Hohner Sutdent32
- Various small percussion instruments

### Hardware Effect Devices
- Vocal: Boss VE-500
- Horsekick
- Various Guitar Effects (Overdirve, Chorus, Octaviator, Delay, Reverb), sometimes uesed for other purposes
- Vintage: Revox A77 tape machine

### Software
- DAW: Pro Logic X (latest)
- Instrument and Effects: Native Instruments Komplelte 13 
- Audient iD Routing
- VE-500 Editor
- Tonebridge Guatiar Effects
- Moog Model 15 Emulation
- Apple Voice Memos (very important if you have ideas in the car)

## Wireing in hard / software

Todo: Add schema here

## Recording settings

### Vocal recording

#### Concept

Situation
- Record a a level, where heavy postprocessing in the DAW is possible, without having strange frquencies and clipping effects.
- For the singer the monitor needs to be at louder level then recording

Solution
- Use a channel just for recording and add enoug gain to hear the voice on the monitor.
- To control the monitor thorugh the DAW controler for all recordings, I route the signal into a montor bus and create a bus channel.
- After recording multiple takes I select the best sections directely from the raw recording channel and bounce it to the editing channel.
- The edditing channel then might have minimal specific processing for better eddting (eg eq and comporessen)
- The eddited track will then be copied to the final produciton channel, so I can always compare the result with the minimal processed signal. 

#### Tests for recording

Since recording is the only process, that cannot be redone and the most crutial for good quality, I want to do a number of experiments to see at how the different mics and hardware settings affect the recorindg and how well the takes can be processsed in the DAW.

- Verify optimal input level of preamp (gain for monitor)
  - 24bit resolution
  - Average of -28db
  - Peak at -10db
  
- Hardware settings. Allways with same audio interface, preamp set as suggested above (from literature):
  - PL84 pure
  - PL84 with pop filter
  - LCT440 pure
  - LCT440 with manufacturer filter
  - LCT440 with pop filter 
  - LCT440 with VE-500 Pitch correction

#### Results
| Mic | Distance to Mic [cm] | Preamp Gain | Signal range [dB] | Peak [dB] | Comments
| --- | -------------------- | ----------- | ----------------- | --------- | --------
| LCT440 pure | 20 | 6 | [-24, -9] | -7.3 | Clear noises at start of sound and wihle whispering. String p and wind noises after production at whisptering. **Choose this setting, if high "agressive" frequencies needed**
| LCT440 with manufacturer filter | 14 | 6 | [-20, -9] | -7 | Better signal for whisper and soft singing smaller range close to -18. However, compressed sound without filter sounds clearer for soft voice. **Best for spoken recordings** too dull for singing.
| LCT440 with pop filter | 14 | 7 | [-24, -10] | -6.1 | Needs mor gain on preamp. Good qulaity for whispering, a bit more dull, or better less agressive when singing. Sonds like the middle between the two other LCT440 options. **Best for an over all smooth** 
| LCT440 with VE-500 Pitch correction ||||| Same settings above, but with VE-500 in the loop (input signal from Audient output4). Pitch correction creats at some point "autotune" like distortion which cannot be fixted. If you are not a perfect singer, I suggest not to used hardware pitch correction before recording. It proved to be a very good tool for the live setting, particularly when the guitar is hooked to it (see below section "Live settings")
| PL84 pure | 4 | 9 | [-25. -9] | -4.1 | PL84 has some dull singig voice compared to the LCT440 and needs a lot of preamping But it seems more tolerant for loud singing. Not so well suited for soft singing, but an option for the rock voice. **Only for life singing an option**
| PL84 with pop filter | 5 | 9 | [-30, -10 ]| -7.1|  Less wind noise with the popfilter, definitifely the better option for recording. Singing still somewhat dull, big range. Soft singing reamis week after production (needs extra compresseion and dynamic gain). **Opt for this config for a loud rock voice**

## Virtual Instruments

### Finding the Rights Sounds
Workflow:
1. Decided for LogicPro Sound or Native Intruments
2. Browse by style or instrument (don't forget to favour interesting sounds, that do not fit to the current project)
3. Find the right preset
4. Adjust the preset
5. If the new preset should be reused. Save as User Preset.

Use Kontakt 7 for best browsing in individual instruments and samples and Presets that are not stand alone synthesiziers.
I use the favourit function (*), so I 'm loosing to much time with browsing and forgetrting. Komplete Kontrol would allow to browse through all presets, but it's less clearly arranged and it does not open the standalone applicaiton to play with settings. Komplete Kontrol becomes interesting when you want to test combinations of intruments and effects. But usually I would to this in my DAW.

### Prioritylist for Deep Dive into Virutal Instruments

1. Find the right synth to create my own sounds
2. Learn more about vocoders
3. Learn more about drum machines
4. Learn more about samplers

### Reaktor Mdoular Synth



## Live settings

### Additional Infrastructure
* Roland RC-300 Loopsatation
* Beringer X1204 Mixer (analog)
* Apple Main Stage