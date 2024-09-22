# CLEANING CTU-13

This is a public repository of my attempt on cleaning and exploring the CTU-13 Dataset, made by the amazing team at the Artificial Intelligence Centre, Faculty of Electrical Engineering at the Czech Technical University in Prague. 

In this repository, I will only be exploring the first scenario, which consist of a Neris malware infecting a Windows XP machine. The dataset notes every communication this infected machine has with other hosts in the network.

Main cleaning steps that I did:
- Categorical data exploring (mapping values to more readable format)
- Null value handling
- Numerical data exploring (getting rid of outliers and other statistical shenanigans)
- Numerosity reduction
- Dimensionality reduction (using PCA)

More information of cleaning steps can be found inside the Jupyter Notebook file and the original dataset can be found in the credits section.

## Credits

"An empirical comparison of botnet detection methods" Sebastian Garcia, Martin Grill, Jan Stiborek and Alejandro Zunino. Computers and Security Journal, Elsevier. 2014. Vol 45, pp 100-123. http://dx.doi.org/10.1016/j.cose.2014.05.011

## Disclaimer

Yes, this is a class project.