# hydrogen-benchmark-PRX

This is the main directory for the hydrogen chain benchmark data.
Please contact shiwei@wm.edu or mmotta@caltech.edu (alternatively mariomotta31416@gmail.com) for questions

#

Paper:
   Phys. Rev. X 7, 031059 (2017)

Title:
   Towards the Solution of the Many-Electron Problem in Real Materials:
   Equation of State of the Hydrogen Chain with State-of-the-Art Many-Body Methods

Authors:
   Mario Motta, David M. Ceperley, Garnet Kin-Lic Chan, John A. Gomez, Emanuel Gull,
   Sheng Guo, Carlos A. Jiménez-Hoyos, Tran Nguyen Lan, Jia Li, Fengjie Ma, Andrew J. Millis,
   Nikolay V. Prokof'ev, Ushnish Ray, Gustavo E. Scuseria, Sandro Sorella, Edwin M. Stoudenmire, 
   Qiming Sun, Igor S. Tupitsyn, Steven R. White, Dominika Zgid, and Shiwei Zhang 
   (Simons Collaboration on the Many-Electron Problem)

DOI:
   https://doi.org/10.1103/PhysRevX.7.031059

#

This work is licensed under a Creative Commons Attribution 4.0 International License 
(http://creativecommons.org/licenses/by/4.0/).

#

Data are in the directories N_number_OBC, N_number_PBC, Thermodynamic-Limit with

OBC          open boundary conditions
PBC          periodic boundary conditions
number       number of particles (number=10,18,...,102)

Inside these directories are data from different methods, named after the technique and basis set

technique_basis-b (Examples: DMRG_basis-DZ, AFQMC_basis-CBS, SBDMRG_basis-SBDZ)

Technique List:
========================================================================
AFQMC:      auxiliary-field quantum Monte Carlo
BDMC:       bold diagrammatic Monte Carlo
DMET:       density-matrix embedding theory
DMRG:       density-matrix renormalization group with a quantum chemistry basis
FCI:        full configuration interaction
GF2:        self-consistent second-order Green's function
LRDMC:      lattice-regularized diffusion Monte Carlo
MRCI:       multireference configuration interaction without Davidson correction
MRCI+Q:     multireference configuration interaction with Davidson correction
MRCI+Q+F12: multireference configuration interaction with Davidson and F12 correction
PC-NEVPT2:  strongly contracted N-electron valence state second-order perturbation theory
SC-NEVPT2:  partially contracted N-electron valence state second-order perturbation theory
RHF:        restricted Hartree-Fock
RCCSD:      restricted coupled-cluster with full treatment of singles and doubles
RCCSD(T):   restricted coupled-cluster with full treatment of singles and doubles and perturbative treatment of triples
SC-GW:      fully self-consistent GW
SBDMRG:     specialized DMRG with sliced basis sets
SEET:       self-energy embedding theory
UHF:        unrestricted Hartree-Fock
UCCSD:      unrestricted coupled-cluster with full treatment of singles and doubles
UCCSD(T):   unrestricted coupled-cluster with full treatment of singles and doubles and perturbative treatment of triples
UGF2:       spin-unrestricted self-consistent second-order Green's function
VMC:        variational Monte Carlo [52,53]

Basis List:
========================================================================
STO:   STO-6G
DZ :   cc-pVDZ
TZ :   cc-pVTZ
QZ :   cc-pVQZ
5Z :   cc-pV5Z
SBSTO: sliced-basis STO
SBDZ:  sliced-basis cc-pVDZ
SBTZ:  sliced-basis cc-pVTZ
CBS:   complete basis set limit
