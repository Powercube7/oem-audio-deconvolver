# oem-audio-deconvolver
Some HP models (featuring Bang & Olufsen audio) rely heavily on proprietary Windows software to correct the physical acoustic limitations of the laptop's hardware. When running Linux, the output is instead a flat, un-equalized signal, resulting in a degraded audio experience.

This personal project is an attempt at restoring the OEM sound signature natively in Linux without requiring its proprietary drivers by utilizing loopback capture in Windows combined with Fourier analysis with the main goals being: 
- the application of theoretical knowledge
- (hopefully) emulating a better experience on the consumer side
