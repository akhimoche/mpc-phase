# Macropinocytosis Phase Analysis

## Description

Many biochemical processes in a cell depend on the extracellular material it absorbs. The transport of these substances such as antigens and mineral ions across the cell membrane is mediated by mechanisms of endocytosis, wherein the desired materials are captured in vesicles through deformation of the cell membrane. One mode of endocytosis is known as macropinocytosis, which has seen much study in recent years as its function in mammalian and amoebae cells has become more recognised. 

The general endocytic process involves a cell membrane that can be deformed using a dynamic mechanical device (e.g via deformation forces from a local network of cells) to internalise external fluids in a vesicle. In the case of macropinocytosis, a circular deformation develops into a 'cup' that retains the external fluid in a vesicle (macropinosome) by means of fusion at the top rims of the cup (see Figure 1). Unlike other endocytic methods which involve binding of the external molecules to surface receptors, macropinocytosis is driven by a ring of polymerised actin at the edges of the active site that is covered with a layer of PIP3 lipid  (see Figure 2). There is evidence to suggest that PIP3 inhibits the growth of the cell surface thereby leading to the cup formation, though the exact mechanism for formation is not fully known. 

<p align="center">
 <img src="/images/fig1.png" width="500" height="330" /> 
 <img src="/images/fig2.png" width="500" height="330"/>
</p>

This repository contains data of the chemcial concentrations present at the active site recorded during an observation of macropinocytosis, and the subsequent data analysis of various chemical combinations for potential two-component reaction-diffusion systems. 

## Methodology

The period of macropinocytosis studied was the final 60 seconds until closure of the cup. Fluorescent intensity values (corresponding to chemical concentration) were recorded in 3 second intervals at different geodesic distances from the PIP3 domain boundary, normalised for each cup. The factor by which the intensity increased or decreased was normalised relative to an inactive part of the membrane, taken to be the median intensity at 5 micrometers from the boundary (calculated for each cup studied).

To plot a phase diagram, the concentrations of chemicals present are plotted against each other across the range of time studied. The primary systems studied in this report were two-component systems involving PIP3 as this series of phase diagrams had easily recognisable non-linear phenomena present (such as Hopf bifurcations) and clear correlation between the dynamical variables considered (for example, see PIP3/Actin system in Figure 3). 

<p align="center">
 <img src="/images/fig3.png" width="500" height="330"/>
</p>

PIP3 is the lipid that covers the active site before the cell membrane undergoes deformation and so is likely to play a crucial role in the RD system that drives the cup formation. This is not to say there is no other interesting behaviour for other two-component systems involving different chemicals (see Myo1E/Actin in Figure 4) but we leave these for further work. Some other systems (e.g PTEN-PI34P2 in Figure 5) indicate there is no significant interaction between the chemicals.

<img src="/images/fig4.png" width="500" height="330" /> <img src="/images/fig5.png" width="500" height="330"/>

## Context
