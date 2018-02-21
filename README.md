~~~Kaori Synth Readme~~~

*********************************
**** Version: 1.0            ****
**** Author: Justin Watts    ****
**** Class: ITEC 498         ****
*********************************



“Maybe there’s only a dark road up ahead, but you still have to
believe and keep going. Believe that the stars will light your
path, even a little bit. Come on… Let’s go on a journey.”
Kaori Miyazono - Your Lie in April




***Basic Operation***


~How to Play~

- Access Monosynth Application via the “Kaori Synth.exe” file within the “Kaori Synth” folder
- Play notes either through a MIDI controller or by selecting notes on the on-screen keyboard
- If using an external controller, please select the desired device from the “Device” dropdown menu
- Default devices for this synth are Oxygen 25 and Oxygen 49 MIDI controllers


~Wave Control~

- Select desired wave type from the “Wave Type” dropdown menu under “Wave Control”
- Default wave type is “Sawtooth”
- Use space bar or the “Toggle Sample Hold” button to cause the note to hold
- “Toggle Sample Hold” being on or off is indicated by the blue “Holding” LED
- Holding notes automatically is off by default


~Volume Control~

- Mapped to controller number 20 on MIDI channel 1
- Operated by slider C9 on Oxygen 25 MIDI input device
- Manually change using “Volume” slider
	- Moving the slider to the right raises the master volume
	- Moving the slider to the left lowers the master volume
- Default volume is 75



***Effects***


~Pitch Bend~

- Using the “Pitch Bend” knob under “Effects” will either raise or lower the pitch of a played note
- Mapped to controller number 1 on MIDI channel 1
- Operated by MOD C16 on Oxygen 25 MIDI input device
- Manually change using “Pitch Bend” dial under “Effects”
	- Turning the knob to the right raises the pitch
	- Turning the knob to the left lowers the pitch
- Default value is set to 0 for no pitch change


~Arpeggiator~

- Select desired arpeggiator from the “Arpeggiator” dropdown menu under “Effects”
- Hold a note on the MIDI controller to produce an arpeggiation of that note
- Mapped to controller number 22 on MIDI channel 1
- Operated by knob C5 on Oxygen 25 MIDI input device
- Manually change using the “Arpeggiator Speed” slider under “Effects”
	- Moving the slider upwards slows the arpeggiator
	- Moving the slider downwards speeds up the arpeggiator
- Switch “Arpeggiator” dropdown menu to “No Arpeggiator” to return to single note values
- Defaults to “No Arpeggiator” and a value of 360 for “Arpeggiator Speed”


~Repetitions~

- Select the desired number of repetitions, or echoes, for a played note by selecting a number from
  the “Amount of Repetitions” dropdown menu under “Effects”
- Once a number is selected, turn the “Repetition Timing” knob to the right in order to increase the
  time between each repetition
- Upon releasing a note the repetitions will follow, getting increasingly softer, simulating an echo
- Mapped to controller number 74 on MIDI channel 1
- Operated by knob C4 on Oxygen 25 MIDI input device
- Manually change using the “Repetition Timing” knob under “Effects”
	- Turning the knob to the right increases the time between repetitions
	- Turning the knob to the left decreases the time between repetitions
- Switch “Amount of Repetitions” dropdown menu to 0 to return to single note values
- Default number of repetitions is 0, and default value for time between repetitions is 0 milliseconds



***Octave Control***


~Octave Switcher~

- Select the desired octave range by either selecting the number of octaves to move up or down
  using the “Octave” dropdown menu under “Octave Control” or by using the “Octave Switcher” knob
- Selecting one of the “Down #” options will move the base octave down, and selecting one of the
  “Up #” options will move the base octave up
- The base octave can also be changed using the “Octave Switcher” knob under “Octave Control”
	- Turning the knob to the right raises the base octave
	- Turning the knob to the left lowers the base octave
- Switch “Octave” dropdown menu to “No Change” to return to the original base octave
- Default octave is set to “No Change”


~Octave Adder~

- Select the desired number of octaves to add by either selecting the number of octaves using the
  “Amount of Octaves” dropdown menu under “Octave Control” or by using the “Octave Addition” knob
- Selecting one of the negative options will add lower octaves, and selecting one of the positive
  options will add higher octaves
- The amount of octaves to add can also be changed using the “Octave Addition” knob under
  “Octave Control”
	- Turning the knob to the right adds higher octaves
	- Turning the knob to the left adds lower octaves
- Switch “Amount of Octaves” dropdown menu to 0 to return to the single base octave
- Default octave addition is set to 0



***Envelope***


~Attack~

