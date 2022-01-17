
This file is the release of the c++ code for the expectation-Maximization algorithm for the method called Generative Topographic Mapping. This is a clustering method for continuous variables from dense data matrices, where the clusters are associated to constraints in order to induce their auto-organization on the plane. The resuling visualisation is available on a 3D view from opengl and embedded in a qt interface. If the implemented code for gtm and pca is able to retrieve the same map than the matlab code, the interface for the visualization is experimental and far from optimal. The code is from 2009 and was compiled for win95 and then win7, but the file "Projet1.exe" is still executable for win10 (not directly from recent wine on ubuntu 20.04), it may not allow saving changes, on the contrary to the available source code. <br />

One example of visualization after the training of the map from gtm for for the 150 iris of fisher from three classes (setosa, versicolor, virginica), with here 
the u-map as a surface where the elevation counts for the distance between the clusters, is just below.
<br />
<p align="center">
<img src="https://github.com/rpriam/gtm3d/raw/main/example/gtm3d_iris150.png"  width="500" height="400" /> 
</p>
<br />

&copy; All Rights Reserved. R.Priam (rpriam@gmail.com) 17/01/2022

To do <br />
improve the interface with an exising library <br />
move the code pca and gtm to a r package  <br />

Reference <br />
https://www.microsoft.com/en-us/research/wp-content/uploads/1998/01/bishop-gtm-ncomp-98.pdf <br />
https://publications.aston.ac.uk/id/eprint/1245/1/NCRG_98_024.pdf <br />
https://linkinghub.elsevier.com/retrieve/pii/S0925231215012795 <br />
