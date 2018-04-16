# DSPFinalProject
Final Project

We aim to unravel the complexities of music recognition algorithms and learn how it works within the world of digital signal processing.  The scenario is as followed: a  song is initially played through a speaker, perhaps in a restaurant or bar, and we pull out our smartphones, open Shazam, and have the app perform the music recognition in seconds.  How does it work?

From a high level, the song initially is an analog signal, specifically a continuous pressure signal.  The phone captures the signal and samples it through a built in analog-to-digital converter.  The phone records the signal and saves it to memory as a series of bytes, which represent the signal in the time domain.  Then, it performs a discrete fourier transform and converts the signal to the frequency domain.  Finally, the magic when we analyze small chunks of the spectrum and begin to identify the peaks, obtaining a signature of the song, a process called fingerprinting.  The signature is then matched with a database of other signatures and outputs the corresponding soundtrack.
