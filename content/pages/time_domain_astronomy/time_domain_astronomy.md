title: Time Domain Astronomy
image: {filename}/../../images/tess_lc.png
status: hidden
slug: time_domain

<!-- 'Time Domain Astronomy' is the observational side of research, and data analysis -->
<!-- 'Extragalactic Astrophysics' is the theory/physics side (SMBHs and SNe) -->
<!-- 'TESS' is the functional stuff -->

##[Back to Research Overview]({filename}../Research/Research.md)##

## Precovery of transients by TESS

See my  [database of transients observed by TESS](https://tess.mit.edu/public/tesstransients/).


Because TESS continuously monitors a large field of view, it observes many astrophysical transients before they are discovered from the ground.  This opens open many opportunities, for example,  measuring the time time of first light of supernova explosions.

There have been over 4,000 transients observed by TESS in its first 4 years of operations.  I am maintaining a [website](https://tess.mit.edu/public/tesstransients/) that shows light curves of these transients.  The light curves are from a custom pipeline built on top of [ISIS](https://ui.adsabs.harvard.edu/abs/1999ascl.soft09003A/abstract) difference imaging.

If you see something that strikes your interest, let me know and I will be happy to share the data (michael.fausnaugh@ttu.edu).

Results from TESS observations of Type Ia supernova are on my [Extragalactic Astrophysics]({filename}../extragalactic/extragalactic.md) page.


## Multiwavelength monitoring with TESS

See my database of [TESS-*MAXI*](https://space.mit.edu/home/faus/tesstransients/maxi_plots/) and [TESS-*Swift BAT*](https://space.mit.edu/home/faus/tesstransients/bat_plots/) light curves.

TESS's large field of view also make it is easy to coordinate multiwavelength monitoring programs.  I'm leading programs with [*NICER*](https://heasarc.gsfc.nasa.gov/docs/nicer/proposals/ao4/NICER_Cycle_4_Accepted_Proposals.pdf), *Swift*, and [TESS](https://hera.gsfc.nasa.gov/docs/tess/data/approved-programs/cycle5/GO5118.txt) to simultaneously observe nearby AGN at X-ray, UV, and optical/NIR wavelengths.

I also maintain databases of simultaneous light curves from TESS and all-sky X-ray monitor data from [*MAXI*](https://space.mit.edu/home/faus/tesstransients/maxi_plots/) and [*Swift BAT*](https://space.mit.edu/home/faus/tesstransients/bat_plots/) (and I am planning to add *Fermi* soon).  I'm happy to share data if you see something interesting.

## Search for fast transients with TESS

With a limiting magnitude of 20th to 21st magnitude in 8 to 30 hours, TESS can find short-timescale, exotic transients such as those powered by newly formed neutron stars and black holes or electromagentic counterparts of neutron star mergers (kilonovae).  For example, the rate of detectable Fast Blue Optical Transients in TESS data is about 1 per 4 months and the rate of detectable kilonova is 0.5 per year. The advantage of using TESS to search for these transients is that its continuous light curves can identify objects that evolve on timescales less than one day, while TESS’s wide field-of-view has a reasonable probability of observing rare events. As of September 2022, TESS data are being released on a weekly basis ([TICA](https://archive.stsci.edu/hlsp/tica), PI Fausnaugh), and we have started a program to search for these valuable transients in TESS images as soon as the data are available.


## Reverberation Mapping

See my calibration code [mapspec on github](https://github.com/mmfausnaugh/mapspec).


Reverberation mapping is a technique to probe the environments around supermassive black holes by measuring light echoes.  I developed a method to calibrate night-to-night reverberation mapping spectra on a consistent scale.

An implementation of this code is available on github, in the form of a python package called [mapspec](https://github.com/mmfausnaugh/mapspec) (*M*CMC *A*lgorithm for *P*arameters of *SPEC*tra).  The algorithm and performance of the code is documented in [Fausnaugh 2017](https://ui.adsabs.harvard.edu/abs/2017PASP..129b4007F/abstract).

Results from reverberation mapping studies that I am involved in are on my [Extragalactic Astrophyics]({filename}../extragalactic/extragalactic.md) page.



<!--
<table style="width:100%">
  <tr>
    <td> Type Ia Supernovae</td>
    <td> Reverberation Mapping</td>
    </tr>
    <tr>
    <td> tess transients</td>
    <td> Mutliwavelength Studies</td>
  </tr>
</table>
-->