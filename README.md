 check out: 
<br/>
# EasyDockVina

[+] Tool Usage:

        EasyDockVina dock [parameters]

[+] Parameters:

        --receptor file.pdbqt                   Receptor should be prepared and in pdbqt format.
        --ligands ./ligands/                    Ligands folder, all ligands should be in pdbqt format.
        --config config.txt                     Config file should only contain search box center and size.
        --output docking_result.txt             All docking results will be written on the file specified.

[+] Example:

        EasyDockVina dock --receptor 1mq4.pdbqt --ligands ./ligands/ --config config.txt --output results.txt
        
        
Config.txt file should contain only:<br/>
center_x = XXXXXX<br/>
center_y = YYYYYY<br/>
center_z = ZZZZZZ<br/>
size_x = XXXXXX<br/>
size_y = YYYYYY<br/>
size_z = ZZZZZZ <br/>


this tool will only work on windows machines, linux version is on the way.<br/>

# Citation:

Ahmed ElTijani, Mazin Yousif Alsafi, & Ahmed Faisal Ahmed. (2019, September 21). EasyDockVina: Graphical Interface for Ligand Optimization and High Throughput Virtual Screening with Vina (Version 2.2). Zenodo. http://doi.org/10.5281/zenodo.3732170
