# Molecular dynamics of a cyclopropane
Structural bioinformatics project<br />
(Read the french report *report.pdf* for more details)

### Prerequisites
UNIX/shell environment<br />
Python3, Rscript

### Running the MD
* Force calculated using an **analytical derivative** :
```
$ python3 scripts/MD_cyclopropane_1.py
```
* Force calculated using a **numerical derivative** :
```
$ python3 scripts/MD_cyclopropane_2.py
```

The file results/MD_cyclopropane.dat is created.

### Plotting the results (Animation and Energies plots) :
```
$ Rscript scripts/MD_cyclopropane.R
```

The files anim_MD_forces.gif, anim_MD_traces.gif and Energies_MD.png are created.

### Authors
* **Hélène Kabbech** - Bioinformatics Master student (University of Paris Diderot)
* **Madeleine De Sousa Violente** - Bioinformatics Master student (University of Paris Diderot)

### License
January 2018
