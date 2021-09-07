# primitive: protein interaction and matching index that informs viral evaluation

<br/><br/>

> ### Traditional bioinformatics have been mainly driven by analysis of 1-D data, that is, nucleic acid sequence, or amino acid sequence. However, it is 3-D protein structure that finally decides whether and how much a virus such as SARS-COV-2 can attach and attach human host cells. Inspired and powered by the emerging technologies in 3-D protein structure prediction, we aim to develop mathematical metrics that could quantify how well the SARS-COV-2 spike protein matches the ACE-2 receptor and examine how that metrics is related to virus transmissibility. 

> ### There are a lot of tools (including TopMatch) that compute the structural similarity of two macromolecules (proteins and/or nucleic acids).  These tools take the 3D coordinates of the structures and tries to find a relative orientation of them that maximizes their overlap.  Overlap here refers to the set of atom pairs (one atom of a pair is from structure A, one is from structure B) that are close in space after optimal superposition.  For example, TopMatch calculates structure alignments and that could be used to compare structures.  Here, the term "match" is used to denote a considerable degree of similarity of two structures.

> ### However, we would like to study “docking“ rather than “matching” between two 3-D structures, that is, how well these structures bind/fit onto each other/have a certain shape complementarity. For this type of analysis, we might need protein-protein docking tools, like ClusPro, HADDOCK, etc.

![RBD](./images/binding.gif)
<br/><br/>  


### Reference:
> - Protein structure 3-D visualization: https://www.ncbi.nlm.nih.gov/guide/howto/view-3d-struct-prot/
> - A list of Structural alignment tools: https://proteopedia.org/wiki/index.php/Structural_alignment_tools
> - TopMatch: https://academic.oup.com/nar/article/48/W1/W31/5849903
> - VAST: https://www.ncbi.nlm.nih.gov/Structure/vastplus/docs/vastplus_help.html
