# MakeMeLaTeX
A simple and easy-to-use python code for LaTeX file template creating.

## Functioning

The concept of MakeMeLaTeX si simply to create a ".tex" file and to write in it the preamble of the document, in a nutshell :
- the packages that will be used
- the author
- the date
- the title

To choose which package will be written in the ".tex" document, the python code will ask questions to which the answer is y(es) or n(o), for instance to the question "Graphs, shemas ?", if the answer is "y", then the package "tikz" will be added, if the answer is "no", the package will not be added.

The questions can be removed from the Python code or some questions can be added as well.

## Installation

To use MakeMeLaTeX, you can either download the Python code and execute it with Python3 from the directory in which it is or you can add it to your commands in your terminal after you have download it.

### Downloading and executing

To download it and execute it, simply open a terminal, enter the directory in which you want this code to be and type this :

    $ git clone https://github.com/Crowerade/MakeMeLaTeX  
    $ python3 makeme

Of course this requires python3.

Once you have done that, you can answer the questions and the code will generate the ".tex" file.

### Turning it into a command

You may want to turn the code into a command if you don't want to type over and over the path to the Python code. If it is added as a command, then you will just have to type in your command-line `makeme`, the questions will appear and once you have answered them the LaTeX file will be generated in the directory you are currently in.

In order to do that, open a terminal and type in :

    $ cd MakeMeLaTeX
    $ sudo mv makeme /bin
    $ cd /bin
    $ sudo chmod +x makeme
    
And you are ready to go !
