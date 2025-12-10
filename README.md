This repository contains the raw corner contribution data, organized by disorder+type > linear size.
For each critical point (percolation, multicritical, and generic), there are two disorder realizations, and for each of these there are 5 linear sizes. For each size, disorder realization, and shear angle, the data is divided into 10 files. 
Each data file contains the position-averaged corner contributions from 1,000 RTFIM samples.
The files are named ```scr-<L>-<n>-<i>.txt```, where $L$ is the linear size, $n$ gives the shear angle as $\theta=\tan^{-1}(1/n)$, and $i$ denotes the number out of 10.
The ```gap-stats``` directory contains the position-averaged line segment (1d) corner contributions for the same sets of samples.
