# About

Comparing 3D structures of homologous RNA molecules yields information about sequence and structural variability. To compare large RNA 3D structures, accurate automatic comparison tools are needed. In this article, we introduce a new algorithm and web server to align large homologous RNA structures nucleotide by nucleotide using local superpositions that accommodate the flexibility of RNA molecules. Local alignments are merged to form a global alignment by employing a maximum clique algorithm on a specially defined graph that we call the ‘local alignment’ graph.

The algorithm is implemented in a program suite and web server called ‘R3D Align’. The R3D Align alignment of homologous 3D structures of 5S, 16S and 23S rRNA was compared to a high-quality hand alignment. A full comparison of the 16S alignment with the other state-of-the-art methods is also provided. The R3D Align program suite includes new diagnostic tools for the structural evaluation of RNA alignments. The R3D Align alignments were compared to those produced by other programs and were found to be the most accurate, in comparison with a high quality hand-crafted alignment and in conjunction with a series of other diagnostics presented. The number of aligned base pairs as well as measures of geometric similarity are used to evaluate the accuracy of the alignments.

# Installation

    git clone git@github.com:BGSU-RNA/R3DAlign.git
    cd R3DAlign
    # initialize FR3D submodule
    git submodule init
    git submodule update

# Credits

Developed by Ryan Rahrig.
Transferred to Github by Anton Petrov.