# FLCore

**Core package of FLR, fisheries modelling in R.**

Version: 2.5.20130716

FLCore contains the core classes and methods for FLR, a framework for fisheries modelling and management strategy simulation in R. Developed by a team of fisheries scientists in various countries. More information can be found at http://flr-project.org/.

Author: FLR Team <flr-team@flr-project.org>

Maintainer: Iago Mosqueira, EC JRC. Ernesto Jardim, EC JRC.


## Installation

**TO INSTALL** this package, start R and enter:

	install.packages(repos="http://flr-project.org/R")

or, to install the development version

	library(devtools)
	install_github("FLCore", "flr)

**TO CITE** this package, start R and enter

	library(FLCore)
	citation("FLCore")

## Documentation

## Details

- Version: 2.5.20130716
- Date: 2013-07-16
- License: GPL (>= 2)
- Depends: R(>= 3.0), methods, grid, lattice, MASS
- Imports: stats, graphics
- URL: <https://github.com/flr/FLCore>

### Classes

#### Arrays
- FLArray
- FLCohort
- FLPar
- FLQuant
- FLQuantDistr
- FLQuantJK
- FLQuantPoint

#### Structures
- FLBiol
- FLGrowth
- FLIndex
- FLModel
- FLModelSim
- FLStock
- FLStockLen

#### Lists
- FLBiols
- FLCohorts
- FLComps
- FLIndices
- FLModelSims
- FLPars
- FLQuants
- FLSR
- FLSRs
- FLStocks

### Methods

Too many to list here.

## Downloads
- Packaged Source [FLCore_2.5.20130708.tar.gz](http://flr-project.org/Rdevel/src/contrib/FLCore_2.5.20130708.tar.gz)
- Windows Binary [FLCore_2.5.20130708.zip](http://flr-project.org/Rdevel/bin/windows/contrib/3.0/FLCore_2.5.20130708.zip)

## Feedback
Please report any bug or issue in the [FLCore issue tracker](https://github.com/flr/FLCore/issues)
