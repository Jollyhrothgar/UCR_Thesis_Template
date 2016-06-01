# How to use
There are two areas: separated chapters, and all_in_one. all_in_one is
structured for peopel who prefer to have all figures and tables in one folder,
and all chapter .tex files in one area. This has the benefit that it is easier
to change around the thesis structure, or look at all your figures at onece,
without needing to do much editing.

Alternatively, if you prefer, there is separated_chapters. This is for people
that prefer more rigorous structuring to the latex document, with figures,
tables, and chapters explicitly organized into their own directories. For a very
large document, this may be preferable, or documents with naming overlap that
makes sense.

Either way, you have options.

Everything in your thesis is stiched together in the thesis.tex file. You must
modify this with the appropriate paths to whatever you add. All paths anywhere
in this package should be relative to the location of the Makefile, which should
be in the same directory as thesis.tex.

# Building

Assuming you have the standard latex linux environment installed, including
pdflatex and bibtex, this should work for you. This package was constructed
under the assumption that you are building in a linux-like environment.

To build, go to the ./thesis directory and execute the command "make"

To get rid of everything that was generated after running "make", type "make
clean" from ./thesis.

Enjoy!

# To Do

Add sample figure, sample table, sample citation, and sample cross-reference
