# UNIFI-50kW-RWT
Main repository for the 50 kw reference wind turbine designed by the university of Florence (Italy)

This repository contains the model data for the 50 kW reference small wind turbine developed by the Department of Industrial Engineering of Università degli Studi di Firenze (Italy).

The documentation for the turbine is accessible here: (https:// ****.pdf) CURRENTLY IN THE WORKS

Data in this repository includes:

Brief technical report of the complete aerodynamic, structural design and control algorithms (both pitch- and stall-based) 
OpenFAST aeroelastic model inputs for the stall and pitch-regulated turbine
CAD modeling of the entire turbine in SolidWorks and a complete model of the blade, both solid and only surface version.
As a part of this project, only the blade and tower are designed in detail, while the other turbine components are mock-ups. 

Requirements for using the OpenFAST model:

The OpenFAST input files are compatable with OpenFAST-v2.4.0 (https://kitefast.readthedocs.io/en/kitefast/). 
OpenFAST is developed and maintained by the National Renewable Energy Laboratory and can be dwnloaded here (https://github.com/OpenFAST/openfast/releases).
More information on installing and running OpenFAST is available in OpenFAST documention.
NREL's Reference OpenSource Controller (ROSCO 2.3 https://github.com/NREL/ROSCO) is required for the pitch regulated turbine. The sourceode and binaries can be found here: https://github.com/NREL/ROSCO/releases/tag/v2.3.0 
If the model will be updated for latter version of openfast this document will be updated accordingly. 

Design Updates:
We encourage the broader wind community to submit design updates either through Pull Requests or by reaching out to the authors. 

If you use this model in your research or publications, please cite the appropriate report as:

@techreport{UNIFI 50kW RWT,
author = {Alberto Nocentini, Francesco Papi, Giovanni Ferrara and Alessandro Bianchini },
institution = {Department of Industrial Engineering of Università degli Studi di Firenze (Italy)},
title = {UNIFI 50kW RWT: an explained-aero-servo-elastic reference model for studies on small wind turbines},
URL = {https://                .pdf},
Year = {2021}
}

author contacts: 
Alessandro Bianchini: 	alessandro.bianchini@unifi.it
Francesco Papi: 		fr.papi@unifi.it
Alberto Nocentini: 		al.nocentini@unifi.it




Copyright [2021] [Università degli Studi di Firenze]
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
