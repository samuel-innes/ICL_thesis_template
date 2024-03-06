# ICL_thesis_template
LaTex template for theses at the Department of Computational Linguistics (ICL), Heidelberg University

*Note that it is not required to use this template for your thesis at ICL, it serves solely as a **suggestion**. Please check with your advisor whether they approve the use of this template.*

## How to install further LaTeX packages
1. Download the package from CTAN
2. See if the package already contains a .sty file. If not, do the instructions in the README to generate this file.
3. Transfer the folder to the correct path (/usr/local/texlive/2023basic/texmf-dist/tex) - Finder > Go > Go to folder
4. Run the command `sudo -H mktexlsr` to update the indexes
5. You're ready to go!

## Instructions for the template

1. **Installation**
    
    Clone this repository:
    `git clone https://github.com/juliakreutzer/ICL_thesis_template.git`

    Or fork it on GitHub and then clone your fork.

2. **Compilation**

    With `pdflatex` and `bibtex`: `pdflatex thesis.tex; bibtex thesis.aux; pdflatex thesis.tex`

3. **Modification**

    The template contains generic placeholders, make sure you change these in `thesis.tex`:
    - [ ] Your name
    - [ ] Your email address
    - [ ] Title of your thesis
    - [ ] The degree of the thesis (Bachelor/Master)
    - [ ] Date
    - [ ] Names of supervisor(s) and reviewers
    
    The references are collected in `references.bib`.
    
    Finally, fill the remaining sections with the actual contents of your thesis. 
    Feel free to change the LaTex template as well, it is just a suggestion.
    
4. **Problems and Suggestions**

    If you run into problems regarding compilation or the like, create an issue in this repository. 
    Even more importantly, if you have suggestions for improvements, create a pull request to share your insights with others.
    
**Best of luck for your thesis! :muscle:**
