## The hp141S/8553L/8552A Spectrum Analyzer

Repository for research and development with the Hewlett-Packard 141S Spectrum Analyzer, 8553L RF Section and 8552A IF Section.

![image](/img/141s-front.jpg)

I created this unit from two separate 141S units that each had their own problem such that they would not run in-themselbes. One had a burned-out power plug and the other a damaged CRT such that the internal storage capabilities were non-functional. With the addition of a whisper-quiet, externally-powered DC fan, this machine is in a state of perfection while being retrocorrect and _without_ bothersome noise.

### Background

Spectrum analysis provides a rapid means of evaluating the performance of power and communications systems; the spectrum analyzer is useful for monitoring, as well as testing and alignment. Important measurements such as distortion, percent amplitude modulation, carrier, and sideband suppression carrier and pilot levels, and calibration of FM deviation by the carrier null technique are easily made. The Model 141S/8553L/8552A Spectrum Analyzer provides high-resolution coverage from 1 kHz to 110 MHz, a range covering baseband, communications broadcast, as wall as navigation systems and the common Intermediate Frequencies (IFs). All functions are calibrated: Scan widths from 200 Hz for modulation and stability analysis to 100 MHz for monitoring out-of-band signals such as carrier distortion.

The analyzer provides three calibrated scan modes; preset scan, selectable `PER DIVISION` can and `ZERO` scan. Present scan displays essentially the entire swept frequency range of the analyzer on a single scale. You can view the broadband effects of circuit adjustments and refinements as they are made. The `FREQUENCY` tuning knob moves the dial pointer on the frequency dial and a corresponding frequency marker on the CRT display. Each response can be identified by reading frequency directly from the calibrated CRT or by tuning the frequency marker to the signal and reading the frequency dial.

The 8553L/8552A Spectrum Analyzer has fully calibrated swept coverage from 1 kHz to 110 MHz. This single instrument can be used over many decades of frequency to examine audio spectra, baseband modulation, system IFs, and modulated RF carriers into the VHF region. System performance tests for absolute levels of power, distortion, or spurious radiation are easy to perform using this analyzer. New features such as absolute amplitude calibration are made possible by flat frequency response and highly stable instrument gain.

### Unit History

For the past years, I had been working with a Hewlett-Packard 141T to perform circuital analysis of the different ideas I would contemplate for wireless power.

![141T](/img/141T.jpg)

With the 8553B RF Section as most, if not all of my models, operated between 400 kHz and 90 MHz. I was able to obtain quite a bit of focus on this work beginning 2020, but after languishing indoors during the pandemic lockdowns sometime in 2021, I found an old journal publication on eBay that had this image on its cover.

![HPJ-A68](/img/HPJ-A68.jpg)

It is a 141S with 8553L RF Section and 8552A IF Section from April 1968, when it was first released. It shows the newly-introduced Spectrum Analyzer with a 8601A Sweeper/Generator that is generating a sweep through a low-pass filter displaying its characteristics across the band. Reflecting-back on the event, I'm not sure if it was the tracking feature or the fact that the machines were photographed outside - where I was forbidded to go at the time - but I decided to switch my foundation equipment to this model.

### The Chase

Obtaining machines such as these are not an easy task and even if they are found, they are usually worse for wear, given their age and uncertanly who either kept them in a clean place or neglected them entirely, leaving them to rust. So a bit of luck and prayer always helps; including a plan to purchase at least two complete units - _complete_ meaning a mainframe and plugins, multiples where possible. As this machine (more the 141T than the 141S) was quite popular at the time, there were a lot of sources to buy. The 141S was difficult but I found two sellers; one sold me this one:

![1-141S](/img/1-141S.jpg)

And this one, where I had found using an image search and was lucky the guy still had it.

![2-141S](/img/2-141S.jpg)

With these exact plugins.

![8553-8552](/img/8553-8552.jpg)

When the first one arrived, I discovered it was packed poorly and had been dropped enroute, where the plugins had pressed themselves into the side of the mainframe closest to the CRT, resuling in this kind of damage.

![bend](/img/bend.jpg)

The other arrived safely but had some kind of electrical incident and the 120-240V input was blackened.

![smoky-filter](/img/smoky-filter.jpg)

It had been repaired so it probably worked, but I wasn't willing to take the risk.

![weld-cap](/img/141S-weld-cap.jpg)

I cleaned the damaged one to see if it could be simply straightened and brought into service. Once the incorrect plugins were removed, the correct ones would not slide-in, the bend was too severe. So I took it apart and it was used in this condition for six months.

![apart-01](/restoration/apart-01.jpg)

Another issue was the condition of the CRT storage driver, where one had decaying plastic adjustments and this was the unit with the good CRT storage. At one point, the dichotomy of functionality verses dishevelment was striking - had I entered a philosophical repair procedure? 

![board-2](/restoration/board-2.jpg)

Given the number of wires, I didn't want to make the mistake of mis-wiring on essembly, so I created two diagrams for the high-voltage board connections

![00141-66512](/restoration/00141-66512.png)

And one for the storage driver card

![00141-66510](/restoration/00141-66510.png)

### Documentation

The Display Section 00141-90905, can be found [here](/doc/00141-90905.pdf).
