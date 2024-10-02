# Trials and in silico simulations to predict daily photo-oxidative capacity under solar conditions: A case study on the inactivation of a oyster pathogenic bacteria, Vibrio harveyi

Cécile Blanchon<sup>1,2,3,4</sup>, Eve Toulza<sup>1</sup>, Christophe Calvayrac<sup>2,3</sup>, Stanislawa Eichendorff<sup>4</sup>, Gael Plantard<sup>4*</sup>

<sup>1</sup> IHPE, Univ Perpignan Via Domitia, CNRS, IFREMER, Univ Montpellier, Perpignan, France
<sup>2</sup> Biocapteurs Analyses Environnement, Université de Perpignan Via Domitia, 66000 Perpignan, France
<sup>3</sup> Laboratoire de Biodiversité et Biotechnologies Microbiennes (LBBM), Sorbonne Universités, CNRS, 66650 Banyuls sur Mer, France
<sup>4</sup> PROMES-CNRS UPR 8521, Process Material and Solar Energy, Rambla de la Thermodynamique, 66100 Perpignan, France

This git contains :
- the data file obtained by operating the photoreactor in batch mode: _**"Test.xlsx ’**_
- irradiation files for the cities of Bordeaux, Nantes and Montpellier
- the various matlab functions used to :
        - solve the material balances on the reactor with the various kinetic laws:_**"ResolBilan.m “**_ in batch and _**”ResolBilan_SimulationContinu.m ’**_ in continuous
        - optimise the calculation of the parameters of each kinetic law: _**‘Optimisation.m’**_
        - calculate the duration of the initial plateau based on batch experimental data: _**"InitialShoulder.m ’**_
        - modulate the feed rate for continuous reactor operation: _**"ResolBilan_SimulationDebit.m ’**_
        - calculate the average inactivation speed in the reactor: _**"AverageInactivationSpeed.m ’**_
- the MAIN containing the body of the code and allowing the simulations to be run on the basis of the various donations and experimental data: _**"CodeSimulationArticle_I_lisse.mlx ’**_
