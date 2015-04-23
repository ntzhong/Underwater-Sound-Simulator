# Underwater-Sound-Simulator
Made in Max/MSP

A filter that attempts to replicate what a sound would sound like if it were played underwater.

The resultant sound also depends on the distance between the source and the listener (which can be adjusted by the user)

This program can be controlled with an arduino. The slider can be used to adjut the distance from the sound source.

To use this program, upload a compatible sound file of your choice, and run the simulator.

The program essentially applies a low-pass filter (one that follows the basic principles of sound attenuation underwater) to the sound file, and applies reverb.

The fourier analysis and re-synthesis of the sound file was done using zsa.Descriptors, a plug-in for Max/MSP

Further details and instructions can be found in the patch.
