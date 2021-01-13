# risset-beater

Towards an instrumentalization of Risset beats

For now we have:

* [beatsF0Plus4-GUI] and [beatsF0Plus4-GUI]: the goal here is to control the beating frequencies of some partials - namely, a fundamental + 4 partials. 
* [blitSaw]: a band-limited sawtooth oscilator. It is created dynamically, parameterized by Number of harmônicos and fundamental frequency. We can group some of these to create "sweeping partials", as pioneer Jean-Claude Risset did - with much more - in  "Computer Music: Why?" WERGO 2033-2, 1985.

We have a fundamental f0 + 4 partials f1, f2, f3, f4 each with a beating frequency (in Hz - beats per second). We also control the volume (yellow sliders) of each tone that generates each beating, decreasing the amplitude of the beating. Note that lower beating frequencies make the beating more perceivable as a pitch oscillation instead of a n amplitude oscillation.

(Other objects would be very welcome - more f1|beat pairs or more beating frequencies per partial, for example. The latter could be made by using [blitSaw]s or other band-limited waveforms for each partial...)

![](https://raw.githubusercontent.com/brizolara/risset-beater/main/risset-beater-help.png)
