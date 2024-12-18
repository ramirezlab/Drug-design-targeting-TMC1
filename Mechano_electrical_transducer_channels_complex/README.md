# Mechano Electrical Transducer (MET) Channel complex

In the absence of 3D-atomic structures of the mammalian MET-channel complex, we constructed a model of the complex by assembling Mus musculus (Mm) TMC1 subunits with MmCIB2 and MmTMIE, adopting an open-like conformation with domain swapping feature at transmembrane domain 10 (TM10). This model was constructed using AlphaFold2 through the ColabFold github repository. The assembled complex was compared with the cryo-EM structure of the expanded CeTMC-1 complex, confirming that the TM10 domain was in the typical domain-swapped conformation, which is a structural requirement for the proper oligomerization of MmTMC1.

The model was subjected to energy minimization, followed by embedding into a pre-equilibrated 1-palmitoyl-2-oleoyl-sn-glycero-3-phosphocholine (POPC) phospholipid membrane and solvation with a final ionic concentration of 15 mM KCl. Subsequently, the system was subjected to 25 ns of equilibrium MDs in a NPγT semi-isotropic ensamble, applying restrictions to the protein backbone, followed by 25 ns of production MDs (three replicas) applying restrictions to the protein secondary structure backbone. Here we provide frame structure at 24 ns post-equilibration of the MET complex (Figure 1) and data analysis of all three replicas of production 25ns-MDs (Figure 2).

<p align="center">
<img width="70%" src="Figures/Fig_MET_complex.jpg">
</p>

**Figure 1.  Mechano Electrical Transducer (MET) Channel complex modeling.** Front view of a 25 ns frame of the dimeric, equilibrated TMC1 protein in complex with two protomers of TMIE (orange) and two protomers of CIB2 (red) proteins. The system is embedded in a POPC membrane, with the phospholipid heads illustrated as white beads. The TMC1 pores of chains A and B are represented by a blue funnel obtained by HOLE analysis.

**Figure 2.  RMSDs de las 3 replicas - FALTAN.** Front .
