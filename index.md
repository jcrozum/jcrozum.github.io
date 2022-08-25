# Jordan Rozum
[GitHub](https://github.com/jcrozum) <br>
[GoogleScholar](https://scholar.google.com/citations?user=xUOh4q4AAAAJ&hl=en&oi=ao) <br>
[ORCiD](https://orcid.org/0000-0002-4356-9809)
## Research Interests

Current work: biological networks, network control theory, discrete and ODE biological models<br>
Previous work: galaxy modeling, airglow physics, differential geometry and Lie theory

My work is about studying how feedback loops underlie multistability in network models of complex systems, and biomolecular systems in particular. I work on generalizing Boolean techniques to ODEs by considering how positive feedback loops in networks give rise to trap sets in phase space. I've used this framework to study attractor control of ODE models in various contexts, including the cell cycle regulation, pattern formation during embriogenesis, and immune cell signaling. I am also interested in studying Boolean networks. I am the lead developer of the Python library pystablemotifs, which enables fast attractor identification and control in Boolean networks. This library has allowed us to study attractor scaling in large random Boolean networks and to drive empirical Boolean networks to any desired attractor.

### Highlights: Characterizing robust behaviors in cells

#### “Identifying (un) controllable dynamical behavior in complex networks”. JC Rozum and R Albert. PLoS Computational Biology 14 (12), 2018

![Drosophila](DrosophilaEN.png)

I developed a formalism that allows one to identify positive feedback loops
in ODE models that function in a manner analogous to the stable motifs of discrete models. I used this
formalism to analyze the biomolecular decisions that lead to the formation of embryonic segments in the
fly (*Drosophila melanogaster*) and to uncover a self-reinforcing feedback loop in the biomolecular circuitry
that governs the response of T-cells to external signals. In both cases, I showed how my methods identify
manipulations of the system that can disrupt observed phenotypes and manipulations that cannot.
Apart from their utility in basic science research, observations of this nature have important potential applications 
in the development of pharmaceuticals
because they can narrow the (often very expensive) search for potential drug targets.

See the relevant paper [here](https://doi.org/10.1371/journal.pcbi.1006630).

### Highlights: Making sense of long-term behaviors in large networks

#### “Parity and time-reversal elucidate both decision-making in empirical models and attractor scaling in critical Boolean networks”. JC Rozum, JGT Zañudo, X Gan, D Deritei and R Albert. Science Adv. 7 (29), eabf8124,2021

![PS](PS_SD_Overview.png)

I led the development of the open-source Python library [pystablemotifs](https://github.com/jcrozum/pystablemotifs), 
which provides one of the world's fastest algorithms for attractor identification
and control in Boolean networks. This library uses parity and time reversal provide new insights into the key regulatory circuits that underpin the biochemical "decisions" that cells make. We used this tool to identify
the attractor repertoires of networks 80 times larger than ever before considered and thereby resolved a 50-year-old open problem about how stochasticity affects a cell's diversity of phenotypes. This was the
first time that stochastic genome-scale biomolecular models were analyzed in such detail. The results
of our analysis showed that the behaviors of traditional random models of gene regulation are
highly sensitive to stochasticity, suggesting biological selection pressures that are not accounted for in the canonical model.

See the relevant paper [here](https://doi.org/10.1126/sciadv.abf8124).
See popular press summary [here](https://www.eurekalert.org/news-releases/583775)

## Research Experience

### Postdoctoral Researcher 2022-Present, Binghamton University (SUNY) Dept. of Systems Science and Industrial Engineering
I am a current member of the Complex Adaptive Systems & Computational Intelligence ([CASCI](https://casci.binghamton.edu/casci.php)) laboratory lead by Professor Luis Rocha. I work on developing new tools and algorithms for analyzing complex networks in a variety of domains, including social media, biomedical data, and systems biology.

### Graduate Research Assistant 2016–2022, Pennsylvania State University Dept. of Physics
Developing new network control approaches that generalize methods for discrete dynamics to continuous ODE network
models in collaboration with Professor Réka Albert. Apply network control theory to biological network models to better
understand decision mechanisms in cellular systems, identify potential drug targets, and predict results of biological
experiments.


### Graduate Research Assistant 2014-2016, Utah State University Dept. of Mathematics
Classification of homogeneous space-times according to their symmetries as part of Master’s Thesis advised by Professor
Ian Anderson and Professor Charles Torre. Devised a new coordinate-free classification scheme for Lie algebras of a
certain type relevant to homogeneous solutions to the Einstein equations and implemented the classification using the
DifferentialGeometry package of the computer algebra system Maple.


### Undergraduate Researcher, 2011-2014, Utah State University Dept. of Electrical Engineering

Data validation for the SABER (Sounding of the Atmosphere using Broadband Emission Radiometry) satellite instru-
ment in collaboration with Professor Gene Ware and Professor Doran Baker. Analyzed SABER data, and maintained
the USU copy of the database. Focused on perceived bifurcation of hydroxyl airglow layer in the mesosphere.
Undergraduate Research Fellow, 2010-2014, Utah State University Dept. of Physics
Examining bias in galaxy catalogs due to galaxy geometry in collaboration with Professor Shane Larson as part of USU’s
Undergraduate Research Fellowship. Wrote computer simulations of galaxy surface brightness. Performed statistical
analyses of galaxy catalogs to search for possible indications of observation bias.

## Education
#### Ph.D. in Physics from Pennsylvania State University, 2022
- Concentration: Network biophysics and dynamical systems
- Dissertation: Attractor identification and control of Boolean and ODE network models in Systems Biology
- Advisor: Professor Réka Albert

#### Master’s in Mathematics from Utah State University, 2016
- Concentration: Mathematical physics and differential geometry
- Thesis: Classification of Five-dimensional Lie Algebras with One-dimensional Subalgebras Acting as Subalgebras of the Lorentz Algebra
- Advisors: Professor Ian Anderson and Professor Charles Torre

#### Bachelor’s in Physics and Mathematics from Utah State University, 2014
- Magna Cum Laude
- Capstone project: Analyzing solutions to the Einstein equations using the Maple package DifferentialGeometry

## Honors, Awards, and Society Memberships
- PSU Peter Eklund Memorial Lectureship Award Honorable Mention, 2019,2020
- PSU David Duncan Graduate Fellowship, 2019
- PSU Department of Physics David H. Rank Memorial Award, 2017
- PSU College of Science Roberts Scholarship Award, 2016
- USU Magna Cum Laude, 2014
- USU Physics Department Outstanding Senior, 2014
- Barry M. Goldwater Scholar, 2013
- Barry M. Goldwater Scholarship Honorable Mention, 2012
- USU A-Pin Award for Consecutive 4.0 Semesters, 2010-2014
- USU Undergraduate Research Fellow and Presidential Scholar, 2010-2014
- Sigma Pi Sigma honor society member
- NetSci member

## Teaching Experience

#### Teaching Assistant, Pennsylvania State University Department of Mathematics 2016-2017
Course: Introductory Classical Mechanics

#### Course Instructor, Utah State University 2015
Course: Advanced Calculus

#### Teaching Assistant, Utah State University Department of Mathematics 2015
Courses: Introductory College Algebra

#### Teaching Assistant, Utah State University Department of Physics 2013-2014
Courses: Introductory Physics I and II

#### Undergraduate Teaching Fellow, Utah State University 2011-2013
Courses: Classical Mechanics, Electromagnetism I and II

## Relevant Skills
Programming ability in C++, Python, Octave, R, Maple, Sage <br>
Expertise in network and network modeling packages StableMotifs, BooleanNet, PyBoolNet, networkx, igraph, statnet <br>
Proficient with graph visualization software yEd, tikz, gephi <br>

## Publications
“Attractor identification and control of Boolean and ODE network models in Systems Biology”. JC Rozum. PhD Dissertation in Physics, 2022

“pystablemotifs: Python library for attractor identification and control in Boolean networks”. JC Rozum, D
Deritei, KH Park, JGT Zañudo, R Albert. Bioinformatics btab825, 2021

“Parity and time-reversal elucidate both decision-making in empirical models and attractor scaling in critical
Boolean networks”. JC Rozum, JGT Zañudo, X Gan, D Deritei and R Albert. Science Adv. 7 (29), eabf8124,
2021

“Controlling the cell cycle restriction switch across the information gradient”. JC Rozum and R Albert. Advances
in Complex Systems 22 (07n08), 1950020, 2020

“A feedback loop of conditionally stable circuits drives the cell cycle from checkpoint to checkpoint”. D Deritei,
JC Rozum, E Ravasz Regan, R Albert. Sci Rep 9 16430, 2019


“Identifying (un) controllable dynamical behavior in complex networks”. JC Rozum and R Albert. PLoS Compu-
tational Biology 14 (12), 2018


“Self-sustaining positive feedback loops in discrete and continuous systems”. JC Rozum and R Albert. Journal of
Theoretical Biology 459 35-44, 2018

“Classification of Five-dimensional Lie Algebras with One-dimensional Subalgebras Acting as Subalgebras of the
Lorentz Algebra”. JC Rozum. Master’s Thesis in Mathematics, Utah State University (Advisors IM Anderson
and CG Torre), 2015

“Global Nightly OH and O2 Mesospheric Airglow: Examining a Decade of Measurements Using the NASA SABER
Satellite Sensor”. J Price, JC Rozum, G Ware, and D Baker. Journal of the Utah Academy of Sciences, Arts, and
Letters, 91, 2014

### Selected Talks and Poster Presentations

“Parity and time-reversal in Boolean networks”. JC Rozum, JGT Zañudo, X Gan, D Deritei and R Albert. Poster
presented at the Cold Spring Harbor Laboratory Cellular Dyanamics and Models meeting, May 19-21, 2021.

“Boolean Networks: discrete dynamical models of high-dimensional nonlinear systems”. JC Rozum. Invited talk
given at the University of Pennsylvania Mathematical Biology Seminar, Apr. 6, 2021.

“Parity and time-reversal in Boolean networks”. JC Rozum, JGT Zañudo, X Gan, and R Albert. Talk given at
the NetSci 2020 meeting, Rome, Italy (remote), Sep. 25, 2020

“Control robust trap spaces with applications to biomolecular networks”. JC Rozum and R Albert. Talk given at
the NetSci 2019 meeting, Burlington, VT, May 29, 2019

“Identifying (un)controllable dynamical behavior with applications to biomolecular networks”. JC Rozum and R
Albert. Invited talk given at PSU Theoretical biology seminar, State College, PA, Feb. 20, 2018

“Modeling spiral galaxy surface luminosity to explain non-uniform inclination distributions”. JC Rozum and SL
Larson. Poster presented at AAS National Conference, Washington D.C., Jan. 5, 2014

“Multiple peaks in SABER mesospheric OH emission altitude profiles”. JC Rozum, GA. Ware, DJ Baker, MG
Mlynczak, J Russell. Poster presented at AGU Fall Meeting, San Francisco, CA, Dec. 4, 2012

