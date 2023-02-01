# De-Esser

Steps to create De-Esser

1) Set up the JUCE project: Create a new JUCE project in the Projucer and configure it to build as a VST3 plugin.

2) Design the filter: The De-esser is a type of dynamic equalizer that reduces the level of sibilance (ess-like sounds) in vocals. You can implement it by designing a frequency-selective filter that only reduces the level of specific high frequency ranges where sibilance is typically found.

3) Implement the filter: Write the code to implement the filter in the JUCE project. Use JUCE's DSP module to handle audio processing, and apply the filter to the audio signal in the processBlock() method.

4) Add controls: Add knobs, sliders, or buttons to control the filter parameters such as the frequency range and the amount of reduction. You can use JUCE's AudioProcessorValueTreeState class to store and manage these values.

5) Test and refine: Test the plugin in your DAW, and refine the filter design as needed.
