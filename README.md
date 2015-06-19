# Music Structure Analysis Framework - GPL version

This repo is complementary to [MSAF](https://github.com/urinieto/msaf) and it
contains algorithms that were originally published under a GPL license.

## Install

First, download the original [MSAF](https://github.com/urinieto/msaf).
Then, copy `setup.py` into the orignal MSAF folder (overwrite the original `setup.py`).
It might look something like this:
    
    $> cp msaf-gpl/setup.py msaf/

Copy all the algorithms into the original MSAF:

    $> cp -R msaf-gpl/algorithms/* msaf/algorithms/

Finally go to the original MSAF folder and install MSAF, like this:

    $> cd msaf
    $> python setup.py install

## Boundary Algorithms ##

* Constrained Clustering (Levy & Sandler 2008) (original source code from [here](http://code.soundsoftware.ac.uk/projects/qm-dsp))
* SI-PLCA (Weiss & Bello 2011) (original source code from [here](http://ronw.github.io/siplca-segmentation/))

## Labeling Algorithms ##

* Constrained Clustering (Levy & Sandler 2008) (original source code from [here](http://code.soundsoftware.ac.uk/projects/qm-dsp))
* SI-PLCA (Weiss & Bello 2011) (original source code from [here](http://ronw.github.io/siplca-segmentation/))
