# Akai Fire

Support script for Akai Fire controller.

## Transport

* **Play** - Start/Stop playback. Double click to move play cursor to start of song. You can configure the behavior on stop in the preferences.
* **Shift + Play** - Toggle repeat
* **Alt + Play** - Toggle Punch In
* **Alt + Shift + Play** - Toggle Punch Out
* **Record** - Start/Stop recording
* **Shift + Record** - Toggle launcher overdub
* **Alt + Record** - Creates a new clip on the selected track and slot, starts playback and enables overdub.
* **Pattern/Song** - Toggle metronome
* **Shift + Pattern/Song** - Toggle metronome ticks

## Knob Modes

* **Bank button**: Select the next Knob mode
* Use Knobs in combination with the Shift key for fine adjustments

### Channel Mode

Changes the parameters of the selected layer of the first instrument device on the channel. Has no effect if the device does not have layers. Especially useful, for drum devices.

* **Volume knob**: Change the layers volume
* **Pan knob**: Change the layers panorama
* **Filter knob**: Change the layers send 1
* **Resonance knob**: Change the layers send 2
* **Alt + Volume knob**: Change the layers send 3
* **Alt + Pan knob**: Change the layers send 4
* **Alt + Filter knob**: Change the layers send 5
* **Alt + Resonance knob**: Change the layers send 6

* **Alt + Select Knob**: Select the previous/next track. In addition you can press the knob while turning to switch between track pages (a page contains 16 tracks).

### Mixer Mode

Change parameters of the currently selected track. Combine with **Shift** for fine adjustments.

* **Volume knob**: Change the tracks volume
* **Pan knob**: Change the tracks panorama
* **Filter knob**: Change the tracks send 1
* **Resonance knob**: Change the tracks send 2
* **Alt + Volume knob**: Change the tracks send 3
* **Alt + Pan knob**: Change the tracks send 4
* **Alt + Filter knob**: Change the tracks send 5
* **Alt + Resonance knob**: Change the tracks send 6

* **Alt + Select Knob**: Select the previous/next track. In addition you can press the knob while turning to switch between track pages (a page contains 16 tracks).

### User 1 Mode

Change parameters of the currently selected device. Combine with **Shift** for fine adjustments.

* **Volume knob**: Change the 1st device parameter
* **Pan knob**: Change the 2nd device parameter
* **Filter knob**: Change the 3rd device parameter
* **Resonance knob**: Change the 4th device parameter
* **Alt + Volume knob**: Change the 5th device parameter
* **Alt + Pan knob**: Change the 6th device parameter
* **Alt + Filter knob**: Change the 7th device parameter
* **Alt + Resonance knob**: Change the 8th device parameter

* **Alt + Select Knob**: Select the previous/next device.
* **Shift + Alt + Select Knob**: Select the previous/next parameter page.

### User 2 Mode

Change user parameters. Combine with **Shift** for fine adjustments.

* **Volume knob**: Change the 1st user parameter
* **Pan knob**: Change the 2nd user parameter
* **Filter knob**: Change the 3rd user parameter
* **Resonance knob**: Change the 4th user parameter
* **Alt + Volume knob**: Change the 5th user parameter
* **Alt + Pan knob**: Change the 6th user parameter
* **Alt + Filter knob**: Change the 7th user parameter
* **Alt + Resonance knob**: Change the 8th user parameter

* **Alt + Select Knob**: Select the previous/next user parameter page (1-8).

## Pad Modes

The play and sequencer modes are selected with the **Step**, **Note** and **Drum** buttons.
All of the three buttons have two modes. Press the button again when selected to call up the second mode.
The buttons can also be used in combination with Shift and have then the following functions:

* **Shift + Step** - Toggle Accent on/off. If enabled, the velocity of the pads is ignored and the accent value, which can be configured in the settings, is used instead.
* **Shift + Note** - Toggle through Record Quantisation setting values
* **Alt + Note** - Quantise the selected clip
* **Shift + Perform** - Toggle the birdseye view of the session

Changing the tempo:

* **Shift + Drum** - Tap tempo
* **Drum + Select knob** - Change tempo in steps of 1
* **Drum + Select + Select knob** - Change tempo in steps of 10
* **Drum + Shift + Select knob** - Change tempo in steps of 0.01
* **Drum + Shift + Select + Select knob** - Change tempo in steps of 0.1

The following functions are available in all modes:

* **Pattern up/down**: Select the next/previous clip of the currently selected track
* **Alt + Pattern down**: Undo
* **Alt + Pattern up**: Redo

### Note Sequencer Mode

Press the **Step** button to activate. The STEP LED is lit orange.

* **Select Knob**: Move the note range up/down
* **Grid buttons**: Move to the previous/next page of the clip
* **Alt + Grid buttons**: Change the step resolution

