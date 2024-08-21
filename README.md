# Quantum Chemical Data Sets and Databases for Machine Learning Potentials

This GitHub dashboard provides links and brief descriptions for various quantum chemistry data sets and databases mentioned in the paper. Here we follow alphabetical order. 


## 1. ANI-1 Dataset
- **Description**: A collection of non-equilibrium DFT total energy calculations for organic molecules, encompassing approximately 20 million conformations of 57,462 small organic molecules, used to train the ANI-1 potential, calculated using MMFF94 force field and $\omega$ B97x/6-31G(d) with the Gaussian 09.
- **Data Accessibility**:
  - [ANI-1 Dataset on Figshare](https://doi.org/10.6084/m9.figshare.5287732.v1)
  - [ANI-1 Dataset on GitHub](https://github.com/isayev/ANI1_dataset)

## 2. ANI-1x and ANI-1ccx Datasets
- **Description**: The ANI-1x data set comprises DFT calculations ($\omega$ B97x/6-31G* and $\omega$ B97x/def2-TZVPP) for approximately 5 million organic molecule conformations. The ANI-1ccx data set is a subset of ANI-1x, recomputed at the CCSD(T)/CBS level of theory. The computations utilized software such as RDKit, ASE, Gaussian 09, ORCA, and the HORTON software library.
- **Data Accessibility**:
  - [ANI-1x and ANI-1ccx Datasets on Figshare](https://doi.org/10.6084/m9.figshare.c.4712477)
  - [GitHub Repository](https://github.com/aiqm/ANI1x_datasets)

## 3. bigQM7ω
- **Description**: Ground-state properties and electronic spectra for over 12,880 molecules calculated using DFT and TDDFT with various functionals and basis sets, using the Gaussian software.
- **Data Accessibility**:
  - [Core Data](https://moldisgroup.github.io/bigQM7w)
  - [NOMAD Repository](https://dx.doi.org/10.17172/NOMAD/2021.09.30-1)
  - [Data-mining Platform](https://moldis.tifrh.res.in/index.html)

## 4. **C7O2H10-17**: 
- **Description**: Molecular dynamics trajectories for 113 randomly selected isomers of C7O2H10 (which represents the largest set of isomers within the
QM9 data set), calculated using DFT (PBE functional) with FHI-aims software.
 - **Data Accessibility**:
   - [quantum-machine.org](http://quantum-machine.org/data%20sets/)

## 5. **CheMFi**: 
- **Description**: A multifidelity compilation of quantum chemical properties derived from a subset of the WS22 database, featuring 135,000 geometries sampled from nine distinct molecules. It includes five different levels of fidelity, each corresponding to a specific basis set size (STO-3G, 3-21G, 6-31G, def2-SVP, def2-TZVP). The dataset was generated using TD-DFT with the CAM-B3LYP functional, calculated via the ORCA software.
- **Data Accessibility**:
  - [GitHub](https://github.com/SM4DA/CheMFi)
    
## 6. GW-QM9
- **Description**: Provides highly accurate frontier orbital energies and ionization potential/electron affinity values for 134,000 molecules from QM9 using the GW method implemented in CP2K.
- **Data Accessibility**:
  - [GW-QM9 on Figshare](https://doi.org/10.6084/m9.figshare.21610077.v1)

## 7. **ISO17**: 
- **Description**: Extends the C7O2H10-17 dataset with 129 isomers and additional data, calculated using DFT (PBE functional, GGA and Tkatchenko
Scheffler (TS) van der Waals correction method) with FHI-aims software.
 - **Data Accessibility**:
   - [quantum-machine.org](http://quantum-machine.org/data%20sets/)

## 8. MD17 and its later versions
- **Description**: Ab-initio molecular dynamics trajectories collection along with total energy and forces for ten small organic molecules, calculated using PIMD, PBE + vdW-TS, PBE/def2-SVP, CCSD, CCSD(T) and DFT FHI-aims with a list of softwares including i-PI code, ORCA and FHI-aims.
- **Data Accessibility**:
  - [MD17 Data Sets](http://www.sgdml.org/#data_sets)
  - [rMD17 Data Set](https://dx.doi.org/10.6084/m9.figshare.12672038)

## 9. MD22
- **Description**: MD trajectories for seven systems spanning four major classes of biomolecules and supramolecular structures, calculated using PBE+MBD level of theory with "light" and "tight" basis sets within the FHI-aims framework.
- **Data Accessibility**:
  - [MD22 Data Set](http://www.sgdml.org/#data_sets)

## 10. MultiXC-QM9
- **Description**: Expands upon QM9 by including data from 76 different DFT functionals alongside three basis sets and a semi-empirical method (GFN2-XTB), for small organic molecules, using the SCM software package.
- **Data Accessibility**:
  - [MultiXC-QM9 on Figshare](https://doi.org/10.11583/DTU.c.6185986.v3)

## 11. $\nabla^2$DFT Dataset
- **Description**: A comprehensive collection of approximately 16 million conformers for around 2 million drug-like molecules, calculated using $\omega$B97X-D/def2-SVP level theory with Psi4 software.
- **Data Accessibility**:
  - [nablaDFT Dataset on GitHub](https://github.com/AIRI-Institute/nablaDFT)

## 12. OrbNet Denali
- **Description**: Data set used to develop a machine learning potential for electronic structure calculations, includes over 2.3 million molecules, calculated using various levels of theory including GFN1-xTB, AIMD and $\omega$B97X-D3/def2-TZVP with a list of softwares including ENTOS BREEZE, DIMORPHITE-DL and ENTOS QCORE.
- **Data Accessibility**:
  -  [OrbNet Denali on Figshare](https://doi.org/10.6084/m9.figshare.14883867)

## 13. PC9
- **Description**: A counterpart to QM9, 99,234 distinct molecules, a subset of PubChemQC project selected based on the limitations of QM9 dataset (size of up to 9 heavy atoms in the range C, N, O and F).
- **Data Accessibility**:
  - [PC9 on Figshare](https://doi.org/10.6084/m9.figshare.9033977.v1)
  - [PC9 on Zenodo](https://doi.org/10.5281/zenodo.3588370)

## 14. PubChemQC B3LYP/6-31G*//PM6
- **Description**: Electronic properties for 85,938,443 molecules using DFT with the B3LYP/6-31G* basis set, following initial geometry optimization with the PM6 method, using the GAMESS software.
- **Data Accessibility**:
  - [PubChemQC B3LYP/6-31G*//PM6](https://nakatamaho.riken.jp/pubchemqc.riken.jp/b3lyp_pm6_datasets.html)

## 15. PubChemQC Database
- **Description**: Contains electronic structures for approximately 3 million molecules, optimized using DFT at the B3LYP/6-31G* level for ground states and TD-DFT with the B3LYP functional and 6-31+G* basis set for low-lying excited states. A list of software are utilized which are Firefly, SMASH and GAMESS.
- **Data Accessibility**:
  - [PubChemQC Database](https://nakatamaho.riken.jp/pubchemqc.riken.jp/b3lyp_2017.html)

## 16. PubChemQC PM6
- **Description**: PM6 data for 221 million molecules, including optimized geometries and electronic structures using the Gaussian 09.
- **Data Accessibility**:
  - [PubChemQC PM6](https://nakatamaho.riken.jp/pubchemqc.riken.jp/pm6_datasets.html)

## 17. QCDGE
- **Description**: An extensive collection of ground and excited-state properties for 443,106 organic molecules, each containing up to ten heavy atoms, including carbon, nitrogen, oxygen, and fluorine. These molecules are sourced from well-known databases such as QM9, PubChemQC, and GDB-11. Ground-state geometry optimizations and frequency calculations for all compounds were carried out using the B3LYP/6-31G* level of theory with BJD3 dispersion correction, while excited-state single-point calculations were performed at the $\omega$ B97X-D/6-31G* level. All computational work was conducted using Gaussian 16.
- **Data Accessibility**:
  - \href{Link}{http://langroup.site/QCDGE/}

## 17. QM1B
- **Description**: A large dataset of one billion training examples for machine learning applications in quantum chemistry, focusing on molecules with 9-11 heavy atoms, calculated using STO-3G and B3LYP in PySCF$_{\rm IPU}.
- **Data Accessibility**:
  -  [QM1B on GitHub](https://github.com/graphcore-research/qm1b-dataset)

## 18. QM7
- **Description**: Focuses on a subset of 7,165 small organic molecules from the GDB-13 database, providing Coulomb matrices, atomization energies, atomic charge, and Cartesian coordinates. DFT calculations are done using PBE0/tier2 basis set implemented in FHI-aims code.
- **Data Accessibility**:
  - [QM7 on Quantum-Machine.org](http://quantum-machine.org/datasets/)

## 19. QM7-X
- **Description**: A comprehensive data set of 4.2 million structures of small organic molecules containing up to seven non-hydrogen atoms, including 42 properties per molecule, calculated using PBE0+MBD level of theory with FHI-aims code.
- **Data Accessibility**:
  - [QM7-X on Zenodo](https://doi.org/10.5281/zenodo.4288677)

## 20. QM7b
- **Description**: An extension of QM7, providing data on 7,211 small organic molecules including 14 properties such as atomization energy, static polarizability, and frontier orbital eigenvalues, calculated using DFT and other quantum chemistry methods. Software used are OpenBabel, ORCA, and FHI-aims code (tight settings/tier2 basis set).
- **Data Accessibility**:
  - [Supplementary material of the reference paper](http://stacks.iop.org/NJP/15/095003/mmedia)

## 21. QM8
- **Description**: Provides electronic spectra data for approximately 21,786 small organic molecules, derived from QM9, calculated using TDDFT and other excited-state methods with the TURBOMOLE program.
- **Data Accessibility**:
  - [Supplementary material of the reference paper](https://pubs.aip.org/jcp/article-supplement/73278/zip/084111_1_supplements/)
  
## 22. QM9
- **Description**: A collection of molecular structures and properties for 134,000 small organic molecules, generated using density functional theory (DFT) at the B3LYP/6-31G(2df,p) level with the Gaussian 09 software.
- **Data Accessibility**:
  - [QM9 on Figshare](https://doi.org/10.6084/m9.figshare.978904)

## 23. QM9-G4MP2
- **Description**: Provides highly accurate G4MP2 calculations for the molecular structures within QM9, focusing on small organic molecules, using the Gaussian 16 software.
- **Data Accessibility**:
  - [QM9-G4MP2 on Figshare](https://doi.org/10.6084/m9.figshare.c.4351631.v1)

## 24. QM-sym Database
- **Description**: A database documenting the C$_n$h symmetry for each molecule within its vast repository, including 135,000 structures, calculated using DFT at the B3LYP/6-31G(2df,p) level with the Gaussian 09 software.
- **Data Accessibility**:
  - [GitHub Repository](https://github.com/XI-Lab/QM-sym-database)
  - [Figshare](https://doi.org/10.6084/m9.Figshare.9638093)

## 25. QM-symex Database
- **Description**: The QM-sym dataset has been expanded to include an additional 38,000 molecules, providing valuable information on excited-state properties. Calculation were performed using DFT at the B3LYP/6-31G(2df,p) level with the Gaussian 09 software.
- **Data Accessibility**:
  - [QM-symex on Figshare](https://doi.org/10.6084/m9.Figshare.12815276)

## 26. **QM-22**:
- **Description**: A compilation of molecular datasets specifically curated for Diffusion Monte Carlo (DMC) calculations of the zero-point state. Each dataset within QM22 employs unique methodologies tailored to the specific molecules involved, with detailed computational methods available in their corresponding publications.
 - **Data Accessibility**:
   - [GitHub](https://github.com/jmbowma/QM-22)

## 27. QMugs
- **Description**: Quantum-mechanical properties of over 665,000 drug-like molecules, calculated at GFN2-xTB and $\omega$B97XD/def2-SVP level theory using xTB and Psi4 software packages.
 - **Data Accessibility**:
  - [QMugs](https://doi.org/10.3929/ethz-b-000482129)

## 28. SPICE
- **Description**: A dataset of 2,008,628 conformations of 113,999 drug-like small molecules and proteins, using $\omega$B97M-D3BJ/def2-TZVPPD level theory implemented in Psi4.
- **Data Accessibility**:
  - [Zenodo](https://doi.org/10.5281/zenodo.7338495)
  - [GitHub](https://github.com/openmm/spice-dataset)

## 29. **TensorMol ChemSpider**: 
- **Description**: Energies for 3 million conformations from 15,000 different molecules, calculated using the QChem software.
- **Data Accessibility**:
  - The TensorMol ChemSpider data set was reportedly available for download at [Google Drive](https://drive.google.com/drive/folders/1IfWPs7i5kfmErIRyuhGv95dSVtNFo0e_) according to the supplementary information. However, the dataset is no longer accessible.

## 30. Transition1x Dataset
- **Description**: A collection of 9.6 million data points, each meticulously generated using DFT calculations with forces and energies for a staggering 10,000 organic reactions. These calculations employed the $\omega$B97x/6-31G(d) level of theory and utilized NEB and CINEB exploration technique. The computations were performed using software such as ASE and ORCA.
- **Data Access**:
  - [Transition1x Dataset on Figshare](https://doi.org/10.6084/m9.figshare.19614657.v4)
  - [Dataloaders and example scripts on GitLab](https://gitlab.com/matschreiner/T1x)

## 31. VIB5 Database
- **Description**: A collection of high-quality ab initio quantum chemical data for five small polyatomic molecules with significant astrophysical relevance, calculated using coupled-cluster and HF theory with the MOLPRO and CFOUR softwares.
- **Data Accessibility**:
  - [VIB5 Database on Figshare](https://doi.org/10.6084/m9.figshare.16903288)

## 32. **VQM24**: 
- **Description**: Provides quantum mechanical properties for 258,242 unique constitutional isomers and 577,705 conformers of varying stoichiometries, focusing on molecules composed of up to five heavy atoms from elements such as C, N, O, F, Si, P, S, Cl, and Br. The dataset utilizes methods including MMFF94, GFN2-xTB, $\omega$ B97X-D3/cc-pVDZ, and DMC@PBE0/ccECP/ccpVQZ, with calculations performed using Surge, RDKit, Crest, Psi4, and QMCPACK.
- **Data Accessibility**:
  - [Zenodo](https://doi.org/10.5281/zenodo.11164951)

## 33. WS22 Database
- **Description**: A comprehensive database featuring ten organic molecules with up to 22 atoms, encompassing 1.18 million geometries, offers a range of quantum mechanical properties. These properties have been calculated using various methods, such as the Wigner sampling approach, geometry interpolation scheme, B3LYP/6-31G*, and classical AIMD. The computations were performed using software including Newton-X and Gaussian 09.
- **Data Accessibility**:
  - [WS22 Database on Zenodo](https://doi.org/10.5281/zenodo.7032334)

## 34. xxMD17
- **Description**: Excited-state molecular dynamics  data set for four molecular systems chosen for their photochemical activity: azobenzene, malonaldehyde, stilbene, and dithiophene, calculated using Surface hopping dynamics, SA-CASSCF electronic theory and unrestricted KS-DFT (M069 meta-GGA and 6-31g) with a list of softwares including SHARC, OpenMolcas 22.06 and Psi4.
- **Data Access**:
  - [GitHub Repository](https://github.com/zpengmei/xxMD)
  - [Zenodo Repository](https://doi.org/10.5281/zenodo.10393859)

## Contributions

We welcome contributions! If you have new data sets or databases to add or updates to existing ones, please submit a pull request.


