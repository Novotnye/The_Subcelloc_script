## The Subcelloc script

The Subcelloc script was created to automate the evaluation of the subcellular localization of a large number of proteins. It combines localization data obtained from the UniProKB database, as well as from PSORTb v.3.0.2 and Cello v.2.5. Additional information is provided by SignalP v.5.0 and TMHMM v.2.0, which predict the presence of a signal peptide and transmembrane helix, respectively. This script can be used to predict the subcellular localization of i) in silico proteomes (downloaded from UniProt) and ii) mass spectrometric data from bottom-up proteomics approaches. It was created in Anaconda (Python distribution) and optimized for use in MS Windows and Google Chrome. 

Please see our detailed **Guide 1 - Preprocessing and localization prediction by Subcelloc script**. The main script pipeline is in the folder **cell_location_pipeline** (available after publication in a scientific journal). For further analyses of proteins with ambiguous localization, please see **Guide 2 - Further data analysis**.








## The Subcelloc script was published in Applied and Environmental Microbiology Journal: Membrane Proteins and Proteomics of Cronobacter sakazakii Cells: Reliable Method for Identification and Subcellular Localization (https://doi.org/10.1128/aem.02508-21).

Members of the genus Cronobacter are responsible for severe infections in infants and immunosuppressed individuals. Although several virulence factors have been described, many proteins involved in the pathogenesis of such infections have not yet been mapped. This study is the first to fractionate Cronobacter sakazakii cells into outer membrane, inner membrane, periplasmic, and cytosolic fractions as the basis for improved proteome mapping. A novel method was designed to prepare the fractionated samples for protein identification. The identification was performed via one-dimensional electrophoresis-liquid chromatography electrospray ionization tandem mass spectrometry. To determine the subcellular localization of the identified proteins, we developed a novel Python-based script (Subcelloc) that combines three web-based tools, PSORTb 3.0.2, CELLO 2.5, and UniProtKB. Applying this approach enabled us to identify 1,243 C. sakazakii proteins, which constitutes 28% of all predicted proteins and 49% of all theoretically expressed outer membrane proteins. These results represent a significant improvement on previous attempts to map the C. sakazakii proteome and could provide a major step forward in the identification of Cronobacter virulence factors.
