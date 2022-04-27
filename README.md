# LUPE
## LUPE Overview

## Repository Structure 
This repository is organized as follows:

* The [tools](./tools) directory contains the implementation of the different tools we developed:
	* [GAPI](./tools/GAPI): The [models](./tools/GAPI/weight/GAPI200_2) trained from D200_BIG dataset
	* [LUPE](./tools/LUPE): The LUPE tool including the trained [model](./tools/LUPE/myModel.h5)
* The [dataset](./dataset) directory contains the datasets described in the paper that we use to evaluate LUPE:
	* [D200_SMALL](./dataset/D200_SMALL): meta-data from 200 small projects
	* [D200_BIG](./dataset/D200_BIG): meta-data from 200 small projects
	* [D1200](./dataset/D1200): meta-data from 1200 
 projects	