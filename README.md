# TTI – Tonoplast Topology Index

***Helena Kočová, George A. Caldarescu, Radek Bezvoda, Fatima Cvrčková***   
**This project is licensed under the [Creative Commons Attribution 4.0 (CC-BY-4.0)](LICENSE), 2025**

<p> BiorXiv link: <a href="https://doi.org/10.1101/2025.08.06.668875" target="_blank">doi.org/10.1101/2025.08.06.668875</a> </p>

<p> Publication link: <i>-will be added once available-</i></p>

<p> More sample images available at the <a href="https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD2226" target="_blank">repository</a>. </p>


## Abstract:

<p> The plant vacuole arises by orchestrated interplay of membrane trafficking, cytoskeletal rearrangements and a variety of signalling pathways. In the root, the characteristic large central vacuole develops by endomembrane reorganization occurring mainly in the transition zone. The vacuole's bounding membrane - the tonoplast - can be visualized in vivo using fluorescent protein markers. The Vacuolar Morphology Index (VMI) is widely accepted as a quantitative measure of vacuole structure. However, this metric has two drawbacks - it only reflects the size of the largest vacuolar compartment (missing therefore possible differences in the organization of smaller compartments), and its determination is labor intensive, limiting its use on large datasets. Here we present an alternative metric for describing vacuole organization, named the Tonoplast Topology Index (TTI), which overcomes the above-mentioned shortcomings of the VMI. The protocol for TTI determination is provided as a two-stage semi-automated procedure involving microscopic image analysis employing an ImageJ macro and subsequent processing of numeric data in the Jupyter Notebook environment, together with benchmarking image data. Since this implementation is freeware-based, platform-independent and (relatively) user-friendly, we hope it will find its use as a high throughput, added value alternative to the VMI metric.</p>


## Package contents:

* TTI version 1.0 user manual
* ImageJ macro: Stage1.ijm  
* Jupyter Notebook file: Stage2.ipynb
* Sample data folder containing sample images and expected outputs (including description)

**Required:** 

* A PC running a recent version of ***Fiji*** ([http://fiji.sc/Fiji](http://fiji.sc/Fiji)), ***Jupyter notebook*** (typically installed as a part of the ***Anaconda*** package, see Appendix 1) and a spreadsheet program such as ***Microsoft Excel*** or ***Libre Office Calc***.  
* Confocal microscopy images (preferably z-stacks) – either original files produced by the microscope´s software or standard \*.ome.tiff files (8-bit images are OK).  We are typically measuring atrichoblasts from isodiametric stage until the first cells with a large contiguous vacuole, which in our setup are about the length of \~1/2 screen.  


