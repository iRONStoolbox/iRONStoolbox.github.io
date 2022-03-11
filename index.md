---
nav: false
---

[<img src="https://github.com/iRONStoolbox/iRONStoolbox/blob/master/iRONS/util/images/iRONS_logo_6.png" alt="iRONS logo" style="width:60%;" >](./index.md/)

## iRONS (interactive Reservoir Operation Notebooks and Software)

**Go to Github repository:** [iRONS](https://github.com/iRONStoolbox/iRONStoolbox)

**Build Status:** [![Build status](https://travis-ci.com/AndresPenuela/iRONS.svg?branch=master)](https://travis-ci.com/AndresPenuela/iRONS)

Python package that enables the simulation, forecasting and optimisation of reservoir systems. The package includes a set of interactive Jupyter Notebooks that demonstrate key functionalities through practical examples, and that can be run in the Jupyter environment either locally or remotely via a web browser. These links are two examples, just click on them so you can play with them online:

[Calibration and evaluation of a rainfall runoff model](https://mybinder.org/v2/gh/AndresPenuela/iRONS/HEAD?urlpath=notebooks/iRONS/Notebooks/A%20-%20Knowledge%20transfer/2.a.%20Calibration%20and%20evaluation%20of%20a%20rainfall-runoff%20model.ipynb)
  
[Recursive decisions and multiobjective optimisation](https://mybinder.org/v2/gh/AndresPenuela/iRONS/HEAD?urlpath=notebooks/iRONS/Notebooks/A%20-%20Knowledge%20transfer/3.a.%20Recursive%20decisions%20and%20multi-objective%20optimisation.ipynb)

## Contents:
- [KT Notebooks](KT_Notebooks.md/)

- [Contact](contact.md/)

**The core functions**

The iRONS package provides a set of Python functions implementing typical reservoir modelling tasks, such as: estimating inflows to a reservoir, simulating operator decisions, closing the reservoir mass balance equation – in the context of both short-term forecasting and long-term predictions.

**The notebooks**

iRONS is based on the use of interactive Jupyter Notebooks (http://jupyter.org/). Jupyter Notebooks is a literate programming environment that combines executable code, rich media, computational output and explanatory text in a single document. 
The notebooks included in iRONS are divided in two sections:

**A.	Knowledge transfer:** A set of simple examples to demonstrate the value of simulation and optimisation tools for water resources management – i.e. why one should use these tools in the first place. 

**B.	Implementation:** A set of workflow examples showing how to apply the iRONS functions to more complex problems such as: generating inflow forecasts through a rainfall-runoff model (including bias correcting weather forecasts); optimising release scheduling against an inflow scenario or a forecast ensemble; optimising an operating policy against time series of historical or synthetic inflows.

### Quick Start
Click on the button below to open iRONS on MyBinder.org so you can run, modify and interact with the Notebooks online. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AndresPenuela/iRONS.git/master)

In the section **A - Knowledge transfer** you can start with the Notebook **iRONS/Notebooks/A - Knowledge transfer/1.a. Simple example of how to use Jupyter Notebooks.ipynb**. 

In the section **B - Implementation** you can start with the Notebook **iRONS/Notebooks/B - Implementation/1.a. Downloading ensemble weather forecasts.ipynb**. 

**To install iRONS locally:** `pip install irons`

### Citation ###
Peñuela, A., Hutton, C., Pianosi, F. (2021) An open-source package with interactive Jupyter Notebooks to enhance the accessibility of reservoir operations simulation and optimisation. Environmental Modelling & Software, 145(105188). https://doi.org/10.1016/j.envsoft.2021.105188

### Acknowledgements
This project was funded by the Engineering and Physical Sciences Research Council (EPSRC), grant EP/R007330/1

### License
Copyright (C) 2021 Andres Peñuela and Francesca Pianosi. iRONS is released under the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

&nbsp;
<div class="row">
  <img src="logo-full-colour.png" alt="Uni logo" style="width:20%;" hspace="00">
<div >
