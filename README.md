GridMAT-MD-parallel
===================

A parallel algorithm to calculate area per lipid headgroup (APL) and bilayer thickness in molecular simulations of lipid bilayers

This program is a parallelized version of the orginal GridMAT-MD developed by W. J. Allen, J. A. Lemkul and D. R. Bevan at Virginia Tech. The citation for the original publication is below.

W. J. Allen, J. A. Lemkul, and D. R. Bevan. (2009) "GridMAT-MD: A Grid-based Membrane Analysis Tool for Use With Molecular Dynamics." J. Comput. Chem. 30 (12): 1952-1958.

## Usage
* Follow the user-guide published on the Bevan Lab website, to setup the analysis script/parameter file. (a sample parameter file is provided in the source code) [GridMAT-MD](http://www.bevanlab.biochem.vt.edu/GridMAT-MD/)
* Add a new line to the parameter file ``` number_of_threads       <num_threads> ``` to specify how many threads to be used for the calculation.
* Run the script using ```perl GridMAT-MD-parallel.pl bilayer_analysis_param```
