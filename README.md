# papers-polite-nool

Writing about Polite for: http://2016.splashcon.org/track/nool2016

To get some of the required bibliography files run: 

    ./get-biblio.sh

The `minted` package has an external dependence to Pygments that you install with: 

    easy_install Pygments
    
Once that's done, you compile with the -shell-escape option: 

    pdflatex -shell-escape paper.tex 

