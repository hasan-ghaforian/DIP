# DIP
digital image processing

## Parts
This repo has assets and tex contents ...

## Prepare environment

<pre>
    $ rm -rf ./DIP_tex/
    $ rm -rf ./DIP_assets/
    $ git clone https://github.com/hasan-ghaforian/DIP.git
    $ cp -R ./DIP/ ./DIP_assets
    $ cd ./DIP_assets/
    $ git checkout assets
    $ cd ..
    $ mv ./DIP ./DIP_tex
</pre>

## How to build?

cd to desired location where "DIP_assets" and "DIP_tex" dires are there, for
example it may be "~/Documents/Studies/ImageProcessing/DIP_Book". 

<pre>
    $ rm -rf ./merged/
    $ mkdir merged
    $ cd ./merged
    $ rsync -a ../DIP_tex/ ./
    $ rsync -a ../DIP_assets/ ./
    $ xelatex ./Book_test.tex
    $ xelatex ./Book_test.tex
</pre>


