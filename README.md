# Installation
Only tested with MacTeX, but will certainly work elsewhere.

First, make your local texmf/latex folder if it doesn't already exist:

    mkdir -p ~/Library/texmf/tex/latex

Next, clone this git repository to it:

    cd ~/Library/texmf/tex/latex
    git clone https://github.com/pschmied/psrc-latex

Finally, link the templates to TeXShop if you use it:

    ln -s ~/Library/texmf/tex/latex/psrc-latex/templates/psrc-report.tex \
    ~/Library/TeXShop/Templates/psrc-report.tex
    
    ln -s ~/Library/texmf/tex/latex/psrc-latex/templates/psrc-letter.tex \
    ~/Library/TeXShop/Templates/psrc-letter.tex
    
    ln -s ~/Library/texmf/tex/latex/psrc-latex/templates/psrc-memo.tex \
    ~/Library/TeXShop/Templates/psrc-memo.tex
