# VL.SharpNoise
SharpNoise Wrapper for VVVV Gamma

SharpNoise is a port of Jason Bevins' libNoise to C#.

Libnoise is a portable C++  library from the 2000´s , an old relic of noise programming that runs in the CPU.
Is used to generate coherent noise, a type of smoothly-changing noise. 
Coherent noise is often used by graphics programmers to generate natural-looking textures, planetary terrain, and other things.

In libnoise, coherent-noise generators are encapsulated in classes called noise modules. There are many different types of noise modules. Some noise modules can combine or modify the outputs of other noise modules in various ways; you can join these modules together to generate very complex coherent noise.

This port to Gamma brings the old libray to a new vision, using new c# techniques that allows to edit Noise maps in realtime.
For High resolution maps there are few techniques that reduce the CPU load bringing the possibility of export in very short times,
and manipulate them.
