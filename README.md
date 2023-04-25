# DIP
digital image processing

## Parts
This repo has assets and tex contents ...

## How to build?
cd to desired location where "DIP_assets" and "DIP_tex" dires are there, for
example it may be "~/Documents/Studies/ImageProcessing/DIP_Book". 

<pre>
    $ mkdir merged
    $ cd ./merged
    $ rsync -a ../DIP_tex/ ./
    $ rsync -a ../DIP_assets/ ./
    $ xelatex ./Book_test.tex
    $ xelatex ./Book_test.tex
</pre>


