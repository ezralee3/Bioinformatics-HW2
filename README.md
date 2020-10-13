# Bioinformatics-HW2

Team Members:
Willy Deng, Ezra Lee, Ivan Zundel\

You will need to import the following libraries:

from Bio import Alphabet\
from Bio.Alphabet import Reduced\
from Bio.Alphabet import IUPAC\
from Bio.Seq import Seq\
from Bio import SeqIO\
import random\
from random import seed\
from random import randint\
from random import choice\
import numpy as np\
from numpy.random import choice\
import pandas as pd\
import sys\
import copy\
import statistics\
import matplotlib.pyplot as plt\
\
The parameters are fastaFileName, selection percentage, population size, mutation rate (percentage), crossover cutoff (percentage), and stop criteria generation\
\
python hw2.py 6ezq.fasta.txt 0.05 100 0.001 0.5 200\
\
This is for high mutation rate:\
\
python hw2.py 6ezq.fasta.txt 0.05 100 0.3 0.5 200\
\
\
We used a smaller fasta file as the time complexity was about O(n^4)\
Our program was not efficient enough to do an entire FASTA file.\
\
The command above will generate and display 3 graphs and save them.\
\

\f1\b0 Source
\f0\b :\

\f1\b0 https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_SciPy_Cheat_Sheet_Linear_Algebra.pdf
\f0\b \

\f1\b0 https://stackoverflow.com/questions/2407398/how-to-merge-lists-into-a-list-of-tuples
\f0\b \
\pard\pardeftab720\partightenfactor0

\f1\b0 \cf0 https://stackoverflow.com/questions/6505008/dictionary-keys-match-on-list-get-key-value-pair
\f0\b \

\f1\b0 https://stackoverflow.com/questions/9622163/save-plot-to-image-file-instead-of-displaying-it-using-matplotlib\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 https://www.r-bloggers.com/ants-snakes-and-the-hydrophobic-polar-model/\
\pard\pardeftab720\partightenfactor0
\cf0 https://matplotlib.org/devdocs/gallery/subplots_axes_and_figures/subplots_demo.html\
}
