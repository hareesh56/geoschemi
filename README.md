[![Release](https://img.shields.io/github/v/release/geoschem/geos-chem?label=Latest%20Release)](http://wiki.geos-chem.org/GEOS-Chem_versions)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1343546.svg)](https://doi.org/10.5281/zenodo.1343546)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/geoschem/geos-chem/blob/master/LICENSE.txt)

## Description

This repository contains the __GEOS-Chem science codebase__.  Included in this repository are:

  * The source code for GEOS-Chem science routines;
  * Scripts to create GEOS-Chem run directories;
  * Scripts to run GEOS-Chem tests;
  * Driver routines (e.g. `main.F90`) that enable GEOS-Chem to be run in several different implementations (as GEOS-Chem "Classic", as GCHP, etc.)

### Version 13.0.0 and later

GEOS-Chem 13.0.0 and later versions use this "Science Codebase" repository as a  submodule within the [GCClassic](https://github.com/geoschem/GCClassic) and [GCHP](https://github.com/geoschem/GCHP) repositories.

### Version 12.9.3 and prior

GEOS-Chem 12.9.3 was the last version in which this "Science Codebase" repository was used in a standalone manner.  For this reason, the latest release is frozen at 12.9.3. All future GEOS-Chem releases will be issued in the [GCClassic](https://github.com/geoschem/GCClassic) and [GCHP](https://github.com/geoschem/GCHP) repositories.

## User Manuals

Each implementation of GEOS-Chem has its own manual page.  For more information, please see:

* __GEOS-Chem "Classic":__ [http://wiki.geos-chem.org/Getting_Started_with_GEOS-Chem](http://wiki.geos-chem.org/Getting_Started_with_GEOS-Chem)

* __GCHP:__ [https://gchp.readthedocs.io](https://gchp.readthedocs.io)

* __WRF-GC:__ [http://wrf.geos-chem.org](http:/wrf.geos-chem.org)

## About GEOS-Chem

GEOS-Chem is a global 3-D model of atmospheric chemistry driven by meteorological input from the Goddard Earth Observing System (GEOS) of the [NASA Global Modeling and Assimilation Office](http://gmao.gsfc.nasa.gov/). It is applied by [research groups around the world](http://acmg.seas.harvard.edu/geos/geos_people.html) to a wide range of atmospheric composition problems. Scientific direction of the model is provided by the international [GEOS-Chem Steering Committee](http://acmg.seas.harvard.edu/geos/geos_steering_cmte.html) and by [User Working Groups](http://acmg.seas.harvard.edu/geos/geos_working_groups.html). The model is managed by the [GEOS-Chem Support Team](http://acmg.seas.harvard.edu/geos/geos_chem_support.html), based at Harvard University and Washington University with support from the US NASA Earth Science Division, the Canadian National and Engineering Research Council, and the Nanjing University of Information Sciences and Technology.

GEOS-Chem is a grass-roots open-access model owned by its [users](http://acmg.seas.harvard.edu/geos/geos_people.html), and ownership implies some responsibilities as listed in our [welcome page for new users](http://acmg.seas.harvard.edu/geos/geos_welcome.html). If you are interested in using GEOS-Chem, please contact the [GEOS-Chem Support Team](http://wiki.seas.harvard.edu/geos-chem/index.php/GEOS-Chem_Support_Team) who will send you instructions for joining the user community and accessing the code.
