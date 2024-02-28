# Tardigrades
Metadynamics of Tardigrade inspired peptides
- ions.mdp: mdp file for adding the ions
- minim.mdp: mdp file for the minimization step
- npt.mdp: mdp file for the equilibration step
- charmm36-mar2029.ff: force field
- CAHS11aa_*.pdb / control_*.pdb: pdb of the peptides
- npt.gro: equilibrated structures
- plumed_metad_input.dat: input for metadynamics
- CAHS11aa_4.pdb / control_ref.gro: references for RMSD

- graphs.qmd: Rstudio notebook for RMSD graphs
- trajclust.ipynb: python notebook for metadynamics analysis
- dssp_cahs.ipynb / dssp_control.ipynb: DSSP analysis for CAHS11aa and control
