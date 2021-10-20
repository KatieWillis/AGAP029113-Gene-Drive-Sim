# AGAP029113-Gene-Drive-Sim
___
This repository contains jupyter notebooks associated with the publication "Resistance to a CRISPR-based gene drive at an evolutionarily conserved site is revealed by mimicking genotype fixation" available at https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1009740.

This code is adapted from https://github.com/KatieWillis/DoubleDriveSimulator and we are currently using this to explore other questions. If you are interested in extending the code please get in touch.

Katie Willis1 and Austin Burt1.

1 Department of Life Sciences, Imperial College, Silwood Park, Ascot, SL5 7PY, UK

For correspondence: katie.willis16@imperial.ac.uk

___
## Requirements

* Jupyter notebook
* Julia 1.5 or above
* All dependencies can be installed by running the following code in julia from the location of the downloaded files to initiate the environment (This only needs to be done once)
```
using Pkg
Pkg.activate("./Environment/")
Pkg.instantiate()
```

The environment can loaded at the beginning of each jupyter session by running:
```
] activate "./Environment/"
```

And the required packages can be loaded by running:
```
using NBInclude
@nbinclude("./Environment/Setup.ipynb");
```
