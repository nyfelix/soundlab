# Recording settings

## Vocal recording

### Concept

Situation
- Record a a level, where heavy postprocessing in the DAW is possible, without having strange frequencies and clipping effects.
- For the singer the monitor needs to be at louder level then recording

Solution
- Use a channel just for recording and add enough gain to hear the voice on the monitor.
- To control the monitor thorough the DAW controller for all recordings, I route the signal into a monitor bus and create a bus channel.
- After recording multiple takes I select the best sections directly from the raw recording channel and bounce it to the editing channel.
- The editing channel then might have minimal specific processing for better editing (e.g. eq and compression)
- The eddied track will then be copied to the final production channel, so I can always compare the result with the minimal processed signal. 

### Preamp settings
During record test I figured out, that the best preamp gain for the instruments/vocals in relation to the pickup location is very important. Here's a good video that explains how to find a good preamp setting: https://www.youtube.com/watch?v=PiCQ-2Umuc0
Basically it's all about looking at the signal and listening for noise. And it's ok to use additional gain in the DAW.

### Tests for recording

Since recording is the only process, that cannot be redone and the most crucial for good quality, I want to do a number of experiments to see at how the different mics and hardware settings affect the recording and how well the takes can be processed in the DAW.

- Verify optimal input level of preamp (gain for monitor)
  - 24bit resolution
  - Average of -28db
  - Peak at -10db
  
- Hardware settings. Always with same audio interface, preamp set as suggested above (from literature):
  - PL84 pure
  - PL84 with pop filter
  - LCT440 pure
  - LCT440 with manufacturer filter
  - LCT440 with pop filter 
  - LCT440 with VE-500 Pitch correction

### Results
| Mic | Distance to Mic [cm] | Preamp Gain | Signal range [dB] | Peak [dB] | Comments
| --- | -------------------- | ----------- | ----------------- | --------- | --------
| LCT440 pure | 20 | 6 | [-24, -9] | -7.3 | Clear noises at start of sound and while whispering. String p and wind noises after production at whispering. **Choose this setting, if high "aggressive" frequencies needed**
| LCT440 with manufacturer filter | 14 | 6 | [-20, -9] | -7 | Better signal for whisper and soft singing smaller range close to -18. However, compressed sound without filter sounds clearer for soft voice. **Best for spoken recordings** too dull for singing.
| LCT440 with pop filter | 14 | 7 | [-24, -10] | -6.1 | Needs mor gain on preamp. Good quality for whispering, a bit more dull, or better less aggressive when singing. Sounds like the middle between the two other LCT440 options. **Best for an over all smooth** 
| LCT440 with VE-500 Pitch correction ||||| Same settings above, but with VE-500 in the loop (input signal from Audient output4). Pitch correction creates at some point "autotune" like distortion which cannot be fixed. If you are not a perfect singer, I suggest not to used hardware pitch correction before recording. It proved to be a very good tool for the live setting, particularly when the guitar is hooked to it (see below section "Live settings")
| PL84 pure | 4 | 9 | [-25. -9] | -4.1 | PL84 has some dull singing voice compared to the LCT440 and needs a lot of preamping But it seems more tolerant for loud singing. Not so well suited for soft singing, but an option for the rock voice. **Only for life singing an option**
| PL84 with pop filter | 5 | 9 | [-30, -10 ]| -7.1|  Less wind noise with the pop filter, definitively the better option for recording. Singing still somewhat dull, big range. Soft singing remains week after production (needs extra compression and dynamic gain). **Opt for this config for a loud rock voice**
