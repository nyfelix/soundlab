# Twelve SoundLab

This ist the root of SoundLab. It's the documentation of hardware and software, configuration, presets and experience of my home recording studio. Currently, the full setup is based on commercial or open source software. Maybe in future my own plugins might go here, too.

This repo organizes:
- My personal logbook, workflow and experience for song writing and production (this file)
- Templates for LogicPro X
- Channel strip presets
- Recording settings (and according experiments)

> :warning: **This is work in progress, content is not complete**



## Infrastructure

This is a list of hardware and software I use in my home studio.

### Studio Hardware
- Audio interface: Audient iD44
- Condenser microphone voice and acoustic instruments: Lewit LCT 440 Pure
- Condenser microphone voice: Electro Voice PL84
- Dynamic microphone acoustic instruments and amps: Shure SM57
- DAW Controller: iCon QCon pro G2
- Midi Controller (manly for synths and drums): AKAI MPK mini
- Headphones: Neumann studio headphones NDH20
- Headphones: Sennheiser HD555
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
- Various Guitar Effects (Overdrive, Chorus, Octaviator, Delay, Reverb), sometimes used for other purposes
- Vintage: Revox A77 tape machine

### Software
- DAW: Pro Logic X (latest)
- Instrument and Effects: Native Instruments Komplete 13 
- Audient iD Routing
- VE-500 Editor
- Tonebridge Guitar Effects
- Moog Model 15 Emulation
- Apple Voice Memos (very important if you have ideas in the car)

### Wiring in hard / software

Todo: Add schema here

## Production Workflow

This is my simple checklist for my production workflow including songwriting. I'm an amateur "I hide in the studio and do it all on my own" guy, That's why I include the songwriting/composition into my workflow. Quite often I will jump back from the production phase to the songwriting phase, if something does not work or if a "cool" verse turns out to be awful once listening to it after recording. Thus, what seems like a sequential workflow is more like a checklist where you can jump back and forth.

### Phase 1: Prepare a song (songwriting / composing)

1. Setting a theme
2. Find the harmonics and rhythm
3. Write the song

Here are some further thoughts about these steps:

1. **Setting a Theme**. As most artists out there I think a song needs a theme and build around it. Sometimes the theme is based on a phrase of lyrics, or something I want to express a thought with words such as "I want to say thank you to my brothers and sisters". But quite often the theme is based on music a cord progression or melody. Then of course to write the lyrics around it can be a hard task. Im most cases my ideas pop up when I'm just fooling around with my guitar or piano. Or I catch up some melody element in the radio I want to further develop. I started to look for new inspiration everywhere and once you found something, you have to catch and hold it. That's why I think it's important to always have a recording app near by. I have a rather long list of awfully sung ideas (I'm not a good singer)j or guitar samples with friends talking in the background. When I lack an idea I go through that list and usually find something to work with. No and then I also delete stuff I don't like after a while to cerate space for new ideas.
  
2. **Find the harmonics and rhythm**. I'm not a professional musician, so don't think its to to explain how to write a song. However, in my case this is a process that is not really controlled. Usually I sit with the guitar or the piano and try until I find a way to match words, rhythm, a basic melody and harmonics. Interesting enough, things turn out to be quite different if I approach a song with guitar than on the piano. In some rare cases I also started with electronic instruments (synth pads or drum machine). I try as long as I have found a verse and a chorus.

3. **Write the song**. Having a rough idea of verse and chorus I then start to figure out how many verses I need to tell the story. Usually, based on that consideration I choose the song pattern. Then it's time to write the full text and very often the option to add a transition to the song pattern helps me to either point out an important part of the main message that does not fit into to tag line or still say the sing that does not fit into the verse. I'm not sure if this is good practices, but it turned out to be helpful for me. 

At the end of these steps I usually have a clear concept of the song:
* pattern
* text
* basic idea of rhythm and speed
* harmonics
* some of the melody elements
* often a very clear idea of the vocals

In some cases I also have a clear idea of the instruments to be used during production. But I try not to restrict myself, playing with different sounds during production is a big part of the fun, I thing. And it's normal that I go into a project with a guitar solo in mind and later on find out it's going to be a melodica, an organ, or an 80ties synth.

### Phase 2: Production
These steps are inspired by [1]

1. Prepare the project in the DAW
2. Setting the rhythm (drums)
   Repeat 3, 4, and 5 for each track (analog or digital instruments):
3. Recording
4. Editing
5. Mixing
6. Arranging 
    * overall mixing and automation

Here are some further thoughts about these steps:

1. **Prepare the project in the DAW**: *ToDo: Explain and give the link to the templates*
   
2. **Setting the rhythm**: I'm not a drummer, so im my case the drums come mostly from an electronic/sampled source. I learnt the hard way that you can fix many things on a later production stage, but not rhythm and speed. That's why I first choose the beat section, even if I record a cajon or percussion myself later on. So, at least for music in my genres, this is the first final decision I do in the production process.
   
3. **Recording**: I play several instruments, but all of them at a very average level. So in the first place I try to set my arrangements in a level that does not demand more than I can handle and still sounds good. Still recoding - in my case - remains a time consuming process. In very project I learn more about where to put the mics, how to handle analog gear, and at what level the preamp should be. To collect my experience and continuously improve I started this project. Test and my current settings to start with can be found [below](#recording-settings). Also, because I'm not a perfect musician, I will always take enough takes to later have good options for editing. As a rule of thumbs.

### Phase 4: Mastering

### Phase 3: Release

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
1. Decided for LogicPro Sound or Native Instruments
2. Browse by style or instrument (don't forget to favour interesting sounds, that do not fit to the current project)
3. Find the right preset
4. Adjust the preset
5. If the new preset should be reused. Save as User Preset.

Use Kontakt 7 for best browsing in individual instruments and samples and Presets that are not stand alone synthesizers.
I use the favorite function (*), so I 'm loosing to much time with browsing and forgetting. Komplete Kontrol would allow to browse through all presets, but it's less clearly arranged and it does not open the standalone application to play with settings. Komplete Kontrol becomes interesting when you want to test combinations of instruments and effects. But usually I would to this in my DAW.

### Prioritylist for Deep Dive into Virutal Instruments

1. Find the right synth to create my own sounds
2. Learn more about vocoders
3. Learn more about drum machines
4. Learn more about samplers

### Reaktor Modular Synth

##

## Live settings

### Additional Infrastructure
* Roland RC-300 Loop station
* Beringer X1204 Mixer (analog)
* Apple Main Stage

## References

[1] Tommy Swindali, "Music Production 2022+ Edition", Fortune Publishing, 2022