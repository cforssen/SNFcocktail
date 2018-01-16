***********
SNFcocktail
***********

Fysik, statistik och lite artificiell intelligens - en bild av den moderna ingenjören
  ===========================================================
:Author: Christian Forssen (christian.forssen@chalmers.se)

Detta repo innehåller den pythonkod som användes för en presentation
på SNF cocktail party 2018-01-18. Publiken var studenter på Chalmers
program i Teknisk fysik och Teknisk matematik.

Min förhoppning är att materialet kan vara intresseväckande och jag
vill uppmana de intresserade att själva installera python och de
moduler som behövs för att sedan kunna testa de exempel som visades.

Nedan installationsinstruktioner med mera på engelska.

Installation
------------

Download the repo from github::

    git clone https://github.com/cforssen/SNFcocktail.git

The scripts depend on several scientific modules (see
the list in environment.yml) and require a python3.5 installation. 

Dependencies are best installed using ``conda`` by creating
a virtual environment:

    conda env create
    source activate SNF-env

 Note that we employ a very broad list of packages in this notebook.
 After all, we explore several different application areas. The core
 packages are numpy and matplotlib, while the others are used for the
 various examples. It could happen that some packages are not included
 in the conda default channel and that the above installation
 fails. This should be solved by adding the
 [conda-forge](https://conda-forge.org/) channel: 

    conda config --add channels conda-forge

To deactivate virtual environment::

    source deactivate


Code overview
-------------

``SNF_presentation.ipynb`` ......... Presentation as a jupyter ipython
notebook

``SNF_presentation_extra.ipynb`` ......... Some extra material,
figures, etc.

``Keras_Addition_rnn.ipynb``  ......... TensorFlow example, addition
of integers in string format.

``environment.yml`` ... Package dependencies

``LICENCE.txt`` .............. MIT License

``README.rst`` .......... This.


Support
-------

For questions regarding this software, feel free to e-mail the main author.

