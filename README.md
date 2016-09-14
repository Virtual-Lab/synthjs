# synthjs

js-library for building a web-based synthesizer

Used for sonification of the diagrams in the project "Sound-Colour-Space"

Builds up a gui inside an element with id="synth", 
or if not present the body


To initialize:

Synth.init();

To use a synth:
var sound = new Sound(freq); // optional preset: frequency

sound.play(220, 2); // play two seconds with frequency 220;



