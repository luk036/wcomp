Motivation:

1. Why waveform comparison?
Pre-silicon Verification. 70% effort of a development cycle is spent on human inspection [1](1.md). Recently I noticed that the company Springsoft has a new product named "Verdi", which has a waveform comparison feature. According to the web site, the product already has quite a lot of customers.

2. What is the difficulty of waveform comparison?
Waveforms from different corners are difficult to be compared automatically. Before performing the point-to-point comparison, we need to performance a transformation in order to align two waveforms. Previously we proposed a transform method that utilizes the Wiener filter. However, it only partially solved the problem.

3. What is the key innovation?
In this project, we attempt to utilize the computer vision transformation techniques recently developed for waveform comparison.