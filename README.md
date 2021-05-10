# malapportionment_shared
Data and GerryChain code for malapportionment analysis

Currently this just has some sample outputs of short ReCom chains run on Washington with 2010 and 2015-2019 average ACS population data. The WA_Enacted_ReCom_Test folder has 10k steps from a run starting at the enacted Congressional plan, balanced on the 2010 population, while the other two contain short runs attempting to optimize for both population columns. The output files are: 

* pops_k.csv: The 2010 population of each district
* proj_pops_k.csv: The ACS updated population of each district
* UR_k.csv: The percentage of the 2010 population of the district coming from urban census blocks, as classified by the census (technical definition: https://www.federalregister.gov/documents/2011/08/24/2011-21647/urban-area-criteria-for-the-2010-census)
* egs_k, hmss_k, mms_k: Partisan symmetry statistics applied to the urban vs. rural data. Probably not useful. 
* map_k.png Images of the kth map of the chain. 

