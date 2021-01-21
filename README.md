![badge-OS](https://img.shields.io/badge/stage-under%20progress-brightgreen)

Support this project and keep always updated by [following on github](https://github.com/dpscience?tab=followers).

![badge-followers](https://img.shields.io/github/followers/dpscience?style=social)
![badge-stars](https://img.shields.io/github/stars/dpscience/deepIRF?style=social)
![badge-forks](https://img.shields.io/github/forks/dpscience/deepIRF?style=social)

# deepIRF

![badge-language](https://img.shields.io/badge/language-Python-blue)

Copyright (c) 2021 Danny Petschke (danny.petschke@uni-wuerzburg.de). All rights reserved.<br>

<b>deepIRF</b> - A deep learning approach for reverse-broadening the instrumental response (IRF) in lifetime spectra. 

## ``preliminary results``

### Goal ...

Are we able to correct for the timing uncertainties inherently produced by the photomultiplier tubes?

### Principle ...

* 1 Mio. pulse-pairs recorded from an isotope 60-Co have been stored along with the obtained timing difference, i.e. the PMT uncertainty between them 
* 70 % of the pulse-pairs have been used for training the model
* subsequently, 30 % of the pulse-pairs have been used to test the trained model
* the results indicate that in principle deep learning can significantly reduce the uncertainty originating from the PMTs 
* see figure: blue curve = initial data, red curve = deepIRF-corrected initial data

![preliminary results](/preliminary%20results/preliminary%20results%20on%2060-Co.png)
