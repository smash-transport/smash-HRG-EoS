# The SMASH hadron resonance gas EoS

This repository contains the equation of state (EoS) of the hadron resonance gas consisting of the degrees of freedom of the [SMASH](http://smash-transport.github.io) transport approach. It can for example be employed in hydrodynamics+transport hybrid approaches to match the equation of state at the transition hypersurface. <br>
When using the SMASH HRG EoS presented herein, please cite
[A. Schäfer, I. Karpenko, H. Elfner: "Conservation laws in a novel hybrid approach"](https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=Conservation%20laws%20in%20a%20novel%20hybrid%20approach).


### Properties and Format
The SMASH HRG EoS is provided in tabulated format mapping from the energy density e, baryon density n<sub>B</sub> and electric charge density n<sub>Q</sub> to the temperature T, pressure p, baryon chemical potential &#956;<sub>B</sub>, charge chemical potential &#956;<sub>Q</sub> and strangeness chemical potential &#956;<sub>S</sub>: (e, n<sub>B</sub>, n<sub>Q</sub>) -> (T, p, &#956;<sub>B</sub>, &#956;<sub>Q</sub>, &#956;<sub>S</sub>)

The table containing the SMASH HRG EoS (``hadgas_eos_SMASH.dat``) consists of 8 columns with explicitly these quantities in order: [e &nbsp; n<sub>B</sub> &nbsp; n<sub>Q</sub> &nbsp; T &nbsp; p &nbsp; &#956;<sub>B</sub> &nbsp; &#956;<sub>S</sub> &nbsp; &#956;<sub>Q</sub>]

The units are GeV/fm<sup>3</sup> for the energy density and pressure, 1/fm<sup>3</sup> for the baryon and charge density, and GeV for the temperature and the chemical potentials. The EoS presented herein covers the range e &#8712; [0.01, 1.0] GeV/fm<sup>3</sup>, n<sub>B</sub> &#8712; [0.0, 0.5] GeV/fm<sup>3</sup>, and n<sub>Q</sub> &#8712; [-0.1, 0.4] GeV/fm<sup>3</sup>. It is perfectly accurate at higher energy densities, but constitutes an approximation at lower energy densities.
Please consult [A. Schäfer, I. Karpenko, H. Elfner: arXiv:2109.08578](https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=Conservation%20laws%20in%20a%20novel%20hybrid%20approach) for further details.
