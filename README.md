# How to use
This is the UCR thesis template.  Workflow is separted into folders for each chapter. You can make directories, or not, beyond this.

Everything in your thesis is stiched together in thesis/thesis.tex. You must modify this with the appropriate paths to whatever you add. All paths anywhere in this package should be relative to the location of the Makefile.

# Building

Assuming you have the standard latex linux environment installed, including pdflatex and bibtex, this should work for you. This package was constructed under the assumption that you are building in a linux-like environment.

To build, go to the ./thesis directory and execute the command "make"

To get rid of everything that was generated after running "make", type "make clean" from ./thesis.

Enjoy!