* **Mute/Solo 1** (from top): Stop playing clip of selected track
* **Mute/Solo 2**: Toggle Mute of selected track
* **Mute/Solo 3**: Toggle Solo of selected track
* **Mute/Solo 4**: Toggle Record Arm of selected track

### Poly Sequencer Mode

Press the **Step** button twice to activate. The STEP LED is lit red.

The buttons behave as with Note Sequencer.
Play a chord in the lower part then enable steps in the upper chord which will be filled with the played chord.

### Play Mode

Press the **Note** button to activate. The NOTE LED is lit orange.

* **Select Knob**: Move the note range one octave up/down
* **Grid buttons**: Change the Scale
* **Shift + Grid buttons**: Change the Scale Base key
* **Alt + Grid buttons**: Change the Scale Layout
* **Shift + Alt + Grid buttons**: Toggle Chromatic / In Scale
* **Mute/Solo 1-4**: Same as in Note Sequencer mode

### Piano Mode

Press the **Note** button twice to activate. The NOTE LED is lit red.
The grid buttons form a piano style keyboard. The *black keys* are in the color of the selected track.
The functions are the same as described for the Play mode but the scale settings do not apply.

### Drum 4 Sequencer Mode

Press the **Drum** button to activate. The DRUM LED is lit orange.

* **Select Knob**: Move the note range up/down
* **Grid buttons**: Move to the previous/next page of the clip
* **Alt + Grid buttons**: Change the step resolution
* **Mute/Solo 1-4**: Mute the drum sound of the row
* **Shift + Mute/Solo 1-4**: Solo the drum sound of the row

### Drum 64 Mode

Press the **Drum** button twice to activate. The DRUM LED is lit red.

64 drum sounds can be played.

* **Select Knob**: -
* **Grid buttons**: -
* **Mute/Solo 1-4**: -

### Session Mode

Press the **Perform** button to activate. The PERFORM LED is lit orange.

* **Select Knob**: Scroll to the previous/next scene. In addition you can press the knob while turning to switch between scene pages (a page contains 4 scenes).
* **Grid buttons**: Select the previous/next page of the track bank
* **Mute/Solo 1-4**: Start Scene 1-4; the LED is lit if the scene is selected
* **Alt + Mute/Solo 1-4**: Stop all playing clips

Use **Shift + Perform** to toggle the birdseye view of the session. In this view a pad represents a block of 16x4 tracks/clips. Press a pad to move the view to that range.

### Mix Mode

Press the **Perform** button twice to activate. The PERFORM LED is lit red.

* **Select Knob**: Select the previous/next track. In addition you can press the knob while turning to switch between track pages (a page contains 16 tracks).
* **Grid buttons**: Select the previous/next page of the track bank

* **Mute/Solo 1** (from top): -
* **Mute/Solo 2**: Turn off mute on all tracks; the LED is lit red if there is at least one muted track
* **Mute/Solo 3**: Turn off solo on all tracks; the LED is lit green if there is at least one soloed track
* **Mute/Solo 4**: -

### Shift Mode

If you press the Shift button (and keep it pressed) the grid changes to the Shift mode.

In the first 2 4x4 blocks the note *repeat settings* can be configured:

* The left/top button dis-/enables note repeat
* The buttons 3 and 4 in the top row select the arpeggiator modes
* All other buttons in the first block select the number of octaves
* The first to columns in the second block select the period length
* The remaining two columns in the second block select the note length

With the bottom row of the 3rd and 4th block the length of new clips are selected (which can be created with Alt+Record).

The three buttons in the other right corner create new Instrument, Audio and Effect tracks.

The Mute/Solo buttons have the following functions:

* **Mute/Solo 1** (from top): Undo
* **Mute/Solo 2**: Redo
* **Mute/Solo 3**: Quantize
* **Mute/Solo 4**: -

### Browser Mode

You can use the browser to add devices, switch presets and select sounds for the drum machine.

You can activate the browser in different ways, depending on the use-case:

* **Browser**: Activates the browser mode to exchange the currently selected device or select a different preset for the device.
* **Shift + Browser**: Activates the browser mode to insert a device *before* the currently selected one.
* **Alt + Browser**: Activates the browser mode to insert a device *after* the currently selected one.
* **Browser + Pad**: If the drum sequencer is active and the Bitwig drum machine is loaded in the selected track you can exchange the sound of one of the drum machine pads by keeping the browser button pressed and pressing any of the grid pads. The sound of the row which contains the pressed pad will be exchanged.

The browser is used in the same way no matter how you opened it:

**Knobs 1-4**: Change the filter value of the respective filter column
**Alt + Knobs 1-3**: dito, for column 5-7
**Select Knob**: Choose a new result item. If you keep the knob pressed while turning the knob you switch sounds in steps of 3.
**Grid left/right**: Change the browser pane (Devices, Presets, ...)

To close the browser and confirm the selection press either the select knob or the browser button. To discard the selection press **Alt + Browser**.