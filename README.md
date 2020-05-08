# Installation

 This project is intended to be run using either Matlab or Octave. More information regarding the installation process can be found [here](docs/installation.md).
 
# Workflow

 The recommended workflow for using the TASBE package is to process your data in three stages: 
 
   1. Creation of a ColorModel which translates raw FCS data to comparable unit data. <br /> 
   2. Using the created ColorModel for batch processing of experimental data. <br /> 
   3. Comparison and plotting of the results from analysis.  
 
Example files are provided that show how these stages typically work.

## Excel Interface
The workflow described above has been consolidated into a new Excel interface feature that provides a user-friendly bridge between raw FCS data and current TASBE data analysis tools. Users can document important aspects of their experiments without having to worry about writing Matlab code. More information can be found [here](docs/Excel_README.md).   

### Demo Video 
[![Alt text for your video](https://img.youtube.com/vi/EMQJlTAzuDU/0.jpg)](https://www.youtube.com/watch?v=EMQJlTAzuDU)
   
# Tutorials

  We have provided a collection of tutorials and examples in order to help users more easily use the TASBE package:
  
  * [Getting Started](docs/installation.md)
  * <a href="https://github.com/TASBE/TASBE/tree/master/docs/FlowCytometryDocumentation"> Introduction to Flow Cytometry </a> (not web formatted) 
  * [Creating a ColorModel](docs/color_model.md)
  * [Running Analysis](docs/analysis.md) 
  * <a href="https://github.com/TASBE/TASBE/tree/master/docs/Example%20Files"> Example Files </a>
  * <a href="https://github.com/TASBE/TASBEFlowAnalytics-Tutorial">Repository of tutorials, templates and example files</a>

# Additional Resources
* [TASBE Codebase](https://github.com/TASBE)

# Citation
**If you make use of the TASBE Flow Analytics package, please cite
the following publication:**

* Jacob Beal, Cassandra Overney, Aaron Adler, Fusun Yaman, Lisa Tiberio, and Meher Samineni. "TASBE Flow Analytics: A Package for Calibrated Flow Cytometry Analysis," ACS Synthetic Biology, 8(7), pp 1524--1529, May 2019


Users are encouraged to report any bugs using the Github Issue Tracker which can be found <a href="https://github.com/TASBE/TASBEFlowAnalytics/issues">here</a>.