- Using the “Attack” knob under “Envelope” will either increase or decrease a note’s attack time
- Upon playing a note, the attack time will determine how quickly the note reaches its full volume
- Mapped to controller number 71 on MIDI channel 1
- Operated by knob C1 on Oxygen 25 MIDI input device
- Manually change using the “Attack” knob under “Envelope”
	- Turning the knob to the right increases the attack time
	- Turning the knob to the left decreases the attack time
- Default attack time is 1 millisecond


~Decay~

- Using the “Decay” knob under “Envelope” will either increase or decrease a note’s decay time
- Upon releasing a note, the decay time will determine how quickly the note fades in volume
- Mapped to controller number 72 on MIDI channel 1
- Operated by knob C2 on Oxygen 25 MIDI input device
- Manually change using the “Decay” knob under “Envelope”
	- Turning the knob to the right increases the decay time
	- Turning the knob to the left decreases the decay time
- Default decay time is 100 milliseconds



~Release~

- Using the “Release” knob under “Envelope” will either increase or decrease a note’s release time
- Upon releasing a note, the release time will determine how long a note holds after being released
- Mapped to controller number 73 on MIDI channel 1
- Operated by knob C3 on Oxygen 25 MIDI input device
- Manually change using the “Release” knob under “Envelope”
	- Turning the knob to the right increases the release time
	- Turning the knob to the left decreases the release time
- Default release time is 350 milliseconds




***Distortion***


~Noise~

- Using the “Noise” knob under “Distortion” will either increase or decrease the amount of noise
  added to a note
- Should this knob be used, the synth will include white noise in conjunction with any played note
- Mapped to controller number 23 on MIDI channel 1
- Operated by knob C6 on Oxygen 25 MIDI input device
- Manually change using the “Noise” knob under “Distortion”
	- Turning the knob to the right increases the amount of noise added
	- Turning the knob to the left decreases the amount of noise added
- Default value is 0 for no noise


~Sampling Rate and Word Size~

- Using the “Sampling Rate” and “Word Size” knobs under “Distortion” will effect the integrity of the
  note being processed
- Should these knobs be used, the synth will distort the sound of any notes played
- Sampling rate is mapped to controller number 26 on MIDI channel 1
- Sampling rate is operated by knob C7 on Oxygen 25 MIDI input device
- Word size is mapped to controller number 27 on MIDI channel 1
- Word size is operated by knob C8 on Oxygen 25 MIDI input device
- Manually change using the “Sampling Rate” and “Word Size” knobs under “Distortion”
	- Turning the knobs to the right increases the integrity of the note
	- Turning the knobs to the left decreases the integrity of the note
- Default sampling rate value is 1 for complete sampling rate
- Default word size value is 23 for full word size



***Recording and Playback***


~Recording~

- Using the “Record” button under “Recording and Playback” will allow the user to record any played
  notes for up to one minute of time
- Upon hitting the “Record” button, everything played will be recorded until the button is pressed again
  or one minute has been reached, as indicated by the red “Recording” LED being on
- Mapped to controller number 118 on MIDI channel 1
- Operated by button C14 on Oxygen 25 MIDI input device
- Manually activate and deactivate using the “Record” button under “Recording and Playback”
- Default value is set to off


~Playback~

<Play>
- Using the “Play” button under “Recording and Playback” will allow the user to play back any
  recorded notes for up to one minute of time
- Mapped to controller number 117 on MIDI channel 1
- Operated by button C13 on Oxygen 25 MIDI input device
- Manually activate using the “Play” button under “Recording and Playback”
- Default value is set to off

<Stop>
- Using the “Stop” button under “Recording and Playback” will immediately stop any playback
- Mapped to controller number 116 on MIDI channel 1
- Operated by button C12 on Oxygen 25 MIDI input device
- Manually activate using the “Stop” button under “Recording and Playback”
- Default value is set to off

<Loop>
- Using the “Loop” button under “Recording and Playback” will allow the user to loop anything
  played using the “Play” button
- Upon hitting the “Loop” button, everything played will be looped until the button is pressed again,
  as indicated by the green “Looping” LED being on
- Mapped to controller number 113 on MIDI channel 1
- Operated by button C11 on Oxygen 25 MIDI input device
- Manually activate and deactivate using the “Loop” button under “Recording and Playback”
- Default value is set to off

<Playback Volume>
- Playback volume may be adjusted separately from the master volume of the synth using the
  “Playback Volume” slider under “Recording and Playback”
	- Moving the slider upwards raises the playback volume
	- Moving the slider downwards lowers the playback volume
- Default playback volume is 75



*******************************************************************************
