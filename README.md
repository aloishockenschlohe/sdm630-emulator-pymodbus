# sdm630 emulator based on pymodnbus

In certain cases, it can be helpful or necessary to emulate an power meter - for example, if a solar installation is too far away from the actual power meter and a demand-oriented feed-in is to be realised. 

A very widely used power meter is the SDM630 from Eastron. This device is supported by quite a few manufacturers of inverters (e.g. Growatt).

The inverters request the consumption from the electricity meter at cyclical intervals via modbus and regulate the feed-in accordingly.

The programme reads a power consumption to be displayed cyclically from a file and makes the corresponding modbus registers available.

I know that the code is terrible. But it works very reliably and I hope that I can save other people a lot of research.

Feedback and improvements are reasonably welcome (I don't want to invest too much time in this project).
