# Primer Design with Primer3

<img src="./deploy/media/images/rush_university_with_logo.jpg">

### Resources
<img alt="datalad" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fpranavmishra90%2Fbadges%2Fmain%2FRush/BFI/datalad.json&color=3e4c75">
<img alt="docker" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fpranavmishra90%2Fbadges%2Fmain%2Fone-sided-badge/docker.json&color=3e4c75">
<img alt="python" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fpranavmishra90%2Fbadges%2Fmain%2FRush/BFI/python.json&color=3e4c75">
<img alt="jupyter" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fpranavmishra90%2Fbadges%2Fmain%2Fone-sided-badge/jupyter.json&color=3e4c75">
<img alt="anaconda" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fpranavmishra90%2Fbadges%2Fmain%2Fone-sided-badge/anaconda.json&color=3e4c75">
<img alt="gitea" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fpranavmishra90%2Fbadges%2Fmain%2Fone-sided-badge/gitea.json&color=3e4c75">
<img alt="pre-commit-enabled" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fpranavmishra90%2Fbadges%2Fmain%2Ftwo-side-status-badge/pre-commit-enabled.json&color=3e4c75">

## Project Details
This repository was created to provide our lab with a "self-hosted Primer Blast". [Primer Blast](https://www.ncbi.nlm.nih.gov/tools/primer-blast/) is an incredible tool that utilizes [Primer3](https://github.com/primer3-org) and the [Basic Local Alignment Search Tool (BLAST)](https://blast.ncbi.nlm.nih.gov/Blast.cgi). The National Institutes of Health offers everyone free access to this tool using NIH servers. Understandably, though, these resources are heavily utilized by people world-wide, leading to "long" wait times for computations.

With this repository, a user can have access to the Primer Blast with a few additional benefits:

- Faster results (dependant on your computer / server's hardware)
- Ability to save Primer Blast run information (NCBI's servers will delete results after a day)
- Free up NCBI's servers for others who do not have the computational power to run BLAST software.

## Feature wish-list (Roadmap)
As this is a personal side-project in our lab, there is no set timeline for deploying the following features. However, I will be listing a few ideas below which may help this project grow. Feature requests can be made by opening an issue ticket.

1. Incoming webhook to ingest FASTA sequences (e.g. send requests from Microsoft Teams to a listening server)
2. Outgoing webhook to send results (e.g. send results to the same Microsoft Teams user / channel)
3. GUI / primer3-plus interface

## License
Copyright © 2022 Pranav Kumar Mishra

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

-----

## References

### Citing this repository
If you are using this code, we would greatly appreciate it if you would cite this repository as in [citation.cff](./citation.cff).

### Primer3 and Primer3Plus
Untergasser A, Cutcutache I, Koressaar T, Ye J, Faircloth BC, Remm M and Rozen SG.
Primer3--new capabilities and interfaces.
Nucleic Acids Res. 2012 Aug 1;40(15):e115.

The paper is available at http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3424584/

Source code available at href="https://github.com/primer3-org.

### BLAST Programs

Altschul, S.F., Gish, W., Miller, W., Myers, E.W. & Lipman, D.J. (1990) "Basic local alignment search tool." J. Mol. Biol. 215:403-410. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/2231712?dopt=Citation)

Gish, W. & States, D.J. (1993) "Identification of protein coding regions by database similarity search." Nature Genet. 3:266-272. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/8790452?dopt=Citation)

Madden, T.L., Tatusov, R.L. & Zhang, J. (1996) "Applications of network BLAST server" Meth. Enzymol. 266:131-141. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/8743682?dopt=Citation)

Altschul, S.F., Madden, T.L., Schäffer, A.A., Zhang, J., Zhang, Z., Miller, W. & Lipman, D.J. (1997) "Gapped BLAST and PSI-BLAST: a new generation of protein database search programs." Nucleic Acids Res. 25:3389-3402. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/9254694?dopt=Citation)

Zhang Z., Schwartz S., Wagner L., & Miller W. (2000), "A greedy algorithm for aligning DNA sequences" J Comput Biol 2000; 7(1-2):203-14. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/10890397?dopt=Citation)

Zhang, J. & Madden, T.L. (1997) "PowerBLAST: A new network BLAST application for interactive or automated sequence analysis and annotation." Genome Res. 7:649-656. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/9199938?dopt=Citation)

Morgulis A., Coulouris G., Raytselis Y., Madden T.L., Agarwala R., & Schäffer A.A. (2008) "Database indexing for production MegaBLAST searches." Bioinformatics 15:1757-1764. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/18567917?dopt=Citation)

Camacho C., Coulouris G., Avagyan V., Ma N., Papadopoulos J., Bealer K., & Madden T.L. (2008) "BLAST+: architecture and applications." BMC Bioinformatics 10:421. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/20003500?dopt=Citation)

Boratyn GM, Schäffer AA, Agarwala R, Altschul SF, Lipman DJ, & Madden T.L. (2012) "Domain enhanced lookup time accelerated BLAST." Biol Direct. 2012 Apr 17;7:12. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/22510480?dopt=Citation)

Boratyn GM, Thierry-Mieg J, Thierry-Mieg D, Busby B, Madden T.L. (2019) "Magic-BLAST, an accurate RNA-seq aligner for long and short reads." BMC Bioinformatics. 2019 Jul 25;20(1):405. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/31345161)


[Full list of BLAST references on the NCBI website](https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=References)