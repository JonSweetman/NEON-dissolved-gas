NEON Dissolved Gas
================

<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- ****** Description ****** -->
This package is for calculating dissolved gas concentrations in surfac water samples from reference air and water equilibrated gas samples.

<!-- ****** Usage ****** -->
Usage
-----

The functions in this package have the following purpose: (1) to format downloaded data, and (2) to calculate dissolved gas concentrations in surface water (mol L-1) from reference air and equilibrated air (ppmv) concentrations. See help files for individual functions for details. The general flow of using this package is:

1.  download data from the NEON data portal, into location "myDataPath"
2.  sdg\_data &lt;- def.format.sdg(dataDir = "myDataPath"), returns a data frame called sdg\_data
3.  sdg\_calc &lt;- def.calc.sdg(sdg\_data), returns a data frame called sdg\_calc with molar concentrations appended as columns

<!-- ****** Calculation Summary ****** -->
Calculation Summary
-------------------

<img src="sdg_1.png" width="700px" />

<img src="sdg_2.png" width="700px" />

<!-- ****** Acknowledgements ****** -->
Credits & Acknowledgements
--------------------------

<!-- HTML tags to produce image, resize, add hyperlink. -->
<!-- ONLY WORKS WITH HTML or GITHUB documents -->
<a href="http://www.neonscience.org/"> <img src="logo.png" width="300px" /> </a>

<!-- Acknowledgements text -->
The National Ecological Observatory Network is a project solely funded by the National Science Foundation and managed under cooperative agreement by Battelle. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.

<!-- ****** License ****** -->
License
-------

GNU AFFERO GENERAL PUBLIC LICENSE Version 3, 19 November 2007

<!-- ****** Disclaimer ****** -->
Disclaimer
----------

*Information and documents contained within this pachage are available as-is. Codes or documents, or their use, may not be supported or maintained under any program or service and may not be compatible with data currently available from the NEON Data Portal.*
