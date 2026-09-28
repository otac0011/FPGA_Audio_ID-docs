# FPGA Audio ID: design map

A clickable map of everything the FPGA Audio ID design does: a PDM MEMS microphone on a Digilent Cmod A7-35T
(Artix-7), filters in the FPGA logic that turn the mic's pulses into 16 kHz audio, an FFT spectrum engine, and a
MicroBlaze V soft processor that computes mel features and runs a small neural network to classify sounds as
speech, vehicle, machinery, alarm or background, twice a second.

View it at https://otac0011.github.io/FPGA_Audio_ID-docs/

This repo only hosts the page. It is generated from `docs/index.html` in the (private) design repository.
