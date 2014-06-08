# Web Audio SPectrogram

This is a web audio-based spectrogram written using
[Polymer](http://polymer-project.org).

![Screenshot](screenshot.png)

Features:

- Toggle between logarithmic and linear scales.
- FFT window size.
- Frequency axis labels and ticks.

TODO: 

- Also allows the spectrogram to be paused and resumed.
- Configurable color map (correlating to amplitude).
- Load audio files.
- Zoom into pieces of the spectrogram for more detail.
- Detailed analysis mode that is sample accurate but not real time.
- Custom FFT with a bigger window.



# The API

Simplest possible version:

    <g-spectrogram/>

Enable controls:

    <g-spectrogram controls>
    </g-spectrogram>

Turn on log scale, enable frequency labels and show 10 ticks.

    <g-spectrogram log labels ticks="10">
    </g-spectrogram>


# Relevant links

- http://taps.cs.princeton.edu/
- http://isse.sourceforge.net/

