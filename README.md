# blast-binder

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/fomightez/blast-binder/master?filepath=BLAST%20on%20Command%20Line%20and%20Integrating%20with%20Python.ipynb)

*tl;dr:*  
Click any `launch binder` badge on this page to run command line-based BLAST inside your browser.

------

***BLAST: Basic Local Alignment Search Tool (BLAST+) command-line applications.***

This repository is for running BLAST+ in Jupyter environment provided by [MyBinder.org](https://mybinder.org/).  
Additionally, having BLAST+ working inside the Jupyter environment with interactive Python adds some convenient features that are illustrated. A utility script for moving command line-based BLAST results into Python is demonstrated.  

-------

Software
--------

The BLAST software will be installed already in each active session launched from this repo. The BLAST software is available directly from the National Library of Medicine under <a href="https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=Download">BLAST+ executables</a>.


**BLAST is a registered trademark of the National Library of Medicine**, see [here](https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=References).

The BLAST software references are listed [here](https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=References).

Users of BLAST+ here should probably cite:

- BLAST+: architecture and applications. Camacho C., Coulouris G., Avagyan V., Ma N., Papadopoulos J., Bealer K., & Madden T.L. (2008) BMC Bioinformatics 10:421. [PMID:20003500](https://www.ncbi.nlm.nih.gov/pubmed/20003500?dopt=Citation)

- BLAST: a more efficient report with usability improvements. Boratyn GM, Camacho C, Cooper PS, Coulouris G, Fong A, Ma N, Madden TL, Matten WT, McGinnis SD, Merezhuk Y, Raytselis Y, Sayers EW, Tao T, Ye J, & Zaretskaya I. (2013) Nucleic Acids Res. 41:W29-W33.[PMID: 23609542](https://www.ncbi.nlm.nih.gov/pubmed/23609542)


***Clarifying Software Attribution: I, Wayne, am not involved in the BLAST software at all. Those at the National Library of Medicine are the developers and distributors of BLAST. See their materials. I simply set up this repository to make the software useable on the command line without installation headaches.***

I, Wayne, did code a Python-based utility for use with the results from command line BLAST; it is available [here](https://github.com/fomightez/sequencework/tree/master/blast-utilities) and utilized in the notebooks in this repository to process the results and allow easily converting the results to other forms.

Usage
-----

This repository is set up to allow running the command line version of BLAST software after pressing the `launch binder` button above or below. The target use case is when you want to run custom BLAST or process a lot of sequences.

In the notebooks that can be launched, I have added some examples illustrating how to use the program and process the results easily with Python and convert to other forms. **Additionally, useful resources for using command line BLAST are in those notebooks.** Alternatively, the notebook with most of resources can be viewed statically [here](https://nbviewer.jupyter.org/github/fomightez/blast-binder/blob/master/BLAST%20on%20Command%20Line%20and%20Integrating%20with%20Python.ipynb). 

Obviously, web-based BLAST is also available. Here are some of my favorite web-based BLAST resources:

* [NCBI's main BLAST page](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
* [Saccharomyces Genome Database web interface](https://www.yeastgenome.org/blast-sgd)


Technical Details
-----------------

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.

Developed mainly from combining much of the binderized repo from [here](https://github.com/fomightez/qgrid-notebooks) with the ability to also run PatMatch, see [here](https://github.com/fomightez/patmatch-binder) for information about PatMatch and launchable Jupyter notebooks demonstrating its use.

Click this button below to begin using BLAST (or PatMatch, as well):

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/fomightez/blast-binder/master?filepath=BLAST%20on%20Command%20Line%20and%20Integrating%20with%20Python.ipynb)
