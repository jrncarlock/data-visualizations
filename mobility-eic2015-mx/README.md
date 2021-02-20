# MX_Mobility_EIC2015

This repository contains the processed mobility data from Mexico's INEGI Intercensal Survey 2015.

The data is downloaded from the Intercensal Survey 2015: http://en.www.inegi.org.mx/programas/intercensal/2015/default.html#Microdatos

Survey characteristics: sample size of 6.1 million homes; information to the national level, states, municipalities, and for each of the towns with 50,000 or more inhabitants, referred to March 15th, 2015.

The data description files are found in:
* Documentation tab --> Classifiers ZIP file: http://en.www.inegi.org.mx/contenidos/programas/intercensal/2015/doc/eic2015_catalogos.zip
* Microdata tab --> File Descriptor (FD) XLS file: http://en.www.inegi.org.mx/contenidos/programas/intercensal/2015/doc/eic2015_fd.xls

The final cleaned files are found in the final_mobility_data.zip file that contains:

Edgelist files:
- school_mob_mx_mun.csv
- school_mob_mx_st.csv
- work_mob_mx_mun.csv
- workl_mob_mx_st.csv

Data descriptor for the nodes codes:
- TC_MUNICIPIO_2015.xls

The edgelist files have the "origin-destine" structure with a "weight" related to the number of people moving from one place to another.

## Work mobility network (municipality level)

<center>
<img src="https://github.com/jrncarlock/MX_Mobility_EIC2015/blob/master/images/work_mobility_network_mun.png" width="800"/>
</center>

## School mobility network (municipality level)

<center>
<img src="https://github.com/jrncarlock/MX_Mobility_EIC2015/blob/master/images/school_mobility_netowrk_mun.png" width="800"/>
</center>

Visualizations made in *Cytoscape*. Links with a weight < 100 were removed.
