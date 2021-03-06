OpenVA_Pipeline
===============
[![image](https://img.shields.io/pypi/v/openva_pipeline.svg)](https://pypi.org/project/openva_pipeline/)
[![image](http://readthedocs.org/projects/openva-pipeline/badge/)](http://openva-pipeline.readthedocs.io/)
[![Travis-CI Build Status](https://travis-ci.org/verbal-autopsy-software/openva_pipeline.svg?branch=master)](https://travis-ci.org/verbal-autopsy-software/openva_pipeline)

Automates the processing of verbal autopsy (VA) data from an ODK Aggregate
server, through the openVA Pipeline middleware, and ending with a DHIS2 server
(with the [VA module](https://github.com/SwissTPH/dhis2_va_draft)). VA data are
analyzed using the [openVA
package](https://github.com/verbal-autopsy-software/openVA) in **R**, which is
demonstrated with code for an RShiny app in the [OpenVA_RShiny
repository](https://github.com/verbal-autopsy-software/shinyVA) and described in a
[vignette](https://github.com/verbal-autopsy-software/shinyVA/blob/master/shiny-openVA-vignette.pdf).

## Getting Started

The OpenVA Pipeline has been designed for (and tested on) Ubuntu LTS 16.04.
The steps to install and configure the pipeline can be found in
`docs/setup.md`. To make the installation easier, there is also a bash shell
script `install_software.sh` that installs all of the necessary software (the
script requires the `sudo` password).

<!-- The documentation can also be found on [Read the Docs](https://openva-pipeline.readthedocs.io/en/latest/): -->

<!-- - [**Software Requirements**](https://openva-pipeline.readthedocs.io/en/latest/software.html)  -->
<!-- - [**Installation Guide**](https://openva-pipeline.readthedocs.io/en/latest/install.html) -->
<!-- - [**Pipeline Configuration**](https://openva-pipeline.readthedocs.io/en/latest/config.html) -->

## License
GNU General Public License v3.0

----

## Licenses for Included Libraries

The openva\_pipeline\ packages includes two libraries in openva\_pipeline/openva\_pipeline/libs:
`ODK-Briefcase-v1.12.2.jar` and `smartva`.  [ODK Briefcase](https://github.com/opendatakit/briefcase) 
is a tool in the Open Data Kit (ODK) Software Suite, and is open-source software available 
under the Apache 2.0 license (see [ODK_Briefcase_LICENSE](./ODK_Briefcase_LICENSE).  `smartva` is
is a closed-source binary packaged available for download from the 
[The Institute for Health Metrics and Evaluation (IHME)](http://www.healthdata.org/verbal-autopsy/tools) and 
is **NOT** included under the above licenses.
