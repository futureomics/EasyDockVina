A new GUI version is available with many new features, check out: https://youtube.com/watch?v=oqKsSJ_uWGs
<br/>
# EasyDockVina

/////////////////////////////////////////////////////////////////////////<br/>
<br/>

        - #EasyDockVina is a free tool to perform multiple receptor-ligand
          docking with AutoDockVina.	
        - Programmed By AhmedElTijani AKA S3cr3tSDN	
<br/>
/////////////////////////////////////////////////////////////////////////<br/>


[+] Tool Usage:

        EasyDockVina dock [parameters]

[+] Parameters:

        --receptor file.pdbqt                   Receptor should be prepared and in pdbqt format.
        --ligands ./ligands/                    Ligands folder, all ligands should be in pdbqt format.
        --config config.txt                     Config file should only contain search box center and size.
        --output docking_result.txt             All docking results will be written on the file specified.

[+] Example:

        EasyDockVina dock --receptor e2cr.pdbqt --ligands ./ligands/ --config config.txt --output results.txt
        
        
Config.txt file should contain only:<br/>
center_x = XXXXXX<br/>
center_y = YYYYYY<br/>
center_z = ZZZZZZ<br/>
size_x = XXXXXX<br/>
size_y = YYYYYY<br/>
size_z = ZZZZZZ <br/>


this tool will only work on windows machines, linux version is on the way.<br/>
Please report any bug to s3cr3tsdn@gmail.com<br/>
if you need help to configure EasyDockVina to run on a webserver, contact me at s3cr3tsdn@gmail.com<br/>

# Citation:

Ahmed ElTijani, Mazin Yousif Alsafi, & Ahmed Faisal Ahmed. (2019, September 21). EasyDockVina: Graphical Interface for Ligand Optimization and High Throughput Virtual Screening with Vina (Version 2.2). Zenodo. http://doi.org/10.5281/zenodo.3732170
