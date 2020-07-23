# In silico end-to-end protein-ligand interaction characterization pipeline: the case of SARS-CoV-2

In the last decades, the world has seen at least three highly pathogenic human coronaviruses: the severe acute respiratory syndrome coronavirus (SARS-CoV-1) in 2002, the Middle East respiratory syndrome coronavirus (MERS-CoV) in 2012 and the SARS-CoV-2 in 2019, leading to the COVID-19 disease. At the time of publication, several countries find themselves in a pandemic state with severe clinical, social and economical consequences, both short and long term, leading to over 600 thousand deaths and more than 14.5 million confirmed cases (as of July 21,2020). Currently, no effective antiviral drugs or vaccines are available in the market that specifically target SARS-CoV-2, despite recent efforts across the globe. To that end, there is an imperative need to develop effective protocols to help understand and characterize not only SARS-CoV-2, but future protein-related diseases, using in silico approaches.   

## Pymol - a key molecular visualization  tool 

In the first basic protocol, we provide an introduction to molecular visualization with the software PyMOL. The protocol covers a precursory explanation of the several tools required for basic 3D molecular visualization and also, a more useful approach to Structural Biology and Medicinal Chemistry such as exploring protein-ligand and protein-protein interactions as well as to produce publication quality figures. In the end, the user should expect an adequate understanding of the software before proceeding to the next protocols. 

## SWISS-MODEL as a tool for homology modeling

The second protocol tackles an important issue for in silico approaches, which is the need of reliable 3D structures. Although the number of 3D structures has been rapidly growing, several protein structures, such as membrane proteins, are difficult to obtain even with recent technological improvement. To adress this issue,
structural and computational biochemists use structure modeling techniques such as: comparative modeling, ab initio and threading methods. In this protocol, the most predominant method, comparative modeling, will be used. The user will learn how to build a 3D replica of the SARS-CoV-2 RNA polymerase using sequence similarities of previously known structures. In the end, the user will be able to use SWISS-MODEL as a homology modeling platform to obtain 3D structures of proteins of interest and thus, support future computational-based experiments. 

## Ligand-Protein docking using HADDOCK
The third protocol focuses on protein-ligand interactions, a very large field of interest especially when studying diseases. Usually, the aim of these studies is how do we determine which ligand, from a big database of pharmaceuticals, is the better fit for our protein of interest to achieve a given desired activity (e.g. inhibition of active sites). To that effect, HADDOCK is a free web-server tool capable of performing data-driven docking and providing interaction energy estimations between molecules. In this tutorial, we will perform three docking approaches using the apo form of the main protease of SARS-CoV-2 and a ligand. In the end, the user will possess an important tool to study binding energies between proteins of interest and/or possible drug candidates. 


## GROMACS - a tool for molecular dynamics simulation

In this fourth and final protocol, the reader will follow a standard workflow to perform molecular dynamics (MD) simulations using the GROMACS software package.
The target of this tutorial is the main protease of SARS-CoV-2 (MPro) and two alpha-ketoamide inhibitors (13b ligands) which possibly interact with the Mpro monomers A and B. Throughout the tutorial, the reader will examine several input and output files and, in a few cases, run a few scripts. However,
due to the time-consuming nature of MD, the reader will not perform any simulations, instead all files will be provided in the Molecular_Dynamics folder.
Please follow the worfklow and inspect the content of each file carefully.
