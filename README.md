# Low Latency Approximate Adders

We provide MATLAB and Verilog Models of GeAr, and previously proposed adders (ACA-I, ETAII, ACA-II and GDA).

GeAr is a low latency Generic Accuracy Configurable Adder that provides a higher number of potential configurations compared to state-of-the-art approximate adders, thus enabling a high degree of flexibility and trade-off between performance and output quality.
These MATALB and Verilog models can allow software programmer as well as hardware designers to evaluate their code and design. To the best of our knowledge, this is the first open-source library of approximate adders that facilitates reproducible comparisons and further research and development in this direction across various layers of design abstraction.

In case of usage, please refer to our corresponding DAC 2015 publication:
Muhammad Shafique, Waqas Ahmad, Rehan Hafiz, Jörg Henkel, "A Low Latency Generic Accuracy Configurable Adder", in 52nd ACM/EDAC/IEEE Design Automation Conference & Exhibition (DAC), 2015.

#Features
All the MATLAB functions and hence the adders parameterizable and can be configured to construct any type of adder configuration.
The error probability function can be used to calculate the error probability of GeAr adder as well as following previous adders i.e. ACA-I, ETAII, ACA-II and GDA.
 
#Main Contributors
Muhammad Shafique: TU Wien, Austria
Waqas Ahmad:
Rehan Hafiz: ITU, Pakistan
Jörg Henkel: KIT, Germany
 
#Software Guide
The software directory contains two folders, MATLAB R2013a (containing MATLAB functions and codes) and ISE Design Suite 14.5 (containing VERILOG HDL codes). The MATLAB directory contains the functions of GeAr adder and previously developed adders like ACA-I, ETAII, ACA-II and GDA. It also contains the error probability calculation function. The details of input and output parameters of each function are mentioned in the function and also a text file is included. The ISE directory contains the codes of GeAr, ACA-I, ETAII, ACA-II and GDA for fixed configurations. Each adder has a text file that defines the configurations and inputs and outputs of the codes.
 
