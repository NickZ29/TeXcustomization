# TeXcustomization
Contains customized packages and preambles for .tex files. There are two ways you can use the custom package in your document. The first is to have the .sty file in your current working directory. This is method should be used when working in Overleaf. 

Alternatively, if using TeXlive (and the default directory tree setup), you may have the .sty in the ".../texlive/texmf-local/tex/latex" directory and any suitable subdirectories. After adding the .sty file to this directory for the first time, run "texhash" into the command line to update the TeXlive tree search.

One may then implement the code into their LaTeX code with the following formatting

\documentclass{article}

\input{.../mypreamble.tex}

\usepackage{mycommands}

% any additional packages or commands

\begin{document}

...

\end{document}

Additionally, there are a few options that come with the mycommands package (one of which the graph theory group will enjoy), though these require the "mycommands.sty" file to be altered. To make the appropriate adjustments, please the instructions laid out in this video:
https://youtu.be/dQw4w9WgXcQ?si=qtoZcTP7KGkK4jgY
