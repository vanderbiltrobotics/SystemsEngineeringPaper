# VUR Systems Engineering Paper
---

This is the repository for the Vanderbilt Robotics Systems Engineering Paper.
This fulfils the requirements described in the rubric contained in <a href="https://www.nasa.gov/sites/default/files/atoms/files/2018_rulesrubrics_partiii.pdf#page=6">Part III of
the NASA RMC Rules</a>.

The LaTeX template used in this document was adapted from Vanderbilt 
Aerospace Design Laboratory's LaTeX template. (Thanks to Kurt Lezon for sharing
it with us!)

## Requirements

This entire document is written in LaTeX, so to compile it, you need a LaTeX 
compiler or IDE. Fortunately, 
<a href="https://www.quora.com/Whats-the-best-LaTeX-IDE">there are several 
for each platform.</a> It is not recommended you compile from the command-line
because doing so will allow you to more easily ignore the hundreds of errors 
you will inevitably have in compilation, and because an IDE will give you a 
pleasant, built-in, what-you-see-is-what-you-get PDF preview.

## Format

Each folder contains a designated portion of the paper. The document 
"SE Paper.tex" links to every other tex file in each folder, so, to compile 
the entire document, you only need to compile "SE paper.tex". 

Each figure is stored in "09_Figures". Make sure when you leave images in there
you name them something you're not easily going to forget.

## Procedure

Please don't complain about the numerous errors that occur at compilation. 
This paper's template was graciously given to us, and we didn't try to eliminate
the errors then because there were simply too many. Fortunately, however,
LaTeX documents read in-order, so they are relatively easy to debug. That 
being said, you can probably safely get away with being sloppy. We just ask 
that you make sure to sufficiently break your lines in tables and large blocks 
of text to ensure the person who has to edit your work later would *not* rather
kill themselves.
