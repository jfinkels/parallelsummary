Brief summary of research on highly parallel approximation algorithms
=====================================================================

This file was last updated on 24 July 2013.

Downloading
-----------

This paper can be found at https://github.com/jfinkels/parallelsummary.

To download the paper using [Git][1], run

    git clone git://github.com/jfinkels/parallelsummary

[1]: http://git-scm.com

A somewhat recent compiled version of this work should be available at
http://cs-people.bu.edu/jeffreyf/files/parallelsummary.pdf, but I can't
guarantee that that will always be up to date, since I compile and upload it
manually.

Compilation dependencies
------------------------

Besides `pdflatex`, compile-time dependencies include the following LaTeX
packages:

* `complexity`

On Ubuntu 11.04, 11.10, 12.04, or 12.10, the necessary system packages which
contain these LaTeX packages are:

* `texlive-science`

To install them, run

    sudo apt-get install texlive-science

Compiling
---------

To compile the document, run

    pdflatex parallelsummary
    bibtex parallelsummary
    pdflatex parallelsummary
    pdflatex parallelsummary

The output is `parallelsummary.pdf`, and can be viewed with any PDF reader.

Copyright
---------

Copyright 2013 Jeffrey Finkelstein.

Except where otherwise noted, both the LaTeX markup and the content of the
article are made available under the terms of the Creative Commons
Attribution-ShareAlike 3.0 license,
https://creativecommons.org/licenses/by-sa/3.0/.

Contact
-------

Jeffrey Finkelstein <jeffrey.finkelstein@gmail.com>
