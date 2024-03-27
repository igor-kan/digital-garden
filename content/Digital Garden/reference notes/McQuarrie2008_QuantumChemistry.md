---
title: "Quantum chemistry"
author(s): Donald A. McQuarrie
year: 2008
container title(journal, book, etc.): 
doi: 
---
Status: #reference #A 
Tags: [[McQuarrie.Simon1997_PhysicalChemistryMolecularApproach]]
# Quantum chemistry
[Zotero Link](zotero://select/items/@McQuarrie2008_QuantumChemistry) - [DOI Link](https://doi.org/) - [Web]()

# Intro

## TMP 

| Classical mechanics                           | Quantum mechanics           |
| --------------------------------------------- | --------------------------- |
| everyday-sized, large, macroscopic(?) objects | very small objects          |
| heavy, relatively large mass objects          | light objects               |
| continuous                                    | discrete or quantized       |
| Newton's equations                            | Schrödinger equations       |
| trajectory                                    | wavefunction                |
| deterministic                                 | probabilistic (stochastic?) |
| intuitive                                     | non-intuitive               |
|                                               |                             | 

For CM, quantities such as velocity, energy, momentum are continuous, can be changed or change by infinitesimal amounts.

In QM, quantities such as energy are discrete or quantized. Only a finite `?` set of values are allowed, or the states the particle can be in.

Newton's equations describe the motion of an object with its position and momentum known at each point in time. Newton's equations give a trajectory.

In QM, the position and momentum cannot be determined at the same point in time `?`. The position and momentum are not well-defined quantities. Energy of a particle is the only well-defined quantity. The Schrödinger equations give wavefunctions of a particle, which doesn't give a map(or trajectory) of position and momentum of the particle at any given time, but rather describes a particle as a wave which spreads out over space. And gives: The position and momentum are not well-defined quantities. Energy of a particle is the only well-defined quantity.

CM is deterministic the same initial conditions(position, momentum, etc.) of a system will result in the same outcomes. All such experiments give the same result. Tells what outcomes will occur.

For QM, two systems in the same initial conditions may not give the same result. Instead the probability of all outcomes is given by the wavefunction. does not tell what outcomes will occur.
![[McQuarrie2008_QuantumChemistry 2023-02-06 12.56.18.excalidraw]]
# Chapter 1

Max Planck
- born in Kiel, Germany.
- received his Ph.D. in theoretical physics from the University of Munich at 21.
- worked at the University of Kiel.
- worked at the University of Berlin, where the Institute of Theoretical Physics was formed around him.
- won the Nobel Prize in Physics in recognition of his discovery of energy quanta.
- at the end of the 1890's, introduced a quantum hypothesis to achieve agreement between his theoretical equations and experimental data for the blackbody radiation problem; became the father of the quantum theory.  The equations were solely based on the second law of thermodynamics and contrary to the mainstream accounts. 

```
assigning a self-consistent set of n to the m


```

Stanislao Cannizzaro - (the controversial in the past) concept of molecules.
Dmitri Mendeleev -  assigning a self-consistent(?) set of atomic masses to the elements and construction a periodic table of the elements; but underlying reasons for the periodic behavior of elements were not understood in his time.
Friedrich Kekule - 
[August Kekule von Stradonitz | German chemist | Britannica](https://www.britannica.com/biography/August-Kekule-von-Stradonitz)
Svante Arrhenius - fundamental principles of chemical reactions, and kinetics(?)

```
Newtonian mechanics vs. ?
Joseph-Louis Lagrange 
Sir William Hamilton

planetary motion
elasticity
hydrodynamics
```



Count Rumford and James Joule - demonstrated the equivalence of heat and work.
Sadi Carnot - formulated entropy and the second law of thermodynamics.

Josiah Gibbs - filled the field of thermodynamics in a way relevant to chemistry; lots of original formulations are still used. 
[J. Willard Gibbs | American scientist | Britannica](https://www.britannica.com/biography/J-Willard-Gibbs)

Sir William Hamilton and Joseph-Lois Lagrange extended the Newtonian mechanics. The resulting theory can be applied to motion of planetary bodies, complicated natural phenomena like elasticity and hydrodynamics. 

Albert Einstein - the theory of relativity that extends the classical physics to high velocities and astronomical distances. 
The theory of relativity has some important effects, e.g. electronic properties of heavy atoms, but not significant for chemical systems in comparison to quantum mechanics.

19th century - ongoing controversy over the nature of the light: wavelike or particle-like.
James Clerk Maxwell - unified diverse physical results into Maxwell equations, which relate the field of optics with electromagnetism. 

1887 - Heinrich Hertz experimentally demonstrated the wavelike properties of light. 

classical physics - the body of accomplishments in physics and their development before about 1900s, before the quantum theory and the theory of relativity.

## 1.1 Classical Physics, Blackbody radiation, and the UV catastrophe

```
material body 

spectrum
spectral
spectral distribution
distribution of vs. plot of 
frequency spectrum 
wavelength spectrum ?
ideal body
idealization

spectral distribution of the intensity of blackbody radiation as a function of frequency for several temperatures. 
vs.
a plot of the the intensity of blackbody radiation versus frequency for several temperatures
a curve of ....

arbitrary unit
the total radiated energy 


```


A heated material body emits radiation with frequencies that increase with temperature. 
The frequency spectrum depends on the particular heated body and ...
[[blackbody radiation]]


the Rayleigh-Jeans Law 
$$d\rho(\nu,T)=\rho_{\nu}(T)d\nu=\frac{8\pi k_{B}T}{c^3}\nu^2d\nu$$

## 1.2 Blackbody radiation, a quantum hypothesis
the Planck distribution law for blackbody radiation
aka the blackbody distribution law
$$d\rho(\nu,T)=\rho_{\nu}(T)d\nu_{}=\frac{8\pi }{c^3}\frac{\nu^3d\nu}{e^{h\nu/k_{B}T}-1}$$
`how both were derived`



according to what laws of  19th century physics the Rayleigh-Jeans Law was derived?


Planck distribution law for blackbody radiation, Planck's radiation law 
- in terms of frequence \nu
- in terms of wavelength \lambda

sub in eq 1.3 doesnt make sense

the notation in 1.1-1.3 and how they derived it?

radiant energy density all per unit volume? why volume? what is in real life in black body radiation?

The Wien displacement law 
- empirical relationship

What is the opposite of empirical? theoretical?

![[McQuarrie2008_QuantumChemistry 2023-01-30 13.36.29.excalidraw]]


the Stefan-Boltzmann law 
- why per square meter and per unit time? why sq meter? sq meter of blackbody itself?
![[McQuarrie2008_QuantumChemistry 2023-01-30 13.51.34.excalidraw]]

$\sigma$ - the Stefan-Boltzmann constant

![[McQuarrie2008_QuantumChemistry 2023-02-15 21.35.46.excalidraw]]


```
little did N V
heady era of 
tenet
Ns were to be 
overturn

```


### TMP

density of radiation
Rayleigh-Jeans law
quantized set of values
Max Planck - 1900?

energy of particles is quantized


![[McQuarrie2008_QuantumChemistry 2023-02-06 12.57.36.excalidraw]]

## 1.3 Photoelectric effect, a Q hypothesis
`how exactly AE proved KE formula using the conservation of energy?`

$$KE = h\nu-\phi = h\nu - h\nu_{0}$$


### TMP 1.2 Photoelectric effect
Quantum theory - 1905 - Albert Einstein 
![[McQuarrie2008_QuantumChemistry 2023-02-06 13.07.26.excalidraw]]
[[photoelectric effect]]
$$KE = h\nu - h\nu_{0}=h\nu - \Phi$$
energy of a photon minus some barrier or initial energy. If photon's energy isn't greater than the work function, an electron is not removed. 
Work function - the amount of energy needed to eject an electron from the metal

$$\Phi = h\nu_{0}$$

- [ ] finish vid

## 1.4 Vibrations of atoms in Crystals
[[law of Dulong and Petit]]

## 1.5 Hydrogen atomic spectrum consists of several series of lines

Lyman 
Balmer
Paschen
Brackett

[[Rydberg formula]]
### TMP 1.3 Rydberg formula


## 1.8 Bohr
According to the Rutherford's nuclear model of an atom, hydrogen atom, $^1H$, can be modelled as a positively charged proton - the nucleus,  and an electron. `the phrasing that e- rotates around p+ implies that p+ is a fixed center?`.  Since the proton's mass is much larger than electronic mass, we can assume that the nucleus is fixed`what does it mean exactly? that it is statinary relative to ref frame of nucleus and e-?` and the electron rotates around it in a circular trajectory.`from where it is known that e- rotates about nucleus?`
`One of Bohr's non-classical assumtpions was that there are stable(aka stationary?) orbits, i.e. the electron, due to the centripetal acceleration, doesn't emit EM radiation, lose its energy, and spiral into the nucleus as the classical physics predicts(e.g. electrons emit radiowaves when accelerated in antenna?); are these all properties equivalent, i.e. from the stable orbit assumption to not spiralling into etc. So we can say that it  also doesn't lose energy at all -> this means that we can assume it moves in uniform ciruclar motion` In an uniform circular motion, the centripetal force `supplied by e.g. the thension in string, attraction forces, friction(on disk?)etc.` exerts  
[[radio transmission]]

$$F_{e}=\frac{1}{4\pi \epsilon_{0}}\frac{q^2}{r^2}$$


### TMP ## 1.4 Bohr hydrogen model 1: radius


### TMP ## 1.5 Bohr hydrogen model 2: energy
https://www.youtube.com/watch?v=rkKhMRD_Lio&list=PLm8ZSArAXicL3jKr_0nHHs5TwfhdkMFhh&index=6
## 1.9 Reduced mass
- [ ] Derive the reduced mass formula and improve Bohr's formulas independently. Also add formulas for He+ and Li2+ specifying the nucleus' charge Ze where Z is a positive integer.
- [ ] Learn the basics of rotation, center of mass, moment of inertia, etc. first.
- [ ] derive from first principles and imagination
- [ ] don't read the first part of the ch. until then

## 1.10 


### TMP 1.6 Wave-particle duality
1906 - Einstein - photoelectric effect - light is a particle and a wave. discrete energy, individual quanta of light, photons

1924 - De Broglie - matter can be both particles and wave ?

$$\lambda=\frac{h}{p}=\frac{h}{mv}$$

for small mass, the $\lambda$ is finite and measurable

wavelength of e- is about that of X-ray when mass of e- and small portion of speed of light speeds
	- de Broglie waves are used in X-ray crystallography and electron interference 

https://www.desmos.com/calculator/gazhf6fafx

circumference is the integer multiple of wavelength such that the wave doesn't interfere/overlap with itself or cancel itself out. It is a standing wave. Any integer n is good according to the hypothesis 
![[McQuarrie2008_QuantumChemistry 2023-02-06 13.24.36.excalidraw]]

Bohr frequency/quantization condition for angular momentum- hypothesis Bohr used to solve the two equations `?`
$$\ell = n \hbar $$

$$\hat{H} ̂Ψ(x)=EΨ(x)$$
## 1.14 Heisenberg's uncertainty principle
### tmp 1.7 Uncertainty Principle in Measurement

1920's - Heisenberg uncertainty principle
$$\Delta x \Delta p \geq \frac{\hbar}{2}$$

Despite its predictive capability(predicts the Rydberg constant, accurately computes the average distance, and the average energy levels), the Bohr Model of atom is not correct since there is zero uncertainty in both position and momentum of a particle. Need more general theory that describe waves of particles etc.


![[McQuarrie2008_QuantumChemistry 2023-02-06 13.42.04.excalidraw]]

$$p= \frac{h}{\lambda}$$
## 2.1 1D wave equation
### TMP 2.1 Classical wave equation

Classical wave equation
$$\frac{\partial^2u(x,t)}{\partial x^2}=\frac{1}{v^2}\frac{\partial^2u(x,t)}{\partial t^2}$$

![[McQuarrie2008_QuantumChemistry 2023-02-06 13.51.26.excalidraw]]

Wave Equation - YouTube
https://www.youtube.com/watch?v=9TQCKWWAVjM&ab_channel=MITOpenCourseWare

PDE 7 | Wave equation: intuition - YouTube
https://www.youtube.com/watch?v=ck-r_qmNNG0&ab_channel=commutant

(2:3) The Wave Equation: Derivation (Walter Lewin, MIT) - YouTube
https://www.youtube.com/watch?v=r2GIY2ZmXPY&ab_channel=hamsterpoop
## 2.2 Vibrating string
### TMP
![[McQuarrie2008_QuantumChemistry 2023-02-06 14.14.45.excalidraw]]
## 3.1 The Schrödinger equation
### TMP 3.1
misses spatial amplitude(wavefunction) factor in one derivation step

![[McQuarrie2008_QuantumChemistry 2023-02-06 14.23.01.excalidraw]]
## 3.2
### TMP 3.2 Operators 
classical properties that can be measured are related to linear qm operators

e.g. operator for the total energy of a particle (i.e total mechanical energy of a conservative system of one particle?)  Hamiltonian


## 3.3
### TMP 3.3 Eigenvalues, Eigenvectors
## 3.4
### TMP
## 3.5 Particle in a box

### CHMB21
![[McQuarrie2008_QuantumChemistry 2023-02-06 15.16.30.excalidraw]]


$$\hat{H} ̂Ψ(x)=EΨ(x)$$
$$ψ′′(x) = -k2ψ(x)$$


![[McQuarrie2008_QuantumChemistry 2023-02-06 15.42.05.excalidraw]]

[[quantum-mechanical tunneling]]
### TMP
![[McQuarrie2008_QuantumChemistry 2023-02-06 14.50.00.excalidraw]]



## 3.6 Normalization 
### CHMB21
https://www.desmos.com/calculator/zqo7bncevb

![[McQuarrie2008_QuantumChemistry 2023-02-06 16.10.18.excalidraw]]

linear combination and superposition
[Time Dependent Particle in a Box Wavefunction (desmos.com)](https://www.desmos.com/calculator/ogqsx8uipx) 
	change c_1 to any vector 

c=[1,0] (for one state)
for eigenstate where all but one entries are 0 -> stationary state
otherwise for a linear combination, e.g [1,1,0,0] -> moving
![[McQuarrie2008_QuantumChemistry 2023-02-06 16.22.21.excalidraw]]

polarization![[McQuarrie2008_QuantumChemistry 2023-02-06 16.40.41.excalidraw]]
### TMP
## 3.
### TMP
## 3.
### TMP
## 3.
### TMP
## 3.
### TMP
## 3.
### TMP


# Chapter 3: The Schrödinger Equation and a Particle in a Box 
[Erwin Schrodinger | Biography, Atomic Model, Cat, & Facts | Britannica](https://www.britannica.com/biography/Erwin-Schrodinger)
Erwin Schrödinger was born in Vienna, Austria, and received his Ph.D. in theoretical physics from the University of Vienna at 23. Held a number of positions in Germany before succeeding Max Planck at the University of Berlin at Planck's request. In 1933, he shared the Nobel Prize in Physics with Paul Dirac for the "discovery of new productive forms of atomic theory" and left Berlin for Austria due to political opposition to Hitler and Nazi policies. Became professor at the University of Graz and was forcibly removed from his professorship after Nazi invasion of Austria. He moved to the Institute of Advanced Studies(created for him) in Dublin, Ireland. 

He rejected the probabilistic interpretation of the wave equation, which led to disagreement with Max Born. Schrödinger preferred working alone, and so no school was developed around him as it did for some other quantum physics developers. 
Biography by Walter Moore, "Schrödinger: Life and Thought"


The Schrödinger equation 

wave function
stationary-state wave funciton


# Chapter 4: Postulates and Principles of QM

## 4.
### TMP
## 4.
### TMP
## 4.
### TMP
## 4.
### TMP
## 4.
### TMP
## 4.
### TMP
## 4.
### TMP
## 4.
### TMP
## 4.9 Orthogonality
### TMP
Symmetric Matrices, Real Eigenvalues, Orthogonal Eigenvectors - YouTube
https://www.youtube.com/watch?v=ZTNniGvY5IQ&ab_channel=MITOpenCourseWare

Eigenvalues and Eigenvectors - YouTube
https://www.youtube.com/watch?v=DzqE7tj7eIM&ab_channel=MITOpenCourseWare

## 4.
### TMP

## 4.
### TMP


# Other
[J. Robert Oppenheimer - Wikipedia](https://en.wikipedia.org/wiki/J._Robert_Oppenheimer)

https://en.wikipedia.org/wiki/Pilot_wave_theory
https://en.wikipedia.org/wiki/Louis_de_Broglie